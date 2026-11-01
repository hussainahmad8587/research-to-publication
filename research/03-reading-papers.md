# Reading Papers Critically

> Read to understand the question, reconstruct the reasoning, evaluate the evidence, and develop your own judgment.

## Choose the Appropriate Reading Depth

Not every paper requires the same attention.

| Reading level | Purpose | Typical focus |
| --- | --- | --- |
| Quick scan | Decide whether the paper matters | Abstract, figures, main findings |
| Focused reading | Understand a relevant contribution | Motivation, method, evaluation |
| Deep study | Support your own research | Assumptions, implementation, reproduction |

Adjust your effort to the paper’s relevance.

## Step 1. Build an Overview

Begin with the title, abstract, major figures, results, and conclusion.

Identify:

- The task.
- The research problem.
- The proposed contribution.
- The main evidence.
- Its relevance to your project.

Avoid getting stuck in technical details before understanding the overall purpose.

### Write a Short Overview

> This paper investigates ______. It proposes ______ and evaluates it using ______. Its main reported finding is ______.

## Step 2. Identify the Central Question

Separate the research question from the proposed solution.

Ask:

1. What uncertainty or limitation motivates the work?
2. Why does it matter?
3. Who or what is affected?
4. Under which conditions is the question studied?

A useful question remains meaningful even if the proposed method fails.

## Step 3. Understand the Existing Work

Determine what was already possible before this paper.

Examine:

- The closest competing approaches.
- Established assumptions.
- Known limitations.
- Previous evidence.
- Differences in experimental settings.

Before studying the full solution, briefly consider how you would investigate the problem yourself.

## Step 4. Reconstruct the Method

Trace the approach from input to output.

For each important component, identify:

| Question | What to understand |
| --- | --- |
| What enters it? | Inputs and representations |
| What does it do? | Main operation |
| Why is it included? | Intended function |
| What does it assume? | Conditions needed for it to work |
| How is it trained? | Objective and optimization |
| How is it evaluated? | Evidence supporting its role |

Explain the method in your own words.

If you cannot explain a component, identify the missing prerequisite or unclear detail.

## Step 5. Evaluate the Experiments

Ask whether the evaluation actually addresses the research question.

### Data

- Are the datasets relevant?
- How were samples selected?
- Are labels and preprocessing described?
- Could information leak between splits?

### Comparisons

- Are the baselines appropriate?
- Were they tuned fairly?
- Are training data and resources comparable?
- Is a simpler alternative missing?

### Results

- Do the metrics reflect the task?
- Is variability reported where appropriate?
- Are improvements practically meaningful?
- Are failure cases investigated?

### Conclusions

- Do the findings support the central claim?
- Are alternative explanations considered?
- Do the conclusions extend beyond the tested setting?

**Medical imaging example:** Check whether multiple images from the same patient appear across training and test sets. An apparently strong score may be misleading if patient information leaks between splits.

## Step 6. Reproduce Selectively

Reproduction is especially useful when a paper is central to your project.

Start with a clearly defined target:

- A baseline result.
- A key table.
- An ablation.
- A specific behavior.

Record differences between the original setup and your implementation.

A mismatch does not immediately prove the paper is wrong. Investigate data, preprocessing, dependencies, hyperparameters, and evaluation first.

## Step 7. Reflect After Reading

Close the paper and answer:

- What did I learn?
- What evidence was convincing?
- What remains unclear?
- Which assumptions might fail?
- What would I investigate next?
- Does this change my research plan?

Distinguish three categories in your notes:

1. **Authors’ claims.**
2. **Your interpretation.**
3. **Findings you independently checked.**

## A Reusable Reading Note

Copy these prompts into your notes:

- **Paper:**
- **Authors and year:**
- **Source link:**
- **Research question:**
- **Why it matters:**
- **Closest previous work:**
- **Main idea:**
- **Method overview:**
- **Datasets and evaluation:**
- **Key findings:**
- **Strengths:**
- **Limitations:**
- **Unanswered questions:**
- **Relevance to my project:**
- **Next action:**

## Common Mistakes

- Reading every sentence with equal attention.
- Memorizing architecture details without understanding the question.
- Accepting motivation without examining evidence.
- Assuming an ablation establishes a causal mechanism.
- Treating the authors’ explanation as the only possible explanation.
- Finishing the paper without recording your own assessment.

## Before You Move On

- [ ] I can state the question and contribution.
- [ ] I understand the closest alternatives.
- [ ] I can explain the main method.
- [ ] I examined the evaluation design.
- [ ] I identified important limitations.
- [ ] I separated claims from interpretation.
- [ ] I recorded a useful next action.

---

## Source and Editorial Note

Adapted into English from **“如何读论文？”** in the [LAMDA-NeSy Research Starter Kit](https://github.com/LAMDA-NeSy/Research-Starter-Kit).

The original material is credited to **Guo Lanzhe and the LAMDA-NeSy team**. This adaptation includes additional explanations, examples, and checklists.

**English adaptation and editing:** Hussain Ahmad.

---

[← Previous: Finding Research Papers](02-finding-papers.md) · [Back to the handbook](../README.md) · [Next: Developing Research Ideas →](04-developing-ideas.md)
