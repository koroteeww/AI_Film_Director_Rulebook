# 04 · Scene breakdown

## Inputs

Screenplay, brief, beat outline and known production constraints.

## Procedure

1. Assign stable SC IDs. Map beats into dramatic scenes and mark the viewer-facing purpose and emotional entry and exit.
2. List location, people, props, action, time, audio, visual-bible references and dependencies. Record required continuity states and allowable changes.
3. Flag transitions, risks and alternate coverage opportunities. A dramatic scene can span several shots and multiple generations.

## Applicable rules

[DRA-005](../rulebooks/01_dramaturgy.md#dra-005) · [DIR-001](../rulebooks/02_directing.md#dir-001) · [DIR-005](../rulebooks/02_directing.md#dir-005) · [MIS-001](../rulebooks/04_mise_en_scene.md#mis-001) · [MIS-007](../rulebooks/04_mise_en_scene.md#mis-007) · [SND-008](../rulebooks/06_sound_design.md#snd-008)

## Output contract

Scene[] with scene_id, heading, purpose, location, time, character_ids, prop_ids, beat_ids, action_summary, emotion_in, emotion_out, estimated_duration_s, continuity and sound_requirements. See the core scene schema in the schemas directory.

## Reusable prompt

> Break the screenplay into scenes and link each to its dramatic beats. For each scene describe the change, state before and after, continuity requirements and essential sound. Flag a smaller coverage plan if the scene is technically ambitious.

## Quality check

- Each screenplay scene and beat has an owner.
- Necessary state changes have causes and time or beat anchors.
- The intended shot count and generation durations are still open editorial decisions.

## Revision trigger

Revise when an action requires an unmapped location, a prop changes without cause, or sound, viewpoint or continuity would be ambiguous.

## Handoff

Pass scenes, beat links, continuity states, audio needs and the location plan to the shot list.
