# Motion prompt

| Field | Fill in |
| --- | --- |
| clip_id and shot_ids | |
| provider, model, profile_id and mode | |
| planned_duration_s, duration_basis, requested_duration_s if fixed | |
| aspect_ratio, resolution and native audio setting | |
| reference_assets and provider bindings | |
| capability_source_id, long_clip_reason and fallback_plan if above 15 s | |

> Start in {camera, character, prop, environment and light state}. After {trigger}, {one ordered primary action with observable performance}. Camera {independent movement type, path and destination}. Environment {relevant motion}. End on {final pose, object state, frame and hold or overlap}. Preserve {identity, costume, world geometry, light and axis}. Audio {cue, speaker, line and perspective, or replacement plan}.

Use the [generation clip schema](../schemas/generation_clip.schema.json). Inspect the start, event, end, audio and adjacent cuts. Record the take and usable interval.
