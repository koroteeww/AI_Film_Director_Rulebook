# 07 · Start and end frame generation

## Inputs

Storyboard, visual bible, shot states and known reference and model capabilities.

## Procedure

1. Choose first frame, dedicated pair, intermediate panel or loose reference based on the motion and required endpoints.
2. Prepare the composition and initial pose, including room for action. Use the same geometry, identity, palette and shot framing when creating compatible variants.
3. Review paths between frames. If any pair implies a morph or unsupported move, revise the end or plan multiple shots. Approve a clean version before motion.

## Applicable rules

[CIN-CAM-008](../rulebooks/03_cinematography.md#cin-cam-008) · [CIN-CAM-010](../rulebooks/03_cinematography.md#cin-cam-010) · [MIS-012](../rulebooks/04_mise_en_scene.md#mis-012) · [LGT-001](../rulebooks/05_lighting_and_color.md#lgt-001) · [LGT-010](../rulebooks/05_lighting_and_color.md#lgt-010)

## Output contract

frame_specs[] with frame_id, shot_id, role, aspect_ratio, state, subject, environment, camera, lighting, composition, reference_asset_ids, invariants, permitted_changes, prompt and approval_status.

## Reusable prompt

> Write a still-frame specification and prompt for each needed role. Name the current state and visible action, identify approved references and protect fixed attributes. Check that any end frame can be reached physically from the start.

## Quality check

- Identity, costume, props, axis, geometry and light match the intended state.
- Start and end are compatible with the camera and action path.
- Aspect, composition and crop leave the required elements readable.

## Revision trigger

Revise when paired frames disagree about space or identity, movement lacks room, or the provider has no suitable mode.

## Handoff

Pass approved frames, intended action path and reference binding plan to motion. See the [image generation guide](../ai_production/image_generation.md).
