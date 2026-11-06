# AI Film Director Rulebook

A source-backed knowledge base for turning a user's original idea into a 3–7 minute AI short film. It connects dramatic intent to performance, staging, camera, lighting, sound, editing, and feasible generation instructions.

## Start here

- [Research roadmap](ROADMAP.md) lists the deliverables and acceptance criteria for M01–M15.
- [Progress](PROGRESS.md) shows the current checkpoint and the next action.
- [Bibliography](sources/bibliography.md) and the [source index](sources/source_index.yaml) record what each source supports.
- [Research log](research/RESEARCH_LOG.md) records decisions, open questions, and source limitations.

## How the rulebook is organized

| Location | Use |
| --- | --- |
| `research/` and `sources/` | Evidence, reading paths, and unresolved questions |
| `rulebooks/` and `rules/` | Seven filmmaking domains and the machine-readable rule catalog |
| `workflows/`, `prompts/`, `schemas/`, and `templates/` | Stage contracts, runnable instructions, and reusable production forms |
| `ai_production/` and `quality/` | Model and editing guides, failure recovery, continuity and review |
| `projects/` | User-authorized film projects |

Read the roadmap for planned files. Each milestone adds its deliverables as they are researched.

## Production vocabulary

- A **scene** is a dramatic unit. It can contain several beats and shots.
- A **beat** is a meaningful change in action, information, intention, or emotion.
- A **shot** is one continuous view in the finished edit.
- A **generation clip** is a model output. It may supply a shot, an excerpt, or several planned shots if the verified mode and edit support that design.
- Plan generated clips at **15 seconds or less** as a working ceiling, subject to the selected interface. Verify any 30-second mode for its exact model, provider, and input mode. Plan shot length from the beat and the edit.

Resolve story and emotional intent, then audience comprehension, dramatic continuity, cinematic expression, technical feasibility, and visual novelty. Label conventions and creative heuristics as such. Record intended exceptions and the effect they should have.

## Resume research

1. Read this file, the roadmap, and the progress log. Inspect recent commits and any files you will change.
2. Work on the next incomplete milestone and check sources in English and Russian where relevant. Give every substantive rule a stable ID, evidence, an AI adaptation, and a validation check.
3. Commit each verified research batch and its progress update together. Use `main` when permitted. If branch protection requires a pull request, keep the work on a research branch and record its status.
4. Update existing research when evidence changes. Preserve existing IDs and record material changes.

Begin a film only after the user supplies its premise. Use the repository's general knowledge independently of individual film projects.
