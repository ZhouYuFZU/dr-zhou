# DR-ZHOU Figure and Table Standards

## Evidence First

Figures and tables should carry the scientific evidence. Text should summarize patterns, interpret causes, and connect results to contributions.

## Tables

- Use tables for dense numerical comparisons.
- Prefer three-line tables.
- Table titles should be concise and informative.
- Include units in headers.
- Align decimals and use consistent significant digits.
- Include baseline methods, proposed method, and key ablations when claims depend on comparison.
- Avoid copying a table's numbers into a long paragraph; state only the most important deltas.

## Figures

- Prefer vector graphics: PDF, SVG, EPS, or embedded vector output.
- Ensure figure text, axis labels, legends, and caption font sizes are visually consistent.
- Use professional scientific colors with sufficient contrast.
- Avoid distorted aspect ratios, crowded legends, fuzzy screenshots, and inconsistent line widths.
- For multi-panel figures, each panel must have a clear role in the argument.
- If a framework figure exists, it should summarize the full paper logic and be visually polished.

## Captions

Captions should be self-contained enough for reviewers to understand the evidence without hunting through the paragraph.

Minimum caption checks:

- Expand nonstandard abbreviations.
- Name the scenario, profile, dataset, or condition when relevant.
- Include variable units when necessary.
- Explain panel labels `(a)`, `(b)`, `(c)` in order.
- Avoid overlong interpretation unless the journal style supports extended captions.

## Full-Paper Figure Logic

Typical engineering SCI figure sequence:

1. Overall framework or mechanism.
2. System setup, sensing configuration, or data pipeline.
3. Main performance comparison.
4. Ablation/component verification.
5. Robustness, generalization, or operating-envelope analysis.
6. Computational cost or deployment validation.

When auditing a paper, check whether the figure sequence mirrors the contribution sequence.

## Common Problems to Flag

- Abstract claims a metric not visible in any result table/figure.
- A figure shows improvement but the text does not explain the mechanism.
- A method module is claimed as important but lacks ablation.
- A comparison is unfair because baselines, hyperparameters, or versions are missing.
- A caption names variables that are not defined in the text.
- Units differ between figure, caption, and main text.
