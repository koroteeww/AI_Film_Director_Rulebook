# 02 · Directing

Read the scene for what changes between people and what the viewer should experience. Plan the playable action, then decide how staging, viewpoint, sound and the edit will make that change legible. An AI motion instruction translates selected cues into observable behavior. The director's internal notes carry the fuller interpretation.

## Rules

### DIR-001

**Name the intended viewer experience** · creative heuristic · priority 1 · high confidence

For each scene, name what the viewer should notice, understand and feel by the exit. Separate this intention from the character's goal.

**Why it works.** One purpose can coordinate performance, staging, camera, sound and the cut.

**Apply.** Before boards and whenever a scene has conflicting notes. **Exception.** A scene may deliberately sustain ambiguity. State which facts stay legible and what interpretations remain open.

**Example.** A calm introduction should become uneasy when the guest recognizes a detail. **Common mistake.** Using a mood adjective as the whole directing brief.

**LLM action.** Record the intended viewer change, evidence beat, and craft choices serving it. **Check.** Each major shot or cue can name a contribution. Remove or revise choices with conflicting purposes.

**Origin.** AFI Director's Craft and NFTS script interpretation. [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir) · [SRC-NFTS-DIR](../sources/bibliography.md#src-nfts-dir)

**Related.** `DIR-002`, `DIR-005`, `DIR-010`, `DRA-005`

### DIR-002

**Choose narrative access and camera viewpoint** · established technique · priority 1 · high confidence

Choose whose experience anchors a beat, what the viewer knows, and when camera or sound aligns with that perspective.

**Why it works.** A controlled viewpoint guides knowledge and emotional alignment even without a literal eye view.

**Apply.** Reveals, contested information and changes of alignment. **Exception.** Switch viewpoints for irony, contrast or an intentional rupture. Give the viewer a cue at the switch.

**Example.** Stay with a speaker until a listener hears a significant off-screen sound, then shift auditory attention. **Common mistake.** Making a literal POV shot for every moment of subjective experience.

**LLM action.** For each beat store focal character, visible and audible access, optical viewpoint, and change cue. **Check.** Recount what the viewer and focal character know after the beat. Check for accidental spoilers.

**Origin.** Bordwell on access to story information and AFI on narrative point of view. [SRC-BORD-BOMB](../sources/bibliography.md#src-bord-bomb) · [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir)

**Related.** `DIR-001`, `DIR-007`, `DIR-009`, `DRA-010`

### DIR-003

**Direct with a playable action** · established technique · priority 1 · high confidence

Give the performer a verb aimed at a target and a reason to try it now.

**Why it works.** The actor or generation planner has a behavior to pursue and can react if it fails.

**Apply.** When the brief names a state such as sad, angry or mysterious. **Exception.** A stylized tableau can use poses as intentional graphic signs. Name the intended image and duration.

**Example.** Ask the performer to reassure a witness while avoiding the witness's question. **Common mistake.** Stacking adjectives without an objective or counterpart.

**LLM action.** Translate an intention into a target, visible tactic and response. Carry one action priority into the clip prompt. **Check.** A viewer can describe something the performer tries to do and where their attention is directed.

**Origin.** Stanislavski's action work and Weston's process-oriented tools. [SRC-STAN-ACT](../sources/bibliography.md#src-stan-act) · [SRC-WEST-TOOLS](../sources/bibliography.md#src-west-tools)

**Related.** `DIR-004`, `DIR-005`, `DIR-006`, `DRA-003`

### DIR-004

**Use given circumstances** · established technique · priority 2 · high confidence

Identify facts of place, relationship, preceding event and immediate constraints that affect this action.

**Why it works.** The same words and gesture play differently under different conditions.

**Apply.** Actor notes, scene interpretation and continuity across separately generated shots. **Exception.** An intentionally abstract performance may omit literal history. Preserve the conditions that actually shape it.

**Example.** A speaker keeps her voice low because the person she is discussing is behind a thin door. **Common mistake.** Writing a complete biography when one relevant fact would change the performance.

**LLM action.** Keep a short circumstances list and convert each relevant item into a visible or audible consequence. **Check.** Every circumstance carried into the prompt changes a choice, motion, position or sound.

**Origin.** Stanislavski's предлагаемые обстоятельства, adapted to a performance brief. [SRC-STAN-ACT](../sources/bibliography.md#src-stan-act) · [SRC-WEST-TOOLS](../sources/bibliography.md#src-west-tools)

**Related.** `DIR-003`, `DIR-006`, `DIR-008`

### DIR-005

**Find beats through changed tactics** · established technique · priority 1 · high confidence

Mark a new beat when the character changes tactic, registers information or shifts the relationship.

**Why it works.** Performance has legible turning points the camera and edit can support.

**Apply.** Dialogue, physical tasks and rehearsals with several intentions. **Exception.** Hold across a subtle turn when the audience benefits from discovering it within a sustained take.

**Example.** A joke becomes a request after it draws no response. **Common mistake.** Marking a cut at every line regardless of what the relationship does.

**LLM action.** Write action, trigger, reaction and exit state. Group consecutive beats into one generation only if the planned action stays feasible. **Check.** Identify the first observable sign of each turn in the board or animatic.

**Origin.** Weston on emotional events and McKee on scene changes. [SRC-WEST-TOOLS](../sources/bibliography.md#src-west-tools) · [SRC-MCK-TURN](../sources/bibliography.md#src-mck-turn) · [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir)

**Related.** `DIR-001`, `DIR-003`, `DIR-007`, `DIR-012`, `DRA-005`

### DIR-006

**Convert performance notes into observable behavior** · creative heuristic · priority 1 · medium confidence

Keep the inner intention in direction notes and choose a few visible or audible cues for the shot.

**Why it works.** Concrete movement, gaze, breath or stillness can be reviewed across takes.

**Apply.** Image and motion prompts and independent generation of adjacent shots. **Exception.** A mask or long shot may require a larger body action. Use the minimum amplitude the framing can convey.

**Example.** A hand begins reaching, stops short, and stays still while attention shifts to the listener. **Common mistake.** Requesting several facial, hand and camera events in the same instant.

**LLM action.** Separate actor intent, observable cue, timing order and end state. Pick the strongest cue when the shot is crowded. **Check.** Check in context at intended size and speed. The cue should be legible and leave the next shot in a compatible state.

**Origin.** Rulebook translation of Weston's physical-life and action tools. [SRC-WEST-TOOLS](../sources/bibliography.md#src-west-tools) · [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir)

**Related.** `DIR-003`, `DIR-004`, `DIR-008`, `DIR-010`

### DIR-007

**Direct the listening and reaction** · established technique · priority 2 · high confidence

Plan when a listener receives a cue, how they register it and whether the viewer sees that response.

**Why it works.** A scene's meaning can change in the recipient while the speaker continues.

**Apply.** Negotiations, withholding, persuasion and off-screen speech. **Exception.** Hold on the speaker if their risk or loss of certainty is the key experience. Use sound or a later reaction to clarify.

**Example.** Let an answer continue off-screen as the listener lowers an object they were about to hand over. **Common mistake.** Cutting mechanically to the person who speaks each line.

**LLM action.** Add a reaction owner, trigger, delay, action, and optional cut candidate. Preserve listening state across shots. **Check.** Watch without dialogue or listen without picture, then check whether the intended relationship turn survives the full cut.

**Origin.** Weston's relationship-based approach and Chekhov's use of pauses. [SRC-WEST-TOOLS](../sources/bibliography.md#src-west-tools) · [SRC-CHEK-PLAY](../sources/bibliography.md#src-chek-play)

**Related.** `DIR-002`, `DIR-005`, `DIR-012`, `DRA-012`, `DRA-014`

### DIR-008

**Rehearse the physical impulse** · established technique · priority 3 · medium confidence

Explore a larger physical gesture that expresses the character's drive, then decide what trace belongs in the performance.

**Why it works.** A whole-body impulse can give a subtle gesture coherent direction.

**Apply.** Stylized performances and scenes where internal conflict needs a physical expression. **Exception.** Use straightforward task action when a formal exercise would distract or when the gesture is meant to stay overt.

**Example.** Explore gathering something toward the chest, then express that impulse through a small change in the grip. **Common mistake.** Putting a large rehearsal exercise on screen when the close framing calls for restraint.

**LLM action.** Keep the exercise in prep and specify the visible trace, its timing, and intensity in the shot. **Check.** The result reads as motivated physical behavior and fits the framing and the scene's tone.

**Origin.** Michael Chekhov's psychological gesture, with a film planning adaptation. [SRC-MCHEK-TECH](../sources/bibliography.md#src-mchek-tech) · [SRC-WEST-TOOLS](../sources/bibliography.md#src-west-tools)

**Related.** `DIR-003`, `DIR-004`, `DIR-006`

### DIR-009

**Block action to guide attention** · established technique · priority 1 · high confidence

Use position, orientation, depth, contrast and timed movement to control when a viewer notices each important action.

**Why it works.** The audience can find the action within a frame and understand who can see what.

**Apply.** Group scenes, entrances and reveals in a single shot. **Exception.** Give the viewer several simultaneous choices when wandering attention is part of the effect. Keep necessary facts recoverable.

**Example.** A quiet background figure steps into an unobstructed pool of light only after the foreground action stops. **Common mistake.** Animating every person and every prop through the decisive gesture.

**LLM action.** Mark the attention target at each beat, movement cue, relative depth and planned occlusion. **Check.** A viewer can point to the intended subject at the key moment without needing a verbal explanation.

**Origin.** AFI cinematic storytelling and NYU staging practice. [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir) · [SRC-NYU-GRAD](../sources/bibliography.md#src-nyu-grad) · [SRC-BLOCK-VIS](../sources/bibliography.md#src-block-vis)

**Related.** `DIR-001`, `DIR-002`, `DIR-010`, `DIR-011`

### DIR-010

**Give the camera and cut a reason** · established technique · priority 1 · high confidence

Tie shot size, movement, camera placement and the cut to a dramatic purpose such as reveal, reaction, clarity or duration.

**Why it works.** Camera emphasis can strengthen a beat or draw attention away from it.

**Apply.** Shot-list review and motion prompt design. **Exception.** A formal move may set rhythm, establish a pattern or make the camera felt. State the planned effect.

**Example.** A camera shift reveals who heard the exchange once that knowledge matters. **Common mistake.** Adding a smooth orbit merely because the tool supports movement.

**LLM action.** Record the purpose, start target, movement trigger, final target and the option of holding the frame. **Check.** Compare the shot to a locked version. Keep the move when it adds the intended information, relation or experience.

**Origin.** AFI Director's Craft and Bordwell's account of narrative access. [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir) · [SRC-BORD-BOMB](../sources/bibliography.md#src-bord-bomb)

**Related.** `DIR-001`, `DIR-002`, `DIR-006`, `DIR-009`, `DIR-014`

### DIR-011

**Make the setting act on the scene** · established technique · priority 2 · high confidence

Choose a feature of the location, prop or environment that alters an action or the viewer's reading of it.

**Why it works.** The scene becomes specific to its world and can reveal information through cause and effect.

**Apply.** Location-led scenes, obstacles, reveals and action design. **Exception.** A stripped set can express abstraction. Treat absence of detail as part of the design.

**Example.** A gust interrupts a handoff and forces a character to reveal which paper matters. **Common mistake.** Adding atmospheric weather that changes between shots without a dramatic or physical reason.

**LLM action.** Link the environmental cue to an action and store its direction, state and continuity requirement. **Check.** Explain what would change if the setting feature disappeared. Check that it persists across relevant shots.

**Origin.** Hitchcock's AFI setting example and BFI analysis of Kurosawa's weather. [SRC-HITCH-AFI](../sources/bibliography.md#src-hitch-afi) · [SRC-KURO-WEATH](../sources/bibliography.md#src-kuro-weath)

**Related.** `DIR-004`, `DIR-009`, `DIR-013`, `DRA-011`

### DIR-012

**Shape tension and release through duration** · creative heuristic · priority 2 · medium confidence

Choose where the scene should tighten, hold or release. Let action, listening, silence or sustained observation create the duration.

**Why it works.** Duration changes how much anticipation and reflection a viewer can experience.

**Apply.** Tense exchanges, waiting, reactions and edits that feel hurried. **Exception.** A hard cut can deny release or create shock when that is the stated intention.

**Example.** Hold a listener long enough to see a decision form, then cut after their response begins. **Common mistake.** Assigning a fast or slow tempo to every shot from a genre label.

**LLM action.** Write pressure change and the cue that justifies each hold or cut. Test alternatives in the animatic. **Check.** Time the beat in context and compare an earlier and later cut. Choose by the intended experience.

**Origin.** Tarkovsky on filmed time and Weston's moment-by-moment process. [SRC-TARK-ESSAY](../sources/bibliography.md#src-tark-essay) · [SRC-WEST-TOOLS](../sources/bibliography.md#src-west-tools) · [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir)

**Related.** `DIR-005`, `DIR-007`, `DIR-014`, `DRA-014`, `DRA-017`

### DIR-013

**Use contrast to express a turn** · established technique · priority 2 · high confidence

Change one or more perceptible relations across a beat, such as distance, movement, tonal value or density, when it serves the intention.

**Why it works.** A perceptible contrast makes a change in the situation easier to feel or recognize.

**Apply.** Turns, shifts of power and transitions between emotional states. **Exception.** Continuity or stillness can make a hidden change more troubling. Find evidence in behavior or sound.

**Example.** Two figures share an even two-shot until one withdraws and the empty space becomes conspicuous. **Common mistake.** Changing camera, lighting and movement together without knowing which one expresses the shift.

**LLM action.** Specify the before/after contrast and which element carries it. Preserve unrelated scene anchors. **Check.** A side-by-side comparison shows the intended change and preserves the necessary identity and geography.

**Origin.** Block's visual contrast and AFI's integration of image with story. [SRC-BLOCK-VIS](../sources/bibliography.md#src-block-vis) · [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir)

**Related.** `DIR-001`, `DIR-009`, `DIR-010`, `DIR-012`

### DIR-014

**Rehearse transitions and minimum coverage** · creative heuristic · priority 1 · high confidence

Walk through the scene from entry state to exit, then plan the shots and transitions needed for the intended cut.

**Why it works.** A rehearsal can find missing geography, reaction, action overlap or a sound bridge before expensive generation.

**Apply.** Before motion production and when a one-take plan is brittle. **Exception.** A long take can carry the full beat if performance and spatial action remain legible. Identify an edit recovery point if feasible.

**Example.** Board the handoff, the receiver's reaction and an exit cue. Test a sound overlap into the next scene. **Common mistake.** Generating every angle without a plan for where they would cut together.

**LLM action.** Mark exit-to-entry link, coverage purpose, overlaps, room tone and fallback. Favor a small reference test before full generation. **Check.** Assemble the boards in order. Check the turn, axis, action match and audio bridge without relying on missing footage.

**Origin.** Lumet's rehearsal account, AFI exercises and NFTS expressive editing. [SRC-LUM-TALK](../sources/bibliography.md#src-lum-talk) · [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir) · [SRC-NFTS-DIR](../sources/bibliography.md#src-nfts-dir)

**Related.** `DIR-005`, `DIR-009`, `DIR-010`, `DIR-012`, `DRA-015`

## Directing pass

1. **Read.** Mark the given circumstances, immediate objective, obstacle, changes in tactic, hidden intention and scene turn. Decide whose experience anchors the audience and which story facts they can access.
2. **Stage.** Choose actor positions and targets for each turn. Walk the interaction without dialogue, then restore the lines that pursue a tactic or carry necessary information.
3. **Frame.** Choose between staying with the actor, cutting to a recipient, widening for space, and moving to reveal. Treat each as a way to change information or attention.
4. **Time.** Build a rough board with the key reaction and the sound cue at its real position. Compare a hold and a cut. Plan where action overlap or a bridge protects the intended rhythm.
5. **Handoff.** Pass the directorial intention, beat map, camera purpose, staging map, visual anchors, audio cue and coverage recovery point to shot planning.

Weston's process tools help specify what performers do moment by moment. Lumet describes rehearsing and staging to give actors confidence in a demanding scene. Michael Chekhov's imagined embodiment gives a different path into the physical impulse. Select the method that yields a legible performance in the planned frame. [SRC-WEST-TOOLS](../sources/bibliography.md#src-west-tools) · [SRC-LUM-TALK](../sources/bibliography.md#src-lum-talk) · [SRC-MCHEK-TECH](../sources/bibliography.md#src-mchek-tech)

AFI's exercises ask directors to account for camera and edit decisions. Tarkovsky's essay gives a reason to study what unfolds within a held frame. Rehearse both decisions when the right cut is uncertain. In generation, verify the intended duration and the endpoint in the assembled edit. [SRC-AFI-DIR](../sources/bibliography.md#src-afi-dir) · [SRC-TARK-ESSAY](../sources/bibliography.md#src-tark-essay)
