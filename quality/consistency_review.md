# M15 · Consistency review

**Review date** 2026-11-06. The pre-audit checkpoint was [`f2bcc207`](https://github.com/koroteeww/AI_Film_Director_Rulebook/commit/f2bcc20755b8c0d174d2d0334095e4730588e9fb). GitHub history records a separate research commit for each completed milestone.

| Area | Verified result |
| --- | --- |
| Rulebook | Seven domain chapters and 100 unique rules. All required fields were present. Rule IDs, principles and validation text agreed between Markdown and YAML. |
| Cross-references | 485 related-rule references resolve. More than 1,000 repository-relative links and anchors passed the navigation check. All 28 starter rules resolve to the catalog and their chapters. |
| Evidence | 126 unique source records. Every rule and model profile links to registered evidence. Corrected a course number and two bylines during spot checks. |
| Production | Ten stage files contain inputs, procedure, applicable rules, output, reusable prompt, review, revision and handoff. The system prompt links each mode to its stage. |
| Machine-readable data | Parsed three YAML registries and four JSON Schema files. Resolved the project schema's relative scene, shot and clip references. |
| Schema behavior | Exercised 20 positive and negative fixtures in a local keyword-level harness. Cases cover endpoint roles, nested IDs, source-inherited editing, extension, long-clip fields, trim metadata and runtime boundaries. |
| Technical research | Five named capability profiles, including three 30-second profiles. The rulebook keeps a 15-second planning ceiling and checks any longer request against a supported profile and mode. |
| Quality | The five working rubric weights total 100. Stage checks, continuity and release gates are distinct. |
| GitHub | Compared the content of 12 key baseline files against their GitHub blob hashes. The [progress history](../PROGRESS.md) identifies the final checkpoint and earlier work. |

## Limits carried forward

Public documentation supports the Seedance and CapCut entries. Provider behavior, exact timestamp adherence, usable take quality, account availability and rendered CapCut exports still need tests in the user's production context. Several copyrighted works are recorded as catalogues or limited excerpts, with the intended scope stated. The schema checks use a local harness covering the keywords used. A standalone Draft 2020-12 validator was unavailable in the runtime.

Start a film from the user's premise using the [AI Director prompt](../prompts/AI_DIRECTOR_SYSTEM_PROMPT.md) and [idea development workflow](../workflows/01_idea_development.md). Use the [open questions](../research/open_questions.md) to record new production evidence or narrower source verification.
