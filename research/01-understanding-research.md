# Understanding Research

> Research begins with a meaningful question and develops through systematic investigation, critical thinking, and credible evidence.

## What Is Research?

Research is a systematic process of investigating questions, developing explanations, and producing knowledge that others can examine, test, and build upon.

In artificial intelligence, research may involve:

- Discovering a new phenomenon.
- Explaining how or why a model works.
- Developing a method that addresses an existing limitation.
- Creating a useful dataset or evaluation benchmark.
- Investigating an important real-world application.

The goal is to make a contribution supported by reliable evidence.

## What Makes a Research Contribution Valuable?

A valuable contribution helps others understand something more clearly or accomplish something previously difficult.

| Contribution | What it provides |
| --- | --- |
| A meaningful problem | An important question or limitation that deserves investigation |
| A new method | A justified approach to a research challenge |
| A clearer explanation | Evidence about how or why a phenomenon occurs |
| A useful resource | A dataset, benchmark, protocol, or tool |
| A rigorous evaluation | Evidence showing when an existing claim holds or fails |

A small improvement can be valuable when it addresses a meaningful limitation and is supported by convincing evidence.

Adding complexity, combining popular techniques, or improving a single score does not automatically establish a strong contribution.

### Questions to Ask

1. What does this work help us understand or accomplish?
2. How does it differ from the closest existing work?
3. Why does that difference matter?
4. What evidence supports the contribution?
5. Under what conditions is it useful?
6. What limitations remain?

## The Responsibilities of a Research Student

Research training extends beyond implementing models and writing papers.

Your responsibilities include:

- **Understanding the literature:** Learn what is already known and identify unresolved questions.
- **Formulating research questions:** Turn broad interests into specific, testable problems.
- **Designing investigations:** Select appropriate methods, datasets, baselines, and evaluation criteria.
- **Developing technical skills:** Build the knowledge needed to implement and analyze your work.
- **Interpreting results:** Investigate successes, failures, and unexpected outcomes.
- **Communicating clearly:** Explain your reasoning through meetings, presentations, and writing.
- **Collaborating responsibly:** Share knowledge, follow through on commitments, and acknowledge contributions.
- **Working ethically:** Follow relevant requirements for data access, privacy, consent, and research integrity.

These abilities develop gradually through practice and feedback.

## Skills That Support Good Research

### Curiosity

Ask why a result occurs, which assumptions support it, and what remains unexplained.

### Critical Thinking

Examine claims, methods, and evidence before accepting a conclusion.

### Independent Judgment

Develop your own interpretation while remaining open to correction.

### Persistence

Expect uncertainty and setbacks. Use them to decide what to investigate next.

### Communication

Explain the problem, reasoning, evidence, and limitations in language your audience can understand.

### Initiative

Bring questions, possible explanations, and proposed next steps to discussions.

## The Research Process

A useful starting sequence is:

**Topic → Problem → Idea → Investigation → Interpretation → Paper**

This process is iterative. Reading may change your question, experiments may challenge your hypothesis, and writing may reveal missing evidence.

### 1. Choose a Topic

A topic is a broad area of interest.

Examples include:

- Multimodal learning.
- Medical image segmentation.
- Natural language processing.
- Energy management.
- Explainable artificial intelligence.

Begin by understanding the terminology, representative studies, common datasets, and evaluation practices.

**Your first task:** Read a small set of relevant papers and summarize the main questions being studied.

### 2. Identify a Specific Problem

A problem is a clearly defined unresolved issue within your topic.

| Broad topic | More specific research problem |
| --- | --- |
| Multimodal learning | Prediction performance deteriorates when one input modality is missing |
| Medical image segmentation | Small lesions are frequently missed despite good overall segmentation scores |
| Natural language processing | A model struggles with entities in a low-resource language |
| Energy management | A scheduling strategy performs poorly when demand forecasts are inaccurate |

A useful research problem should be important enough to investigate and narrow enough to study with the available resources.

**Your first task:** Write the problem in one or two sentences and identify the closest existing approaches.

### 3. Develop an Idea

An idea is a proposed explanation or solution.

State both what you propose and why it might work.

**Illustrative hypothesis:**

> Training a multimodal model with intentionally missing inputs may improve robustness because the model learns to make predictions from different combinations of available information.

This statement is a hypothesis to test. It should not be presented as an established result.

**Your first task:** Explain the proposed mechanism and identify an observation that would challenge it.

### 4. Design an Investigation

Choose experiments or analyses that can support or challenge your hypothesis.

Consider:

- Suitable datasets and data quality.
- Appropriate training, validation, and test splits.
- Relevant and fairly tuned baselines.
- Metrics that reflect the research question.
- Controlled comparisons and ablation studies.
- Repeated runs and uncertainty, where appropriate.
- Computational cost and resource requirements.
- Reproducibility.

**Your first task:** Design the smallest useful experiment that tests the central assumption.

### 5. Interpret the Evidence

Go beyond the headline result.

Ask:

- When does the approach work?
- When does it fail?
- Which component contributes to the outcome?
- Could another explanation account for the improvement?
- Are the comparisons fair?
- What remains uncertain?

A negative result can still improve understanding when the investigation is well designed.

**Your first task:** Separate what the results demonstrate from what you suspect but have not yet established.

### 6. Communicate the Findings

A paper should explain:

1. The question being investigated.
2. Why the question matters.
3. What existing work leaves unresolved.
4. The proposed approach.
5. The supporting evidence.
6. The limitations and implications.

Begin writing notes early. Writing can help clarify the research before the experiments are complete.

**Your first task:** Draft a short explanation connecting the problem, hypothesis, method, and evidence.

## A Practical Starting Template

Use these prompts to clarify a new project:

| Prompt | Your response |
| --- | --- |
| My broad research topic is… | |
| The specific problem is… | |
| This problem matters because… | |
| The closest existing approaches are… | |
| Their relevant limitation is… | |
| My hypothesis is… | |
| The smallest useful test is… | |
| Evidence against my hypothesis would be… | |
| The main practical constraints are… | |

## Common Mistakes

- Choosing a method before defining a worthwhile problem.
- Claiming a research gap without examining the closest literature.
- Treating a higher benchmark score as a complete explanation.
- Adding components without explaining why they are necessary.
- Ignoring findings that contradict the preferred hypothesis.
- Confusing a working implementation with a demonstrated contribution.
- Making claims that extend beyond the tested conditions.

## Before You Move On

- [ ] I can describe my broad research topic.
- [ ] I can state a specific research question.
- [ ] I understand the closest existing approaches.
- [ ] I can explain why the question matters.
- [ ] I have a plausible hypothesis.
- [ ] I have identified evidence that could challenge it.
- [ ] I have a feasible first investigation.
- [ ] I can describe the limits of my current knowledge.

---

## Source and Editorial Note

Adapted into English from **“如何做科研？”** in the [LAMDA-NeSy Research Starter Kit](https://github.com/LAMDA-NeSy/Research-Starter-Kit).

The original material is credited to **Guo Lanzhe and the LAMDA-NeSy team**. This English adaptation was refined from the supplied screenshots, with additional explanations, illustrative examples, and checklists.

**English adaptation and editing:** Hussain Ahmad.

---

[← Back to the handbook](../README.md) · [Next: Finding Research Papers →](02-finding-papers.md)
