# 06 · Visual bible and storyboard

## Inputs

Shot list, scene maps, any approved assets, director notes and delivery aspect ratio.

## Procedure

1. Create versioned character, costume, prop, location, lighting and palette references. Mark stable details and authorized state changes.
2. Board shots in order with frame IDs, directional cues and annotations. Use a floor plan to check framing, sightlines and occlusion.
3. Time a minimal animatic. Compare whether a hold, cut, or additional reaction changes comprehension or emotional rhythm.

## Applicable rules

[DIR-014](../rulebooks/02_directing.md#dir-014) · [CIN-CAM-003](../rulebooks/03_cinematography.md#cin-cam-003) · [CIN-CAM-008](../rulebooks/03_cinematography.md#cin-cam-008) · [MIS-008](../rulebooks/04_mise_en_scene.md#mis-008) · [MIS-012](../rulebooks/04_mise_en_scene.md#mis-012) · [LGT-010](../rulebooks/05_lighting_and_color.md#lgt-010)

## Output contract

visual_bible with version and entity references. storyboard_panels[] with frame_id, shot_id, beat_ids, time_or_phase, frame_purpose, reference_asset_ids, expected_state and notes. animatic_plan with trim estimates, cut cues, scene audio and validation results.

## Reusable prompt

> Create a visual-bible record and board the shot list in order. Keep identities, geography and light in a stable reference layer. Describe only intended state changes per panel. Diagnose the cut before asking for more coverage.

## Quality check

- The intended action reads in the selected crop and duration.
- Panels agree about identity, facing, props, geometry and light.
- The intended transition and reaction survive the rough assembly.

## Revision trigger

Revise if boards are individually attractive but cut together with confusing action, or if an important reference is unapproved.

## Handoff

Pass approved reference IDs, panel states, delivery aspect and cut points to frame generation.
