# 06 · Sound design

Design the scene's sound when choosing the space, blocking and viewpoint. Specify what the audience hears, what characters hear, and which cues change the scene. For AI footage, place the final scene mix on an editable timeline with persistent cue IDs.

Useful Russian terms include звуковое решение фильма (film sound concept), атмосфера (ambience), фон помещения (room tone), синхронные шумы (synchronized action sounds, including performed Foley where applicable), and закадровый звук (off-screen or out-of-frame sound, depending on context). The СПбГИКиТ study plan identifies film sound concept as a distinct craft topic. [SRC-GIKIT-PLAN](../sources/bibliography.md#src-gikit-plan)

## Rules

### SND-001

**Classify a sound by its relation to the story world** · established technique · priority 2 · high confidence

Mark whether a cue belongs to the story world, comes from outside it, or intentionally changes status. Record on-screen, off-screen and subjective access separately.

**Why it works.** The classification helps a viewer infer who could hear the cue and how it should behave in the edit.

**Apply.** Music, voice-over, environment and ambiguous cues. **Exception.** A reveal can reclassify a cue, such as score that becomes a visible radio. Plan the point at which the distinction changes.

**Example.** A melody begins as an apparent score and becomes spatially anchored when the radio is shown. **Common mistake.** Classifying all sounds added in post as non-diegetic, including footsteps.

**LLM action.** Store world relation, source ID, listener, perspective and reveal or transition. **Check.** Trace whether a character's reaction, location and sound perspective agree with the intended status.

**Origin.** Film sound analysis and Chion's audiovisual framework. [SRC-OSU-SOUND](../sources/bibliography.md#src-osu-sound) · [SRC-CHION-AV](../sources/bibliography.md#src-chion-av) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd)

**Related.** `SND-007`, `SND-008`, `SND-010`

### SND-002

**Protect intelligibility where speech carries meaning** · established technique · priority 1 · high confidence

Keep story-critical words and the intended performance readable. Make room through level, timing and masking control.

**Why it works.** Audiences can follow the consequence of a line without losing the environment or the speaker's delivery.

**Apply.** Dialogue, narration and audible plot information. **Exception.** A line may be obscured to express distance, subjectivity or concealment. Preserve another route to essential information.

**Example.** Reduce a competing cue during a decisive line and restore it during the pause. **Common mistake.** Raising speech until it distorts while keeping competing sound at the same level.

**LLM action.** Mark essential words and intended perspective. Adjust or remove competing cues. Check several playback conditions. **Check.** Listen at a modest level with eyes closed and confirm the needed words and intent can be understood.

**Origin.** Chion's discussion of voice and practical dialogue mixing guidance. [SRC-CHION-NOTE](../sources/bibliography.md#src-chion-note) · [SRC-ADOBE-ROOM](../sources/bibliography.md#src-adobe-room) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd)

**Related.** `SND-001`, `SND-003`, `SND-007`, `SND-012`, `SND-013`

### SND-003

**Maintain performance and synchronization across dialogue** · continuity convention · priority 1 · medium confidence

Select a coherent voice performance and align visible speech, breaths, gaps and reactions to it.

**Why it works.** Continuity of timing and timbre makes multiple angles feel like one exchange.

**Apply.** Dialogue assembled from generated takes, off-screen lines and replacement recordings. **Exception.** Use voice-over, a listener shot, a cutaway or an intentionally unsynchronized style when it serves the scene.

**Example.** Keep the chosen voice track across the reverse and cut to a listener through a difficult syllable. **Common mistake.** Concatenating incompatible voices and trusting each clip's native audio.

**LLM action.** Keep a dialogue cue ID, speaker, line, take, onset, sync targets and source provenance. Use one track as the timing reference. **Check.** Scrub visible consonant closures and line starts, then listen through the cut for voice and room jumps.

**Origin.** Film sound practice adapted to separate generations. [SRC-ADOBE-ROOM](../sources/bibliography.md#src-adobe-room) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd) · [SRC-ADOBE-JL](../sources/bibliography.md#src-adobe-jl)

**Related.** `SND-002`, `SND-004`, `SND-007`, `SND-009`, `SND-013`, `DIR-007`

### SND-004

**Lay a continuous scene ambience** · continuity convention · priority 1 · high confidence

Build a scene bed with consistent ambience or room tone. Make shifts deliberate and connect them to changes in place, time or listening perspective.

**Why it works.** A continuous bed masks accidental holes and gives adjacent images a shared acoustic space.

**Apply.** Interior coverage, repeated locations and clips with noisy native audio. **Exception.** A hard acoustic break can signal a new scene or subjective shift. Choose and test it deliberately.

**Example.** Carry a low ventilation bed through a dialogue cut and change it once the door closes. **Common mistake.** Letting native ambience restart with every clip or looping a distinctive noise at audible intervals.

**LLM action.** Assign one bed per space and listening state. Use loops or crossfades with variation, and mute incompatible clip ambience. **Check.** Listen over joins without picture and check for gaps, repeated ticks, sudden changes and level pumping.

**Origin.** Adobe's room-tone guidance and sound-design practice. [SRC-ADOBE-ROOM](../sources/bibliography.md#src-adobe-room) · [SRC-ADOBE-SFX](../sources/bibliography.md#src-adobe-sfx) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd)

**Related.** `SND-003`, `SND-007`, `SND-009`, `SND-011`, `SND-013`

### SND-005

**Use Foley for timed physical detail** · established technique · priority 2 · high confidence

Perform, select or synthesize action sounds that match timing, weight, material and perspective. Prioritize contact cues that affect the story.

**Why it works.** A synchronized contact can establish texture, force and a sense of physical connection.

**Apply.** Footsteps, fabric, handoffs and handled props. **Exception.** Omit or heighten a contact for attention, humor or subjectivity. Keep the intended rhythm.

**Example.** Give a loaded bag a heavier landing than an empty bag on the same table. **Common mistake.** Applying the same stock footstep to different surfaces, pace and distance.

**LLM action.** Create a cue list with contact time, source, material, intensity and perspective. Keep clean tails for edits. **Check.** Compare each cue with the visible contact and play the sequence without Foley to judge its contribution.

**Origin.** Adobe's practitioner explanation of Foley. [SRC-ADOBE-SFX](../sources/bibliography.md#src-adobe-sfx) · [SRC-CHION-AV](../sources/bibliography.md#src-chion-av)

**Related.** `SND-004`, `SND-006`, `SND-007`, `SND-013`, `MIS-007`

### SND-006

**Design effects around an event and its cause** · established technique · priority 2 · high confidence

Choose or design effects by the event they identify, imply or stylize. Distinguish a recurring environment from a discrete event cue.

**Why it works.** An effect can communicate scale, danger or function even when the source is partly or wholly unseen.

**Apply.** Machines, impacts, transitions and expressive events. **Exception.** Use abstract sound when literal identification would spoil a reveal or when the world has stylized rules.

**Example.** A mechanical whine changes before a device stops, allowing the listener to anticipate failure. **Common mistake.** Adding dense effects to every movement, burying the cue that matters.

**LLM action.** Record cause, onset, development, tail and who hears it. Design the cue in a separate editable track when possible. **Check.** A listener can identify or infer the intended event and distinguish it from the background.

**Origin.** Sound-effects practice and Chion's audiovisual relationship. [SRC-ADOBE-SFX](../sources/bibliography.md#src-adobe-sfx) · [SRC-CHION-AV](../sources/bibliography.md#src-chion-av) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd)

**Related.** `SND-005`, `SND-007`, `SND-008`, `SND-010`, `SND-012`

### SND-007

**Set an auditory point of view** · established technique · priority 1 · high confidence

Choose what the audience hears from a listener's position or from a deliberately freer perspective. Use level, spectrum, occlusion, reverb and localization as needed.

**Why it works.** Changes in listening position can reveal distance, a barrier or a character's selective attention.

**Apply.** Moves between spaces, perspectives and near and far coverage. **Exception.** A production can keep dialogue close through many angles to protect emotional access. Make spatial cues elsewhere coherent.

**Example.** A sound behind a shut door loses presence and regains detail when the door opens. **Common mistake.** Reversing spatial placement or changing reverberation with each image angle without a reason.

**LLM action.** Store listener ID or mix perspective, source relation, room state and planned perspective shifts. **Check.** Listen to the scene without picture and identify whether the intended barrier or access shift is audible.

**Origin.** Thom's sound-centered point of view, with practical spatial cues. [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd) · [SRC-CHION-AV](../sources/bibliography.md#src-chion-av) · [SRC-ADOBE-ROOM](../sources/bibliography.md#src-adobe-room)

**Related.** `SND-001`, `SND-002`, `SND-004`, `SND-008`, `SND-009`, `DIR-002`

### SND-008

**Use off-screen sound to extend or withhold space** · established technique · priority 2 · high confidence

Give an unseen sound a plausible source or deliberate ambiguity. Decide who notices it, what it implies and whether it will be revealed.

**Why it works.** A cue can imply activity beyond the image, redirect attention, or create anticipation without another generated shot.

**Apply.** Entrances, reveals, environment and scenes of constrained viewpoint. **Exception.** An unexplained sound can remain thematic or unsettling. Establish the intended uncertainty.

**Example.** A tool drops in the next room and one character stops speaking before anyone appears. **Common mistake.** Giving a plot-critical off-screen cue the wrong direction or leaving all listeners indifferent unintentionally.

**LLM action.** Record source status, cue time, spatial relation, reaction, reveal condition and any intended ambiguity. **Check.** Check whether viewers infer the intended event or uncertainty and whether the characters react in the planned order.

**Origin.** Thom and a close reading of Chekhov's off-stage cues. [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd) · [SRC-CHEK-PLAY](../sources/bibliography.md#src-chek-play) · [SRC-CHION-AV](../sources/bibliography.md#src-chion-av)

**Related.** `SND-001`, `SND-006`, `SND-007`, `SND-009`, `SND-011`, `DIR-007`

### SND-009

**Bridge picture cuts with independently timed sound** · established technique · priority 1 · high confidence

Use a J-cut to introduce the incoming cue ahead of its picture. Use an L-cut to let outgoing audio continue. A shared bed can also bridge either join.

**Why it works.** The viewer can anticipate the next space or stay with a performance while the picture changes.

**Apply.** Dialogue, scene transitions and rough-cut repair. **Exception.** Cut picture and sound together for punctuation, rupture or a clean shift in place.

**Example.** Let a line continue over the listener's reaction. Start the next room's ambience just before a planned reveal. **Common mistake.** Making a J- or L-cut that changes the apparent cause of a sound or obscures important dialogue.

**LLM action.** Store cue in/out, picture cut point, carry direction and audio handles. Detach or replace native audio when necessary. **Check.** Watch and listen through the transition. Identify which scene each audible cue belongs to and whether the overlap lands cleanly.

**Origin.** Adobe's split-edit definitions and the rulebook's scene assembly method. [SRC-ADOBE-JL](../sources/bibliography.md#src-adobe-jl) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd)

**Related.** `SND-003`, `SND-004`, `SND-007`, `SND-008`, `SND-013`, `DIR-014`

### SND-010

**Give music a relationship to the drama** · established technique · priority 2 · high confidence

Decide whether music supports, counters, paces or reinterprets a beat. Choose when it enters and leaves and which voice or effect takes priority.

**Why it works.** Music changes how the same image is understood and how duration feels.

**Apply.** Score, source music, motifs and transitions. **Exception.** A continuous cue can establish the form of a sequence. Check that it permits necessary variation and silence.

**Example.** Let an established melody thin out after a refusal, leaving one audible instrument and the room. **Common mistake.** Using a constant emotional track that states the same information as dialogue and leaves no dynamics.

**LLM action.** Spot entry, exit, foreground priority, relation to picture and beat references. Compare music and no-music passes. **Check.** The cue supports the intended reading and preserves essential speech, rhythm and contrast.

**Origin.** Chion on audiovisual perception and Thom on writing for sound. [SRC-CHION-AV](../sources/bibliography.md#src-chion-av) · [SRC-CHION-NOTE](../sources/bibliography.md#src-chion-note) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd)

**Related.** `SND-001`, `SND-002`, `SND-007`, `SND-009`, `SND-011`, `SND-012`

### SND-011

**Distinguish dramatic silence from a missing track** · creative heuristic · priority 2 · medium confidence

Decide what remains audible, what falls away, and why the space or inner perspective changes.

**Why it works.** Reducing sound can focus attention, make a cue salient or create a break in the audience's access.

**Apply.** After a turn, before an off-screen cue, or when withholding music. **Exception.** Absolute digital silence can be an intentional break. Confirm it survives playback and belongs at the chosen moment.

**Example.** Remove the score and keep a breath and low room presence until a distant cue interrupts. **Common mistake.** Muting one generated clip and leaving an accidental dead patch in otherwise continuous space.

**LLM action.** Mark the silence type, retained bed or deliberate zero, duration and exit cue. **Check.** Compare playback with and without the silence. Confirm the intended cue or performance remains readable.

**Origin.** Chekhov's staged silence and Thom's sound-design approach. [SRC-CHEK-PLAY](../sources/bibliography.md#src-chek-play) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd) · [SRC-CHION-AV](../sources/bibliography.md#src-chion-av)

**Related.** `SND-004`, `SND-007`, `SND-008`, `SND-010`, `SND-012`, `DRA-014`

### SND-012

**Manage dynamic range against the delivery target** · technical constraint · priority 1 · high confidence

Treat integrated loudness, loudness range and true peak as different measurements. Use the destination's specified values and preserve purposeful dynamics within them.

**Why it works.** Mix quality depends on intelligibility, contrast and adequate headroom as well as compliance with any delivery requirements.

**Apply.** Final mixes, multiple platforms and loud scenes. **Exception.** In the absence of a specified target, log your working target and test playback. Avoid importing an unrelated standard as a requirement.

**Example.** Check the finished export's loudness and true peak, then listen to the quietest dialogue and loudest effects. **Common mistake.** Checking peak alone and assuming that dialogue loudness or range is correct.

**LLM action.** Record destination spec or working target, meter, measured result and audibility checks. Re-measure after export. **Check.** The export meets the relevant spec and carries intelligible speech and intended dynamics at ordinary listening levels.

**Origin.** EBU R 128 measurement terms and Adobe dialogue practice. [SRC-EBU-R128](../sources/bibliography.md#src-ebu-r128) · [SRC-ADOBE-ROOM](../sources/bibliography.md#src-adobe-room)

**Related.** `SND-002`, `SND-004`, `SND-010`, `SND-011`, `SND-013`

### SND-013

**Assemble clip audio into a single scene mix** · creative heuristic · priority 1 · medium confidence

Keep the final audio plan on an editable timeline. Retain native clip audio only where it serves the scene, with separate tracks for dialogue, ambience, Foley/effects and music as useful.

**Why it works.** Separate layers make continuity, synchronization and balance repairable when individual model outputs vary.

**Apply.** Any scene made from more than one independent generation. **Exception.** A cohesive single native take can supply a useful base. Save it separately and document what is embedded.

**Example.** Use one room-tone bed, a selected clean line across coverage, and matched contact cues at cuts. **Common mistake.** Importing each native track at full level so ambience, music or voices reset on every picture cut.

**LLM action.** Record audio ownership by cue, line source, room state, overlap handles and synchronization anchors. Plan replacement tracks before generating close dialogue. **Check.** Listen through each join, compare intended perspective and review the full export in addition to solo tracks.

**Origin.** Rulebook integration of the sound categories, ambience and split editing. [SRC-ADOBE-ROOM](../sources/bibliography.md#src-adobe-room) · [SRC-ADOBE-SFX](../sources/bibliography.md#src-adobe-sfx) · [SRC-ADOBE-JL](../sources/bibliography.md#src-adobe-jl) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd)

**Related.** `SND-002`, `SND-003`, `SND-004`, `SND-005`, `SND-007`, `SND-009`, `SND-012`

## Assemble a scene from independent clips

1. **Spot.** Mark cue ID, beat, source, world relation, listener, start and end, sync event, and whether a cue can carry over the picture cut.
2. **Choose dialogue.** Pick consistent takes or record a replacement track. Cut picture to the performance where possible. Cover unsalvageable lip sync with a listener or other motivated view, or regenerate that line with a stable reference.
3. **Build space.** Lay a scene-level room-tone or ambience bed. Select consistent perspective, and change it deliberately when the space, barrier or listener changes.
4. **Add action and music.** Align Foley and effects to physical contact and event timings. Choose which cue dominates each beat. Add music and silence for specific effects.
5. **Join.** Check picture handles and sound tails. For a picture cut at 00:08, incoming audio beginning at 00:07.5 makes a J-cut. Outgoing audio ending at 00:08.5 makes an L-cut. These offsets are examples.
6. **Review.** Solo dialogue, then review the full mix at ordinary levels, across every join and on the actual export. Record the destination's delivery requirements and measurement method.

Film audio can change the apparent meaning of a visually identical beat. Test that relationship by playing the scene with the intended cue, without it, and with an alternate perspective. Choose the version that carries the required story information and emotional effect. [SRC-CHION-AV](../sources/bibliography.md#src-chion-av) · [SRC-THOM-SND](../sources/bibliography.md#src-thom-snd) · [SRC-ADOBE-JL](../sources/bibliography.md#src-adobe-jl)
