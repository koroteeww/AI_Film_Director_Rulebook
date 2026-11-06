# 08 · Seedance motion generation

## Inputs

Approved shot and frame plan, asset IDs, verified provider mode, exact model and audio plan.

## Procedure

1. Check provider inputs and duration using the capability sources. Plan at 15 s or below by default. Record evidence and the creative reason for a longer supported request.
2. Bind each reference. Describe initial state, action order, camera and environment separately, final state and audio. Keep exact timecode decisions for the edit.
3. Inspect each take at key frames and across joins. Select trims, log failures and retry with one controlled change when practical.

## Applicable rules

[DIR-006](../rulebooks/02_directing.md#dir-006) · [CIN-CAM-007](../rulebooks/03_cinematography.md#cin-cam-007) · [CIN-CAM-017](../rulebooks/03_cinematography.md#cin-cam-017) · [MIS-012](../rulebooks/04_mise_en_scene.md#mis-012) · [SND-003](../rulebooks/06_sound_design.md#snd-003)

## Output contract

GenerationClip[] with clip_id, shot_ids, provider, model, profile_id, mode, planned_duration_s, duration_basis, aspect_ratio, resolution, reference_assets, prompt, initial_state, final_state and audio_plan. Record actual output and usable ranges after generation.

## Reusable prompt

> Create a provider-compatible motion brief for the approved shot. Use the selected reference roles and one coherent camera and action path. Confirm duration and endpoint compatibility. Return a generation record, repair option and review checks.

## Quality check

- Exact interface supports requested duration, mode and references.
- The prompt and reference roles agree, and the endpoint is reachable.
- The selected take preserves identity, action phase, screen direction and critical cues.

## Revision trigger

Revise for drift, contradictions, unsupported controls or story-critical defects. Use alternative coverage or a targeted edit where it can preserve the beat.

## Handoff

Pass chosen takes, usable intervals, frame anchors and audio status to sound and editing. See the [Seedance manual](../ai_production/seedance_manual.md).
