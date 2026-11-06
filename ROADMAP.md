# Research roadmap

The initial release targets 80–120 cited rules across seven filmmaking domains and a 20–30 rule beginner shortlist. Domain targets below total 97. Counts are planning targets and can shift when the evidence warrants it.

| Milestone | Expected files | Definition of done |
| --- | --- | --- |
| M01 · Film schools and sources | `research/film_schools.md`, `research/hollywood_traditions.md`, `research/russian_soviet_traditions.md`, `research/open_questions.md`, `sources/bibliography.md`, `sources/source_index.yaml` | Compare the requested schools using public institutional evidence. Map the named authors and works to usable evidence or an explicit access gap. Document evidence classes and bilingual terminology. |
| M02 · Dramaturgy | `rulebooks/01_dramaturgy.md`, `rules/rule_catalog.yaml` | Extract about 16 rules with scene-scale validation and adaptations for 3-, 5-, and 7-minute films. Compare competing structures and document exceptions. |
| M03 · Directing | `rulebooks/02_directing.md`, `rules/rule_catalog.yaml` | Extract about 14 rules that turn intentions, viewpoint, beats, and performance into observable staging and coverage decisions. |
| M04 · Cinematography | `rulebooks/03_cinematography.md`, `rules/rule_catalog.yaml` | Extract about 16 rules for coverage, composition, lenses, movement, and spatial continuity. Translate them into coherent camera and subject instructions. |
| M05 · Mise-en-scène | `rulebooks/04_mise_en_scene.md`, `rules/rule_catalog.yaml` | Extract about 12 rules that make blocking, set, props, costume, and spatial power legible. Include frame-state and screen-geography checks. |
| M06 · Lighting and color | `rulebooks/05_lighting_and_color.md`, `rules/rule_catalog.yaml` | Extract about 12 rules for motivated sources, contrast, light quality, color, and cross-shot matching. |
| M07 · Sound | `rulebooks/06_sound_design.md`, `rules/rule_catalog.yaml` | Extract about 13 rules for dialogue, perspective, off-screen cues, ambience, Foley, music, silence, dynamic range, and bridges. Show how to assemble a scene across independent clips. |
| M08 · Montage and editing | `rulebooks/07_montage_and_editing.md`, `rules/rule_catalog.yaml`, `rules/priority_rules.md` | Extract about 14 rules from continuity and montage traditions, with explicit exceptions and cut checks. Publish a 20–30 rule beginner shortlist across all domains. |
| M09 · Seedance capabilities | `research/seedance_research.md`, `ai_production/seedance_manual.md`, `ai_production/seedance_profiles.yaml` | Date and identify the exact provider, model, and input mode behind each feature claim. Separate documented limits, demonstrations, and unverified claims. Verify any 30-second entry or leave it unverified. |
| M10 · Generation failure modes | `ai_production/failure_modes.md`, `ai_production/continuity_management.md` | Map every named failure to likely causes, planning, reference strategy, mitigation, detection, and repair. Describe an inspection and regeneration loop. |
| M11 · End-to-end workflow | `workflows/01_idea_development.md` through `workflows/10_editing.md`, `ai_production/image_generation.md`, `ai_production/capcut_workflow.md` | Give every stage input, procedure, rule IDs, output, prompt, check, revision trigger, and handoff. Verify CapCut capabilities by platform and source. |
| M12 · Prompts and schemas | `prompts/` role prompts, `schemas/` JSON Schemas, `templates/` | Publish reusable role and frame/motion prompts, validate film/scene/shot/clip schemas, and align templates with the handoff contracts. |
| M13 · Evaluation and quality | `quality/evaluation_rubric.md`, `quality/continuity_checklist.md`, `quality/final_film_checklist.md`, `quality/rights_and_disclosure.md` | Publish a 100-point working rubric and review gates for script, storyboard, generated clips, rough cut, and finished film. Distinguish festival policies from jurisdiction-specific legal requirements. |
| M14 · AI Director system prompt | `prompts/AI_DIRECTOR_SYSTEM_PROMPT.md` | Define three operating modes, retrieval, handoffs, exception handling, continuity, user authorship, and GitHub project persistence when requested. |
| M15 · Consistency review | `README.md`, `CHANGELOG.md`, `PROGRESS.md`, `quality/consistency_review.md`, audit fixes | Check internal links, IDs, source support, counts, prompt and schema alignment, capabilities, and readiness for a future user idea. Record unresolved evidence limits. |

## Publication and evidence standards

Every milestone commit includes the deliverables, updates to the source index and research log as applicable, and a matching progress entry. Use the same rule ID throughout Markdown, YAML, prompts, and workflows. Mark candidates and unverified details explicitly.

The rule catalog uses the fields `rule_id`, `name`, `domain`, `type`, `priority`, `origin`, `principle`, `why_it_works`, `when_to_apply`, `when_to_break`, `good_example`, `common_mistake`, `ai_implementation`, `validation`, `related_rules`, `source_ids`, and `confidence`. Give technical constraints, conventions, techniques, dramaturgical principles, and creative heuristics distinct types. A classroom rule, theory, or useful production default may have a narrower scope than a physical constraint.

For source records, retain author, title, institution or publisher, publication year when available, URL, access date, supported finding, evidence class, and scope. Preserve Russian terms alongside an English gloss when useful. Keep a separate record of any AI-specific adaptation or inference.

Final acceptance requires all seven domain rulebooks, a consistent catalog, a verified model manual, a complete production pipeline and rubric, an AI Director system prompt, and a checked GitHub checkpoint. [Progress](PROGRESS.md) records verified status.
