# Seedance production manual

Use this guide after the story, staging and shot purpose are clear. Read the [capability research](../research/seedance_research.md) and the [documented profiles](seedance_profiles.yaml) for the exact interface. Treat every output as a take to inspect.

## Choose the smallest workable input mode

| Mode | Choose it when | Prepare and verify |
| --- | --- | --- |
| Text to video | Identity, composition and precise endpoints are flexible, or the shot is exploratory | Give one key action, one camera behavior and a clear final image. Save the approved result as a reference if the sequence needs it. |
| First-frame image to video | Opening identity, geometry, lighting or camera is important | Use one approved frame with adequate room for action. Check the first usable frame and preserve the reference's meaningful attributes. |
| Dedicated first/last frames | The viewer must see a specific before/after state and the two can be joined with plausible movement | Match identity, prop state logic, geometry, aspect and light. Describe the path between them and inspect for morphing or a hidden cut. |
| Multimodal reference | An identity, composition, motion, rhythm or voice needs guidance without locking both endpoints | Bind each reference to a job. Clarify what to retain from the motion reference and what to ignore. Confirm exact provider syntax and limits. |
| Edit | A take works and a bounded region, event or sound needs repair | Pin edit mode where supported, name the part and expected change, and inspect changes outside the target. Keep the original and compare. |
| Extend | An approved shot needs additional duration and the relevant endpoint is stable | Pin extension, identify which end, describe the new action and compare the seam. The returned file may include overlap or source content. Trim it in the timeline. |

Use an opening reference plus separate character or location references when incompatible start and end frames would force a morph. Use a shot/reverse, insert, staged cut, or deliberate sound bridge when the beat needs several changes that one take cannot reliably express.

## Write a generation brief

1. Pin provider, model ID or UI label, mode, duration, aspect ratio, resolution and audio setting. Bind references by stable asset ID and the provider's actual slot or token. Record the intended edit duration separately.
2. State initial camera framing, world layout, character state, light and relevant object states.
3. Give one primary subject action in chronological order. State camera movement independently, with a trigger, path and target. Describe only relevant environmental motion.
4. Describe the intended final pose, object state, composition and hold or overlap for the cut. Protect identity, light direction and screen direction. Keep conditions compatible with any paired endpoints.
5. Give essential audio cues or arrange a replacement track. For native speech, specify speaker and short line, language and when it occurs. Check voice, sync and intelligibility independently.
6. Generate and inspect a small set of takes. Keep take IDs, settings, source references, start and end stills and reasons for rejection. Compare across adjacent shots in the scene.

| Shot problem | Starting brief | Fallback |
| --- | --- | --- |
| Static shot | Locked position, stable horizon and composition, one timed subject cue | Use a still hold, ambience or a simple insert when movement adds little |
| Camera movement | Specify rotation or translation and start/end view | Reduce travel, rotate less, or separate the reveal into a cut |
| Dialogue | Short line, one speaker at a time, stable face and light | Chosen dialogue track, listener coverage, resync or regenerate |
| Emotional close-up | A playable action and one readable gaze, breath or hand change | Hold the clean portion or let sound and the adjacent shot supply context |
| Two-person interaction | Shared spatial map and distinct identity, gaze and prop roles | Cover action and reaction separately, with a matched state |
| Action | One ordered physical action and visible contact or reaction | Split at a readable action phase and cut on motion or use an insert |
| Transition | Clear endpoint geometry, gesture, graphic relation or sound bridge | Use an editorial cut and overlap instead of a generated morph |
| Long take | One coherent path with planned milestones, a terminal state and backup coverage | Split at a motivated beat, or extend a verified endpoint and check the seam |

Use prose for order and optional approximate timestamps as cues. Precise frames belong in the edit timeline. Use the 15-second default for planning. A single generation above 15 seconds needs a mode that explicitly supports that duration, a reason to sustain the take, and a split plan if the result drifts. A 30-second capacity is also available for reference-guided clips that contain internal cuts on some surfaces. Treat each usable continuous view as a separate shot in the edit plan.

## Accept or revise

Compare first, middle, endpoint and every key contact or expression. Check identity, costume, hands, prop state, axis, light, intended camera motion, final geometry, voice and sound continuity. Retain only the usable source interval. Where a clip is wrong, decide between trimming, a targeted edit, approved alternate coverage, or regeneration with fewer concurrent instructions. Use the [camera](../rulebooks/03_cinematography.md), [staging](../rulebooks/04_mise_en_scene.md), and [sound](../rulebooks/06_sound_design.md) chapters for the corresponding checks.
