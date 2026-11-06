# 10 · CapCut assembly and export

## Inputs

Approved shot order, selected clips, source intervals, sound layers, continuity notes, delivery requirements and verified asset permissions.

## Procedure

1. Assemble a rough cut for story, feeling, orientation and pacing. Match action and set the sound overlaps. Compare a different cut point when a join is doubtful.
2. Fine-cut chosen takes, balance sound, match shots, then apply the creative look. Add titles and verified captions and check safe placement.
3. Export to the required dimensions, rate and format the current platform supports. Review the actual output and log the versions and issues.

## Applicable rules

[EDT-001](../rulebooks/07_montage_and_editing.md#edt-001) · [EDT-003](../rulebooks/07_montage_and_editing.md#edt-003) · [EDT-009](../rulebooks/07_montage_and_editing.md#edt-009) · [EDT-014](../rulebooks/07_montage_and_editing.md#edt-014) · [SND-009](../rulebooks/06_sound_design.md#snd-009) · [LGT-012](../rulebooks/05_lighting_and_color.md#lgt-012)

## Output contract

edit_plan with timeline_settings, shot_uses[] with shot_id, clip_id, source_in_s, source_out_s, timeline_in_s, timeline_out_s, transition and continuity_notes. Include audio_cues, titles, export_target, review_issues and approval status.

## Reusable prompt

> Assemble an editing plan from the chosen takes and sounds. Prioritize emotional intent and audience comprehension, then continuity, pace and polish. Specify source and timeline trims, overlaps, matching references, titles and export checks.

## Quality check

- Cuts preserve or deliberately change emotion, action, axis and sound.
- Color and levels match across intended continuity.
- The export is reviewed at delivery scale with the correct duration, picture, sound and titles.

## Revision trigger

Revise for an unclear turn, accidental gaps, sync, identity, grade or export issues. Reopen the earlier stage that owns the fix.

## Handoff

Pass the export, cut log and remaining risks to the finished-film review. See the [CapCut guide](../ai_production/capcut_workflow.md).
