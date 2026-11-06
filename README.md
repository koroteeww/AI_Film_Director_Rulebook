# AI Film Director Rulebook

A source-backed working manual for turning an original idea into a 3–7 minute AI short film. It connects story and emotional intent to direction, staging, camera, lighting, sound, generation and editing.

## Start a film

Give the LLM your original premise and the stage you want to work on. Use the [AI Director system prompt](prompts/AI_DIRECTOR_SYSTEM_PROMPT.md) to route the work. It can help with a single stage or guide the full production.

1. Start with the [28 starter rules](rules/priority_rules.md) and the relevant chapter below.
2. Use the [ten workflows](workflows) to move from idea and screenplay through scenes, shots, storyboard, frames, Seedance, sound and CapCut.
3. Prepare records with the [role prompts](prompts), [production templates](templates) and [JSON schemas](schemas/README.md).
4. Review the cut with the [100-point working rubric](quality/evaluation_rubric.md), [continuity checklist](quality/continuity_checklist.md) and [release checks](quality/final_film_checklist.md).

## Cinematic rulebooks

| Domain | Rule IDs | YAML |
| --- | --- | --- |
| [Dramaturgy and screenwriting](rulebooks/01_dramaturgy.md) | DRA-001–DRA-017 | [YAML](rules/01_dramaturgy.yaml) |
| [Directing](rulebooks/02_directing.md) | DIR-001–DIR-014 | [YAML](rules/02_directing.yaml) |
| [Cinematography and camera movement](rulebooks/03_cinematography.md) | CIN-CAM-001–CIN-CAM-018 | [YAML](rules/03_cinematography.yaml) |
| [Mise-en-scène](rulebooks/04_mise_en_scene.md) | MIS-001–MIS-012 | [YAML](rules/04_mise_en_scene.yaml) |
| [Lighting and color](rulebooks/05_lighting_and_color.md) | LGT-001–LGT-012 | [YAML](rules/05_lighting_and_color.yaml) |
| [Sound design](rulebooks/06_sound_design.md) | SND-001–SND-013 | [YAML](rules/06_sound_design.yaml) |
| [Montage and editing](rulebooks/07_montage_and_editing.md) | EDT-001–EDT-014 | [YAML](rules/07_montage_and_editing.yaml) |

The [YAML catalog index](rules/rule_catalog.yaml) maps rule ID prefixes to the seven domain files and defines the shared priority and confidence scales. Each domain file has a `rules` list. Open the domains you need, or combine their `rules` lists to load all 100 rules. The [bibliography](sources/bibliography.md) and [YAML source index](sources/source_index.yaml) record evidence, scope, and access limitations.

## Production guides

- [Seedance 2.0 and 2.5 manual](ai_production/seedance_manual.md), [capability evidence](research/seedance_research.md), and [interface profiles](ai_production/seedance_profiles.yaml)
- [Image generation](ai_production/image_generation.md), [continuity management](ai_production/continuity_management.md), and [13 failure modes](ai_production/failure_modes.md)
- [CapCut workflow](ai_production/capcut_workflow.md) and [rights and disclosure](quality/rights_and_disclosure.md)

A **scene** is a dramatic unit, a **beat** is a meaningful change, and a **shot** is a continuous view in the finished edit. A **generation clip** is the model's output, which can supply a shot, part of one, or several planned shots. Plan clips at **15 seconds or less** by default. Use a longer single generation only where the exact provider, model and mode are documented. Choose the finished shot length by its dramatic job.

## Research and maintenance

Read the [roadmap](ROADMAP.md), [progress checkpoint](PROGRESS.md), [research log](research/RESEARCH_LOG.md), and [consistency review](quality/consistency_review.md) before changing the knowledge base. Use [open questions](research/open_questions.md) for bounded evidence gaps. Preserve stable IDs and update sources and progress with every research batch. Use `main` when permitted and a research branch and pull request when branch protection requires one.

[Film-school comparison](research/film_schools.md) · [Hollywood and international traditions](research/hollywood_traditions.md) · [Russian and Soviet traditions](research/russian_soviet_traditions.md)

Store user-authorized productions under [projects](projects/README.md) and keep private assets and permission records in suitable private storage.
