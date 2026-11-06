# 02 · Story structure

## Inputs

Film brief and approved constraints. User-supplied beats or ending, if any.

## Procedure

1. Compare one structure that fits the premise and one alternative if it clarifies a real tradeoff.
2. Assign stable BT IDs to consequential beats. Track viewer knowledge, objective, obstacle, action, result and change in feeling.
3. Allocate rough seconds for orientation, pressure, decision, consequence and any afterbeat. Choose reasonable scene scope after a read.

## Applicable rules

[DRA-002](../rulebooks/01_dramaturgy.md#dra-002) · [DRA-005](../rulebooks/01_dramaturgy.md#dra-005) · [DRA-008](../rulebooks/01_dramaturgy.md#dra-008) · [DRA-015](../rulebooks/01_dramaturgy.md#dra-015) · [DRA-016](../rulebooks/01_dramaturgy.md#dra-016) · [DRA-017](../rulebooks/01_dramaturgy.md#dra-017)

## Output contract

Beat outline with structural_approach, dramatic_question, planned_runtime_s, credits_reserve_s, beats[] with beat_id, purpose, objective, obstacle, action, result, viewer_knowledge, emotional_state_in, emotional_state_out, estimated_duration_s and setup/payoff references.

## Reusable prompt

> Build a timed beat outline from the approved brief. Preserve author-supplied story facts. For each beat show the causal link or intentional associative relation, the viewer's knowledge and the emotional turn. Explain any open ending in one sentence.

## Quality check

- Beat durations plus reserve fit the target.
- Setup, turn and consequence are traceable.
- The chosen structure works without imposing feature-length page or beat formulas.

## Revision trigger

Revise when a turn relies on a missing cause, the same dramatic job repeats, or a timed read lacks room for a necessary reaction.

## Handoff

Pass the ordered beats and duration budget to screenplay.
