# Continuity management

The visual bible defines the stable world. The state ledger records how that world changes. The footage log records what the generated material actually does. Keep these three records linked by scene, beat, shot, clip, frame and asset IDs.

## State ledger

| Scope | Required state | Common authorized changes |
| --- | --- | --- |
| World | Location plan, orientation, fixed landmarks, entrances, occluders and source IDs | Door, weather, time or light state with a beat trigger |
| Character | Identity, outfit version, position, facing, gaze, hands and observable intention | Route, pose, costume condition, interaction and gaze |
| Prop | Shape, size, location, holder, hand and condition | Transfer, opening, breakage, disappearance or reveal with cause |
| Camera | Action axis, camera side, viewpoint, framing and focus | Motion path, orientation change and axis reset |
| Sound | Voice take, listener, room state, ambience and active cues | Line, barrier, room, off-screen cue or bridge |

Freeze a versioned set of stable references and document allowed deltas. A library can keep several useful angles for review. Send the few references the selected mode needs for a particular clip, with each role spelled out. A new version is a deliberate change with an explanation and a point where it begins. [Mise-en-scène](../rulebooks/04_mise_en_scene.md#mis-012) · [Provider reference guidance](../sources/bibliography.md#src-volc-p25)

## Inspect the shot and the join

1. Before submission, compare the planned first and last frames and trace the intended physical path. Verify identity, axis, props, visible sources and frame roles. Check the model profile and remove conflicting references.
2. After generation, inspect first usable frame, several intermediate states, key contact or expression, last usable frame and audio. Record observed trim points, deviations and timecodes. Keep the original.
3. Join candidate takes in an animatic or edit. Compare action phase, screen direction, silhouette, prop ownership, light, voice, room tone and the intended emotional handoff. Check in the delivery crop.
4. Classify each issue as story-critical, continuity-critical or cosmetic and choose accept, edit repair, alternate coverage or regeneration. Record the owner of the fix and re-review after any changed take or trim.
5. For an intentional discontinuity, record the violated expectation, artistic goal, planned viewer inference and supporting cue. Ensure the rough cut produces the intended effect.

Use the [failure guide](failure_modes.md) for diagnosis and the [Seedance manual](seedance_manual.md) for prompt and reference preparation. A take can satisfy its own brief and still fail at the cut, so keep both evaluations.
