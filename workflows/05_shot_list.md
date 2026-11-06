# 05 · Shot list

## Inputs

Scene breakdown, screenplay, director intention, action axis and visual-bible information available so far.

## Procedure

1. Assign stable SH IDs and scene and beat links. Decide what each shot adds, in what order, and what audio belongs to it.
2. Specify size, angle, lens intent, focus, camera position and move, composition, blocking, subject and environmental motion, light and color.
3. Set estimated edit duration, entry and exit state, transition, audio and overlap or cutaway option. Check geometry before storyboarding.

## Applicable rules

[DIR-009](../rulebooks/02_directing.md#dir-009) · [DIR-010](../rulebooks/02_directing.md#dir-010) · [CIN-CAM-004](../rulebooks/03_cinematography.md#cin-cam-004) · [CIN-CAM-005](../rulebooks/03_cinematography.md#cin-cam-005) · [CIN-CAM-010](../rulebooks/03_cinematography.md#cin-cam-010) · [CIN-CAM-017](../rulebooks/03_cinematography.md#cin-cam-017) · [MIS-012](../rulebooks/04_mise_en_scene.md#mis-012)

## Output contract

Shot[] with shot_id, scene_id, beat_ids, purpose, estimated_duration_s, shot_size, camera, composition, blocking, subject_motion, environment_motion, lighting, color, sound, transition, continuity and rule_ids. Camera includes viewpoint, angle, lens intent, motion and focus.

## Reusable prompt

> Design the minimum useful coverage for each scene. Explain each shot's purpose in the cut. Specify spatial and camera choices independently, preserve actor and prop state, and include the planned sound and cut relationship.

## Quality check

- Each shot adds story, emotion, orientation, rhythm, or a planned editorial option.
- Screen direction, eyelines and contact phases fit adjacent views.
- Camera and subject movements can reach the planned endpoint.

## Revision trigger

Revise if the cut is unclear, the shot has no dramatic job, or movement and framing instructions conflict.

## Handoff

Pass the shot list, floor plan, continuity needs and frame candidates to storyboard.
