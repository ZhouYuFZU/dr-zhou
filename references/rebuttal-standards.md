# DR-ZHOU Rebuttal Standards

## Tone

Be respectful, direct, and concrete. Do not sound defensive. Every response should either make a manuscript change, justify why no change is needed, or both.

Default DR-ZHOU tone is patient, technically serious, and slightly deferential. Show that the reviewer has helped improve the manuscript, but do not flatter excessively. Prefer `Thanks for your insightful comments`, `Many thanks for your constructive comments`, and `Thank you for underlining this deficiency`.

## Response Structure

For each reviewer comment:

1. Acknowledge the comment.
2. State the action taken.
3. Quote or summarize the manuscript change.
4. Explain why the change addresses the concern.
5. Mention location if known: section, page, paragraph, equation, figure, or table.

For major or complex comments, do not answer in one long paragraph. Split the response into subpoints with short labels, such as:

```text
The following are our responses:
1. <technical issue or subquestion>
2. <manuscript revision>
3. <scope or limitation>
```

or:

```text
Our response consists of three parts:
- <methodological clarification>
- <additional experiment or comparison>
- <revision made in the manuscript>
```

Default template:

```text
Response: Thank you for this valuable comment. We agree that ...
To address this concern, we have revised ...
Specifically, the revised manuscript now ...
This revision clarifies ...
```

## Opening and Revision Statement

For a full response letter, begin with a short global statement:

```text
We would like to thank the editors and reviewers for their helpful suggestions and constructive comments. We have studied all comments carefully and revised the manuscript accordingly. Detailed responses are provided below, and the corresponding revisions are marked in <color/style> in the manuscript.
```

Use `marked in blue` or `marked with red text` only when this is true in the submitted files.

## When the Reviewer Is Correct

Admit and fix:

```text
We agree with the reviewer that the previous description was insufficiently clear.
```

Use especially direct language for typos, unclear figures, missing definitions, incomplete references, inconsistent equations, and weak explanation:

```text
Thanks for pointing out this issue. We have corrected it as follows:
```

```text
Thank you for underlining this deficiency. We have added a more detailed explanation in ...
```

## When the Reviewer Misunderstands

Clarify without blaming:

```text
We apologize for the ambiguity in the original manuscript. The intended meaning was ..., and we have revised the text to make this explicit.
```

If the misunderstanding comes from unclear manuscript structure, accept responsibility first, then explain:

```text
We apologize for the insufficient clarity in the previous version. The intended meaning is ..., and we have revised Section ... to avoid this ambiguity.
```

## When Rejecting a Suggestion

Use evidence and scope:

```text
We appreciate this suggestion. In the present study, however, ... is outside the scope because ...
To avoid overclaiming, we have added a limitation statement ...
```

DR-ZHOU style allows gentle disagreement only after acknowledging the reviewer's concern. Avoid blunt rejection. Preferred pattern:

```text
We understand the reviewer's concern. However, we cannot fully agree that ... because ...
Nevertheless, to facilitate the reader's understanding, we have added a discussion on ...
```

When something is beyond the present paper, do not stop at `outside the scope`. Add a boundary and a useful manuscript change:

```text
This issue is important but falls beyond the scope of the present study because ...
To avoid overextending the claim, we have added a limitation/future-work statement in ...
```

## Manuscript Change Text

When possible, provide polished replacement text in English. Keep Chinese explanation separate from manuscript text.

Use a location-and-quote habit. After explanation, include:

```text
For clarity, we have added/revised the following description in Section ..., page ...:
"..."
```

If the paper was substantially reorganized, explicitly list the changes:

```text
For clarity, we have made extensive revisions throughout the manuscript:
1. Title: ...
2. Introduction: ...
3. Methodology: ...
4. Simulation/Experiment: ...
```

## DR-ZHOU Common Response Moves

- If the reviewer asks for background or definitions, add a compact explanatory paragraph to the manuscript and cite relevant literature if verified.
- If the reviewer asks about assumptions, explicitly list assumptions and state where they hold.
- If the reviewer questions practical implementation, answer with computational burden, sensor requirements, hardware feasibility, and current limitation.
- If the reviewer questions novelty or motivation, compare method families, state each limitation, then restate the paper's specific contribution.
- If the reviewer questions model validity, distinguish ideal physics, modeling approximation, parameter uncertainty, and validation evidence.
- If the reviewer requests more experiments, add feasible comparison, ablation, sensitivity, noise, or robustness tests when data exist; otherwise explain scope and add limitation/future work.
- If the reviewer points to a figure problem, correct the figure, state the exact plotting or scale issue, and avoid any impression of visual manipulation.
- If the reviewer asks about extension to modules/packs or broader applications, answer in levels: current proof-of-concept, reasonable assumptions, extension route, and limitation.
- If the reviewer raises the value of spatially distributed battery thermal modeling, explain nonuniformity, safety/aging relevance, sparse sensing, monitoring/diagnosis/control use, and why lumped models are insufficient for that claim.

## Technical Defense Pattern

For strong technical challenges, DR-ZHOU often uses this sequence:

1. Thank the reviewer and acknowledge the technical concern.
2. Break the concern into subquestions.
3. Give physical or mathematical reasoning.
4. Add or cite a figure/table/equation/remark in the manuscript.
5. State the practical implication and boundary of the claim.

Example skeleton:

```text
Thanks for your insightful comments. We hope the following explanations can address your concern.
1. <Physical/mathematical reason>
2. <Comparison with alternative method>
3. <Revision made in the manuscript>
```

## Risk Checks

- Do not promise new experiments unless the data exist or the user explicitly confirms.
- Do not claim statistical significance without tests.
- Do not add citations that have not been verified.
- Do not overuse `we sincerely thank`; once per response is enough.
- Do not use `You are indeed an expert in this field` routinely. It appears in older letters but should be softened to `This is an insightful and important point`.
- Do not write `we tried our best` inside individual responses unless used in the global cover statement; concrete revisions are stronger.
- Do not say revisions are marked in a color unless the manuscript actually uses that marking.
