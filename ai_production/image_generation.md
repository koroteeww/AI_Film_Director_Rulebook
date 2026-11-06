# Image generation for continuity

A frame is an asset with a job in a planned shot. Approve its composition, world state and implications for movement before committing to motion generation. Use the [staging rules](../rulebooks/04_mise_en_scene.md), [camera rules](../rulebooks/03_cinematography.md) and [lighting rules](../rulebooks/05_lighting_and_color.md) to review it.

## Build and use reference sheets

| Sheet | Required anchors | Acceptable variants |
| --- | --- | --- |
| Character | Stable identity ID, face and silhouette, distinguishing features, posture baseline | Approved angles and expressions for review. Keep the actual generation reference set small. |
| Costume | Version, layers, closure, fabric, palette, accessories | Authorized garment, wear and wetness states with beat IDs |
| Location | Floor plan, fixed openings, major surfaces, light sources and geography | Approved camera views, season or time-of-day versions |
| Prop | ID, visible dimensions, material, symmetry, ownership and state | Open/closed, held/set down, damaged/intact where motivated |
| Look | Delivery aspect, palette, camera and lighting intent, hero still | Planned variation by viewpoint or beat |

## Frame selection and prompt structure

1. Set role and state. Use **start** for the opening appearance, **end** for a necessary reachable outcome, and **intermediate** for an important panel or approved reference when the mode can use it.
2. Bind reference assets to identity, outfit, location, prop, composition or light. Distinguish the features to preserve from the permitted changes.
3. Describe the subject, pose, gaze, grip, geometry and relative layers. Specify camera position, frame boundaries, focus, world-space light and aspect ratio. Give a concrete visible expression.
4. Compare the resulting frame to the approved map and shots. Retain the frame ID, source asset IDs, version, prompt and acceptance note.

A dedicated start/end pair is useful when both endpoints matter and the path between them is physically plausible. A first frame with identity or location references can preserve the stable world while giving performance more freedom. A midpoint board may be useful editorially even when the selected generator cannot ingest it. See the [Seedance capability research](../research/seedance_research.md#mode-distinctions) for dedicated roles and prompt-led references.

For each pair check facing and gaze, prop hand and state, real geometry, shot size, camera change, shadows, object trajectories and timing. Revise the endpoint or divide the shot when one clip cannot express the change coherently. Avoid baking captions or credits into shot assets when the edit needs clean frames.
