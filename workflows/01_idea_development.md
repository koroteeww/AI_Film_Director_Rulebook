# 01 · Idea development

## Inputs

User premise, intent, language, constraints, target platform and runtime if provided. The user's supplied idea is required.

## Procedure

1. Restate the premise and preserve supplied people, world and ending constraints. Separate user decisions from suggestions.
2. Identify protagonist or focal experience, pursuit, motive, resistance, stakes, theme, genre, tone and emotional promise.
3. Identify what could be shown or heard, and what should stay open. Flag only feasibility issues that could change the creative choice. Ask for missing essentials when necessary.

## Applicable rules

[DRA-001](../rulebooks/01_dramaturgy.md#dra-001) · [DRA-003](../rulebooks/01_dramaturgy.md#dra-003) · [DRA-006](../rulebooks/01_dramaturgy.md#dra-006) · [DRA-016](../rulebooks/01_dramaturgy.md#dra-016)

## Output contract

Film brief with project_id, title, premise, authorship_notes, creative_intent, target_runtime_s, aspect_ratio, tone, genre, focal_character, dramatic_question, goal, stakes, constraints, assumptions and open_questions. Text fields may be provisional. Store questions separately from user decisions.

## Reusable prompt

> Use my supplied idea and constraints. Return a short film brief with a concrete focal action, meaningful stakes, an emotional promise, visual and sonic opportunities, and the few decisions that remain open. Label any optional alternative as a proposal. Preserve my creative choices.

## Quality check

- The brief matches the supplied premise and language.
- A viewer-facing goal or organizing question and emotional intention are clear.
- A workable scope is plausible at the selected runtime.

## Revision trigger

Revise when the idea changes, the dramatic engine is unclear, or a required constraint is unknown.

## Handoff

Pass the brief, assumptions, decisions and target runtime to story structure.
