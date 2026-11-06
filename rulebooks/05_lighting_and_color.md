# 05 · Lighting and color

Plan light as part of the scene's physical and emotional design. Track where it comes from, how it falls, the areas it should reveal, the white-balance intention and its authorized changes. Use concrete effects such as shadow edge, highlight position, readable silhouette and color contrast in generation prompts.

Russian terms include рисующий свет (key), заполняющий свет (fill), контровой свет (back or rim light), светотеневой рисунок (light-and-shadow pattern), цветовая температура (color temperature), and цветовое решение (color design). The VGIK sample program and ARRI Russian-edition listing provide reading paths. [SRC-VGIK-CIN](../sources/bibliography.md#src-vgik-cin) · [SRC-ARRI-RU](../sources/bibliography.md#src-arri-ru)

## Rules

### LGT-001

**Motivate the visible light** · established technique · priority 1 · high confidence

Start with a plausible source in the scene, or a clearly intended stylized lighting system. Specify how it illuminates surfaces and performers.

**Why it works.** Consistent direction and quality make spatial relations and a change in light intelligible.

**Apply.** New locations and cross-angle frame generation. **Exception.** An expressionist change can break naturalism. Record its beat, effect and visual logic.

**Example.** A side window supplies soft daylight from world east across both angles. **Common mistake.** Recreating camera-left light in the reverse even though the window has changed screen side.

**LLM action.** Anchor source position and direction in world space. Derive screen effects after choosing camera position. **Check.** Across cuts, trace shadow and highlight direction to the mapped source or documented stylization.

**Origin.** ARRI source roles and ASC set-lighting practice. [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light) · [SRC-ASC-BURUM](../sources/bibliography.md#src-asc-burum) · [SRC-VGIK-CIN](../sources/bibliography.md#src-vgik-cin)

**Related.** [LGT-002](05_lighting_and_color.md#lgt-002), [LGT-004](05_lighting_and_color.md#lgt-004), [LGT-007](05_lighting_and_color.md#lgt-007), [LGT-010](05_lighting_and_color.md#lgt-010), [MIS-001](04_mise_en_scene.md#mis-001)

### LGT-002

**Assign key, fill, and separation by function** · established technique · priority 1 · high confidence

Use key for the dominant modeling light, fill for shadow control, and back, edge or background light where separation is needed.

**Why it works.** Independent functions help tune form, contrast and legibility. A single source and bounce can serve multiple functions.

**Apply.** Portraits, dialogue and hard-to-read silhouettes. **Exception.** A silhouette, flat wash or single-source effect may be the goal. Omit roles that would weaken it.

**Example.** A window models the face. Wall bounce keeps eyes readable. A lighter wall separates the dark costume without a rim. **Common mistake.** Assuming every subject needs three conspicuous sources.

**LLM action.** Describe each function in terms of source, relative level and visible effect. Allow one source to cover several roles. **Check.** The viewer sees the intended planes, shadow detail and separation without distracting extra shadows.

**Origin.** ARRI handbook and Burum's professional demonstration. [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light) · [SRC-ASC-BURUM](../sources/bibliography.md#src-asc-burum)

**Related.** [LGT-001](05_lighting_and_color.md#lgt-001), [LGT-003](05_lighting_and_color.md#lgt-003), [LGT-005](05_lighting_and_color.md#lgt-005), [LGT-010](05_lighting_and_color.md#lgt-010)

### LGT-003

**Define the contrast ratio you mean** · technical constraint · priority 2 · high confidence

Name what is being compared. A source key-to-fill ratio and a lit-to-shadow subject ratio describe different measurements. Two stops is a fourfold ratio in a linear exposure measure.

**Why it works.** Explicit measurement avoids mismatched targets and false precision across views.

**Apply.** Contrast specifications, on-set references, and exposure matching. **Exception.** For generated images without a calibrated workflow, state a qualitative target and use reference frames or scopes in a known space.

**Example.** Record shadow-side reference exposure roughly two stops below the lit-side reference, with a consistent metering method. **Common mistake.** Giving a 4:1 number without defining what was measured or deriving it from display-code values directly.

**LLM action.** Use relative shadow depth and sample areas. Store measured stops only where the measurement method and color pipeline are known. **Check.** Compare the selected reference areas under equivalent conditions and ensure important texture remains readable.

**Origin.** Lighting role separation in ARRI and exposure arithmetic. [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light) · [SRC-ASC-BURUM](../sources/bibliography.md#src-asc-burum) · [SRC-BMD-MATCH](../sources/bibliography.md#src-bmd-match)

**Related.** [LGT-002](05_lighting_and_color.md#lgt-002), [LGT-006](05_lighting_and_color.md#lgt-006), [LGT-010](05_lighting_and_color.md#lgt-010), [LGT-012](05_lighting_and_color.md#lgt-012)

### LGT-004

**Coordinate practicals with off-camera support** · established technique · priority 2 · high confidence

Record visible practical fixtures and their apparent effect, then add plausible off-camera support if required for the frame.

**Why it works.** A visible lamp can motivate color and direction while controlled support protects faces and background detail.

**Apply.** Interiors, night exteriors and scenes where a fixture changes state. **Exception.** A practical may read as decor without contributing much light. Leave it subdued if its output is irrelevant.

**Example.** A warm desk lamp glows in frame and a soft nearby source extends its direction across the face. **Common mistake.** Brightening the lamp but leaving the adjacent table completely unaffected in a realistic shot.

**LLM action.** Set fixture position, on/off state, color, bloom and affected surfaces. Store the supported direction and side. **Check.** Check fixture and spill consistency and whether a switched state changes the planned surfaces.

**Origin.** ARRI background-light and source guidance plus ASC examples. [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light) · [SRC-ASC-BURUM](../sources/bibliography.md#src-asc-burum)

**Related.** [LGT-001](05_lighting_and_color.md#lgt-001), [LGT-002](05_lighting_and_color.md#lgt-002), [LGT-007](05_lighting_and_color.md#lgt-007), [LGT-010](05_lighting_and_color.md#lgt-010), [LGT-011](05_lighting_and_color.md#lgt-011), [MIS-007](04_mise_en_scene.md#mis-007)

### LGT-005

**Control hard and soft light by apparent source size** · technical constraint · priority 1 · high confidence

With the subject and shadow-receiving surface geometry held fixed, a larger apparent source produces a wider shadow-edge transition. A small apparent source produces sharper shadows.

**Why it works.** Shadow-edge quality changes texture, form and the feel of a space independently of brightness.

**Apply.** Specifying sun, diffuse sky, windows, bounce and fabric texture. **Exception.** Mixed hard and soft components can be intentional. Give each a separate source and effect.

**Example.** A broad nearby window gives a gradual cheek shadow, while direct sun marks a harder window shape. **Common mistake.** Equating dim light with soft light or requesting a large close source with uniformly razor-sharp penumbrae.

**LLM action.** Describe apparent source size, distance relationship, shadow edge and affected surface. Keep quality distinct from level. **Check.** Inspect transition width and direction on a stable surface and the subject across frames.

**Origin.** ASC Light Quality 101 and ARRI hard/soft examples. [SRC-ASC-QUALITY](../sources/bibliography.md#src-asc-quality) · [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light)

**Related.** [LGT-001](05_lighting_and_color.md#lgt-001), [LGT-002](05_lighting_and_color.md#lgt-002), [LGT-003](05_lighting_and_color.md#lgt-003), [LGT-006](05_lighting_and_color.md#lgt-006), [LGT-011](05_lighting_and_color.md#lgt-011)

### LGT-006

**Use high-key and low-key as tonal designs** · established technique · priority 2 · high confidence

For a high-key treatment keep most important areas luminous and manage contrast. For low-key design reserve substantial darkness and selective areas of light.

**Why it works.** Tonal distribution steers attention and sets the scene's visual texture. Mood follows context.

**Apply.** Choosing a scene's tonal organization. **Exception.** A bright image can have strong contrast and a dark image can be flat. Describe the actual distribution when labels are ambiguous.

**Example.** A low-key hallway leaves walls dark while light makes the doorway and face readable. **Common mistake.** Writing low-key as an instruction to underexpose every surface.

**LLM action.** Name dominant value ranges, shadow regions and protected readable details. Reference a hero frame. **Check.** At delivery brightness the intended detail remains visible and the frame holds its intended tonal organization.

**Origin.** ARRI lighting functions and the Alton reading path. [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light) · [SRC-ALTON-LIGHT](../sources/bibliography.md#src-alton-light) · [SRC-BLOCK-VIS](../sources/bibliography.md#src-block-vis)

**Related.** [LGT-002](05_lighting_and_color.md#lgt-002), [LGT-003](05_lighting_and_color.md#lgt-003), [LGT-005](05_lighting_and_color.md#lgt-005), [LGT-008](05_lighting_and_color.md#lgt-008), [LGT-010](05_lighting_and_color.md#lgt-010)

### LGT-007

**Separate source color from white balance** · technical constraint · priority 1 · high confidence

Track the apparent colors of sources and the camera's neutral reference separately. Mixed sources may remain visibly different after one is neutralized.

**Why it works.** A stable reference keeps planned warm and cool relationships consistent across angles.

**Apply.** Mixing daylight, lamps, color effects or footage from different generations. **Exception.** A deliberate white-balance shift can mark time, point of view or disorientation. Declare the change and anchor it to the story.

**Example.** A room keeps a cool window and warmer fixture in the same relationship across coverage. **Common mistake.** Neutralizing every source or treating Kelvin alone as a complete description of an LED spectrum.

**LLM action.** Store named source colors, white reference or intent, exposure state and expected visible surfaces. Use Kelvin as a cue if useful. **Check.** Compare neutral reference objects and source relationships across adjacent shots.

**Origin.** ARRI notes on color, applied to shot continuity. [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light) · [SRC-BMD-MATCH](../sources/bibliography.md#src-bmd-match)

**Related.** [LGT-001](05_lighting_and_color.md#lgt-001), [LGT-004](05_lighting_and_color.md#lgt-004), [LGT-008](05_lighting_and_color.md#lgt-008), [LGT-010](05_lighting_and_color.md#lgt-010), [LGT-012](05_lighting_and_color.md#lgt-012)

### LGT-008

**Use palette contrast and affinity to organize attention** · established technique · priority 2 · high confidence

Define a palette for the environment and wardrobe, then reserve selected hue, value or saturation differences for the intended attention target.

**Why it works.** A consistent palette can bind space and character. A contrast can make a reveal or relation legible.

**Apply.** Design, boards and framing before generation. **Exception.** A crowded or discordant palette can express a world. Use position, focus or motion when necessary to preserve the important signal.

**Example.** A muted room leaves a single saturated object legible when it becomes relevant. **Common mistake.** Applying a generic cinematic color treatment that erases the character or prop's distinguishing cue.

**LLM action.** Record base palette, accent role, protected asset colors and what changes on specific beats. **Check.** Compare the frame in color and grayscale. Verify the intended cue is carried by the planned channel.

**Origin.** Block's visual structure and AFI design work. [SRC-BLOCK-VIS](../sources/bibliography.md#src-block-vis) · [SRC-AFI-DES](../sources/bibliography.md#src-afi-des)

**Related.** [LGT-006](05_lighting_and_color.md#lgt-006), [LGT-007](05_lighting_and_color.md#lgt-007), [LGT-009](05_lighting_and_color.md#lgt-009), [LGT-010](05_lighting_and_color.md#lgt-010), [CIN-CAM-008](03_cinematography.md#cin-cam-008)

### LGT-009

**Use a color motif as a contextual promise** · creative heuristic · priority 2 · medium confidence

Build color meaning through repetition, placement and change across the film. Give any shift a dramatic or perceptual job.

**Why it works.** Meaning accumulates from the film's own pattern. Viewers can connect colors to a character, condition or evolving relation.

**Apply.** Color arcs, motif returns and subjective transitions. **Exception.** A film can stay within one palette and change texture, light direction or sound. Avoid a hue shift that conflicts with continuity.

**Example.** A recurrent color moves from the environment to an object the character chooses to keep. **Common mistake.** Assuming a color has the same emotional meaning in every story or culture.

**LLM action.** Store the motif, appearances, baseline associations, planned changes and a reference frame per look state. **Check.** Review the arc in thumbnails and a rough cut. Identify what creates the intended reading beyond the hue label.

**Origin.** Block's contrast framework and a rulebook application of setup and payoff. [SRC-BLOCK-VIS](../sources/bibliography.md#src-block-vis) · [SRC-AFI-DES](../sources/bibliography.md#src-afi-des) · [SRC-CHEK-GUN](../sources/bibliography.md#src-chek-gun)

**Related.** [LGT-007](05_lighting_and_color.md#lgt-007), [LGT-008](05_lighting_and_color.md#lgt-008), [LGT-010](05_lighting_and_color.md#lgt-010), [LGT-012](05_lighting_and_color.md#lgt-012), [DRA-008](01_dramaturgy.md#dra-008)

### LGT-010

**Protect separation and exposure continuity** · continuity convention · priority 1 · high confidence

Keep important subject surfaces distinguishable from the background and preserve believable exposure relationships across views.

**Why it works.** The viewer retains a stable reading of the subject and location. Designed changes can register distinctly.

**Apply.** Reverse angles, repeated setups and mixed-source continuity. **Exception.** A subject can disappear into the background for concealment or abstraction. Preserve the information the scene needs.

**Example.** A rim or lighter wall separates a dark sleeve while the room's window direction stays consistent. **Common mistake.** Solving every shot independently so shadows, skin values and room contrast jump across a cut.

**LLM action.** Choose a hero reference, match shadow side, relative face and background values and critical color patches. Store changes by beat. **Check.** Compare adjacent frames with stills or appropriate scopes and play the cut at speed.

**Origin.** ARRI separation and background light plus shot-matching practice. [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light) · [SRC-BMD-MATCH](../sources/bibliography.md#src-bmd-match) · [SRC-ASC-BURUM](../sources/bibliography.md#src-asc-burum)

**Related.** [LGT-001](05_lighting_and_color.md#lgt-001), [LGT-002](05_lighting_and_color.md#lgt-002), [LGT-003](05_lighting_and_color.md#lgt-003), [LGT-006](05_lighting_and_color.md#lgt-006), [LGT-007](05_lighting_and_color.md#lgt-007), [LGT-012](05_lighting_and_color.md#lgt-012)

### LGT-011

**Give atmospheric light spatial logic** · established technique · priority 2 · medium confidence

Place haze, dust, smoke or rain in the mapped space. Describe how sources, occluders and movement make the effect visible.

**Why it works.** Atmosphere can reveal depth, alter visibility and give the scene a physical condition.

**Apply.** Backlit rain, shafts, silhouettes, and air between planes. **Exception.** Stylized light can act as a graphic form. State where it starts, stops and changes.

**Example.** A shaft from a window becomes visible in light haze, with a beam interrupted by the person crossing it. **Common mistake.** Adding bright beams in clean air with no plausible source or occlusion in a realistic shot.

**LLM action.** Specify density by layer, source path, beam visibility, airflow and the action it affects. **Check.** Inspect volume placement, occlusion, motion direction and consistency between coverage angles.

**Origin.** ASC lighting quality and BFI on expressive weather, adapted to generation. [SRC-ASC-QUALITY](../sources/bibliography.md#src-asc-quality) · [SRC-KURO-WEATH](../sources/bibliography.md#src-kuro-weath) · [SRC-ARRI-LIGHT](../sources/bibliography.md#src-arri-light)

**Related.** [LGT-001](05_lighting_and_color.md#lgt-001), [LGT-004](05_lighting_and_color.md#lgt-004), [LGT-005](05_lighting_and_color.md#lgt-005), [LGT-010](05_lighting_and_color.md#lgt-010), [MIS-009](04_mise_en_scene.md#mis-009)

### LGT-012

**Match shots before applying the creative grade** · established technique · priority 1 · high confidence

Identify the footage's color interpretation, correct accidental exposure and balance differences, and compare to a hero shot before building a shared creative look.

**Why it works.** Technical matching reduces cut-to-cut discrepancies. A look can then develop intent across scenes.

**Apply.** Editing generated footage from different modes, providers, or lighting states. **Exception.** Preserve deliberate differences tied to time, perspective or source changes. Document the discontinuity.

**Example.** Align a costume patch and background tone in two matching angles before applying the scene's low-saturation look. **Common mistake.** Applying an identical preset to mismatched clips and assuming they will match, or tagging an SDR clip as log.

**LLM action.** Log source space if known. Normalize only with verified transforms, match visible references, and then apply the look. Check export against timeline. **Check.** Use stills or scopes in a consistent viewing pipeline. Compare near the cut and replay the exported file.

**Origin.** Blackmagic shot-matching training and the ACES concept of a look. [SRC-BMD-MATCH](../sources/bibliography.md#src-bmd-match) · [SRC-ACES-LOOK](../sources/bibliography.md#src-aces-look) · [SRC-BLOCK-VIS](../sources/bibliography.md#src-block-vis)

**Related.** [LGT-003](05_lighting_and_color.md#lgt-003), [LGT-006](05_lighting_and_color.md#lgt-006), [LGT-007](05_lighting_and_color.md#lgt-007), [LGT-008](05_lighting_and_color.md#lgt-008), [LGT-009](05_lighting_and_color.md#lgt-009), [LGT-010](05_lighting_and_color.md#lgt-010)

## Frame and editorial continuity

| State | Record | Check in output |
| --- | --- | --- |
| World sources | Stable IDs, position, direction, size, color, visible practical state | Shadow and highlight direction; spill on nearby surfaces |
| Tone | Important midtones, protected highlights, intended shadows and separation | Readability at delivery brightness; clipping or crushed detail |
| Palette | Scene base, accent and protected object or wardrobe colors | Hue and contrast around the cut; continuity of neutral references |
| Atmosphere | Layer, source path, density, motion and reason | Consistent depth, occlusion and visible interaction |
| Change | Beat, trigger, target state, before and after frames | Only the planned source, exposure or look changes |

Use one hero still for each scene lighting state. In a reverse view the screen position of the source or its shadows can change while the physical source stays put. Check exposure and color relationships before using a creative preset. Review the cut and exported file, since display and encoding can affect the result. [SRC-ASC-BURUM](../sources/bibliography.md#src-asc-burum) · [SRC-BMD-MATCH](../sources/bibliography.md#src-bmd-match)
