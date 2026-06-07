# Five-Dimension Prompt Coding Report

This report codes each `iteration_X_prompt` using the five dimensions from the screenshot: prompt function, prompt sophistication, conceptual focus, AI reasoning uptake, and energy change.

The coding is rule-based and audit-friendly. It should be treated as a first-pass coding layer suitable for review, refinement, and reliability checking.

Project rows with prompts: 70
Prompt rows coded: 399
Student rows matched to assessment with both pre/post: 48

## Coding Scheme

- Prompt function: generate, revise, optimize, evaluate, conceptual inquiry, aesthetic, off-task, or unclear.
- Prompt sophistication (PSI): 0-10 total from five 0-2 sub-scores: goal clarity, constraints/parameters, scientific concepts, evaluation criteria, and specificity.
- Conceptual focus: 0-3 score plus label for thermal energy, orientation/solar, renewable energy, envelope/openings, general sustainability, or none.
- AI reasoning uptake: 0-2 score based on whether the current prompt reuses terms or scientific ideas from the previous AI reasoning response.
- Energy change: improved, worsened, or maintained based on change in `iteration_X_net` from the previous iteration. Lower net energy is treated as improvement.

## Overall Distributions

Prompt function counts:
- generate: 172
- conceptual_inquiry: 104
- revise: 64
- optimize: 36
- unclear: 11
- aesthetic: 11
- evaluate: 1

Conceptual focus counts:
- thermal_energy: 145
- none: 101
- renewable_energy: 96
- envelope_openings: 31
- orientation_solar: 24
- general_sustainability: 2

Energy change counts:
- maintained: 242
- improved: 57
- worsened: 25

## Assessment-Linked Descriptives

For matched students with both pre/post scores, average student-level PSI was 4.20/10.
Average conceptual focus was 1.64/3.
Average AI reasoning uptake was 0.80/2.

Next analytic step: use these coded dimensions as interpretable Stage 2 features instead of raw prompt text or embeddings.
