# DR-ZHOU Section Patterns

## Title

Preferred pattern:

```text
<Constraint/Context>-Aware <Method> for <Engineering Task> in <System>
<Method> for <Task> Under <Practical Constraint>
<Physics/Model>-Informed <Learning/Estimation/Diagnosis> for <Object>
```

Good title signals from source examples:

- `Operating-Envelope-Aware Fault Detection for Partially Known Nonlinear Parabolic Distributed Parameter Systems`
- `Rapid Battery Temperature Field Reconstruction Under Terminal-Constrained Sensing: A Physics-Informed Koopman Approach`
- `A Contact-Aware Spectral Modeling Framework for 3-D Thermal Field Reconstruction in Stacked Battery Modules`

## Abstract

Use 6-8 compact sentences:

1. Practical challenge or methodological bottleneck.
2. Paper's proposed method/framework.
3. Main components of the method.
4. Theoretical property or error/stability/detectability analysis if present.
5. Validation setting.
6. Quantitative results.
7. Engineering implication.

Avoid generic final sentences. The last sentence should state what capability the work enables.

## Introduction

Recommended structure:

1. Engineering importance and safety/control relevance.
2. Practical sensing/modeling/computing constraints.
3. Method families and their limitations.
4. Precise unresolved gap.
5. Motivation and basic idea of this work.
6. Contributions as verifiable bullets.
7. Paper organization.

For IEEE papers, contribution bullets should not be slogans. Each bullet should include an artifact and evidence type:

- method/framework component
- theoretical result
- validation or deployment result

## Problem Formulation

Include:

- system/domain definition
- available measurements and constraints
- objective
- assumptions
- desired output
- evaluation or decision criterion when relevant

Do not include:

- literature survey
- performance numbers
- detailed module derivations
- repeated motivation from the Introduction

## Methodology

Start each major module with:

1. What problem this module solves.
2. What input and output it has.
3. How it is formulated mathematically.
4. Why this design is suitable for the physical/engineering constraint.

When revising method prose, make the dependency chain explicit:

```text
The framework first ...
Then, ...
To compensate for ...
Finally, ...
```

## Results

Recommended order:

1. Experimental setup and metrics.
2. Overall comparison.
3. Ablation or component analysis.
4. Robustness/generalization/operating-condition analysis.
5. Computational cost or embedded deployment if relevant.
6. Discussion of failure modes or limitations.

Do not merely write `Fig. X shows that the proposed method performs better`. Explain why, by linking the evidence to a design component.

## Figure Legends

For engineering figures, captions should identify:

- what is shown
- the experimental condition or scenario
- compared methods or modules
- variables/units when not obvious
- key takeaway only when the journal style allows it

## Response to Reviewers

Use a respectful, concrete, evidence-based tone:

```text
Response: Thank you for this insightful comment. We agree that ...
To address this issue, we have ...
The revised manuscript now ...
```

Never argue abstractly when a concrete manuscript change can answer the reviewer.
