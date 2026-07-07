# DR-ZHOU Revision Rubric

Use this checklist before and after revision.

## Title and Abstract

- Title is concise, preferably within about 15 words when feasible.
- Title directly reveals the object, method, or core contribution.
- Avoid `Research on...` and `Study of...`.
- Abstract follows a compact line: problem -> method -> theoretical/technical core -> quantitative validation -> implication.
- Abstract includes key quantitative results when available.
- Abstract has no citations, formulas, nonstandard abbreviations, or unsupported claims.
- Every abstract number and conclusion is consistent with the body, figures, and tables.

## Introduction

- First paragraph reaches the engineering pain point within three sentences.
- Related work is grouped into methodological families, not listed paper by paper.
- The gap is explicit and technical: what existing methods cannot handle, under what constraints, and why.
- The penultimate part explains motivation and basic idea before listing contributions.
- Contributions are bullet points when appropriate, about three items, and each is verifiable.
- The final paragraph gives paper organization.

## Problem Formulation

- This section contains only problem definition and a concise solution overview.
- No experimental results, detailed algorithm steps, or long related-work discussion.
- Engineering reality is abstracted into mathematical language: sets, mappings, objectives, constraints, assumptions, inputs, outputs.
- All symbols are defined on first use.
- A qualified reader can understand exactly what problem is solved and under what conditions.

## Methodology

- Structure is layered: overall framework -> module 1 -> module 2 -> module 3.
- Start with a clear framework figure or logic overview when revising a full paper.
- Explain the mathematical or physical intuition of each core module.
- Use equations, algorithms, and pseudocode where they are clearer than prose.
- Keep methods separated from results: do not preview performance improvements inside method description.
- Include enough hyperparameters, model details, data processing, and implementation settings for reproducibility.

## Results and Discussion

- Use figures and tables as primary evidence; text summarizes and interprets.
- Large numerical comparisons should be in tables, not buried in prose.
- Results should answer the paper's claims in the same order as the contributions.
- For strong results, explain which design component causes the improvement.
- For weak results, explain limitation, data property, operating condition, or model boundary.
- Experimental setup must include datasets, metrics, baselines, versions/settings, hardware/software environment, and hyperparameters where relevant.

## Conclusion

- Conclusion must not simply repeat the abstract.
- It should cover method contribution, key findings, achieved effect, limitation or future work.
- Claims must be consistent with evidence and not oversold.

## References

- Prefer recent high-level journal papers, especially IEEE Transactions in the relevant field.
- Avoid or minimize arXiv, theses, and excessive conference citations unless necessary.
- Recent three-year literature should be sufficient for frontier awareness.
- Use BibTeX when possible and ensure author, title, venue, volume, issue, pages, year, and DOI are complete.

## Scientific Aesthetics

- Figures should look like professional scientific work, not technical reports.
- Formulas should be clean, aligned, and symbolically consistent.
- Tables should generally use three-line style.
- Vector graphics are preferred: PDF, SVG, EPS, or embedded vector output.
