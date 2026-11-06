# 09 · Scene sound and mix plan

## Inputs

Chosen takes, screenplay and beat list, location and listener notes, dialogue and asset provenance.

## Procedure

1. Spot dialogue, ambience, Foley/effects, music and planned silence for each scene. Define source and auditory point of view.
2. Select a dialogue take and align visible performance. Build a continuous ambience bed and spot contacts, off-screen sounds and transitions.
3. Plan editable layers, sync points, overlaps and tails. Review intelligibility and dynamic range on an assembled scene.

## Applicable rules

[SND-002](../rulebooks/06_sound_design.md#snd-002) · [SND-003](../rulebooks/06_sound_design.md#snd-003) · [SND-004](../rulebooks/06_sound_design.md#snd-004) · [SND-007](../rulebooks/06_sound_design.md#snd-007) · [SND-009](../rulebooks/06_sound_design.md#snd-009) · [SND-013](../rulebooks/06_sound_design.md#snd-013)

## Output contract

sound_cues[] with cue_id, scene_id, shot_ids, type, source_asset_id, world_relation, listener, timeline_in_s, timeline_out_s, sync_event, perspective and transition. scene_mix includes dialogue, ambience, Foley/SFX and music track intent, silence, levels and delivery checks.

## Reusable prompt

> Make a scene sound plan with editable layers, clear speaker timing, continuous environment, necessary action cues and meaningful silence. Mark each overlap and distinguish generated native audio from selected and replacement tracks.

## Quality check

- Essential dialogue remains intelligible and synchronized.
- The room and voice do not reset unintentionally at a cut.
- Music, effects and silence do their stated dramatic job.

## Revision trigger

Revise when speech cannot be understood, lip sync is poor, a cue implies the wrong space, or the mix hides the intended beat.

## Handoff

Pass synced cues, layers, audio handles, provenance and quality checks to the editor.
