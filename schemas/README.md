# Production schemas

These Draft 2020-12 JSON Schemas validate a film brief, scene record, planned shot, and generation clip record. The project schema references the other three by relative URI. Register their `$id` values in a local resolver or let the validator resolve them from the same published schema directory.

| Record | ID | Role |
| --- | --- | --- |
| [Film project](film_project.schema.json) | `FP-<slug>` | User premise, creative intent, 180–420 s target and optional nested scene, shot and clip records |
| [Scene](scene.schema.json) | `SC-001` | Dramatic unit with beats and intended state changes |
| [Shot](shot.schema.json) | `SH-001` | Planned continuous view in the edit with camera, scene, beat and continuity links |
| [Generation clip](generation_clip.schema.json) | `CL-001` | Request for a generation or modification plus optional observed result |

Use stable `BT-001` beat IDs, `FR-001` frame IDs, `AS-001` asset IDs, `CH-001` character IDs and `PR-001` prop IDs. Assign IDs once across the project and never reuse an ID for a different object. Use logical asset IDs and keep actual media locations in the approved project storage.

Validate each standalone record as well as the film manifest. Then check uniqueness across records, references to existing scenes, beats, shots, frames and assets, rule and source IDs, authorized state changes, and that `0 ≤ usable_in_s < usable_out_s ≤ actual_duration_s` when result trims are present. These are cross-record and cross-value checks.

For every generation, verify the provider, exact model, mode, references, resolution and duration against the [capability profile](../ai_production/seedance_profiles.yaml) or the documented current interface. A request above 15 seconds requires a listed profile supporting that mode and duration, a matching source ID, a creative reason and a fallback. Update the evidence-backed profile registry before using an unlisted 30-second surface. JSON Schema checks the required fields. The provider and cross-record checks verify what the values mean.

`planned_duration_s` is a planning length, while `requested_duration_s` is the integer sent when the mode permits a fixed request. An edit uses a source-inherited duration. An extension plans the added segment. Use the observed output duration and actual usable trim when the returned file includes an original or overlapping part.
