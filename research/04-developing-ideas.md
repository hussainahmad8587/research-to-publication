# Developing Research Ideas

> A strong research idea connects a worthwhile question with a plausible approach and a clear way to evaluate it.

## Where Research Ideas Come From

Ideas develop through reading, observation, discussion, implementation, and experimentation.

Two common starting points are:

| Starting point | Main question |
| --- | --- |
| Problem-driven research | What important limitation should we address? |
| Method-driven research | Where could this technique provide useful insight or capability? |

Both can produce valuable research. In either case, explain the problem, the reasoning behind the approach, and what the investigation will establish.

## 1. Read With Questions in Mind

While reading, ask:

- Which assumptions support this method?
- What cases are excluded?
- What happens when the setting changes?
- Which claims are weakly supported?
- Could a simpler approach achieve a similar result?

Combine literature reading with question generation.

Record uncertainties while they are fresh.

## 2. Investigate Failure Cases

Average performance can hide important weaknesses.

For example:

> A multimodal model performs well overall but struggles when one input is missing or unreliable.

Before proposing a solution:

1. Verify that the failure is reproducible.
2. Identify the conditions under which it occurs.
3. Check data and implementation issues.
4. Compare possible explanations.
5. Design a targeted test.

A clearly understood failure often provides a stronger starting point than an unexplained score improvement.

## 3. Ask Why a Successful Method Works

Useful research can begin with an existing success.

Ask:

- Which component contributes most?
- Does the improvement depend on a particular dataset?
- Could training choices explain the result?
- Does the proposed explanation hold under controlled tests?

Design experiments that distinguish competing explanations.

## 4. Examine Contradictory Findings

Two papers may report different conclusions about similar approaches.

Investigate differences in:

- Dataset composition.
- Data preprocessing.
- Baseline strength.
- Training budgets.
- Evaluation metrics.
- Definitions and assumptions.
- Implementation details.

Resolving a disagreement can produce valuable knowledge without introducing a more complicated model.

## 5. Work Backward From Practical Needs

Applications reveal constraints that benchmarks may overlook.

Examples include:

- Limited annotations.
- Missing measurements.
- Restricted computing resources.
- Changing operating conditions.
- Requirements for interpretability.
- Differences between development and deployment data.

Translate a practical difficulty into a question that can be investigated systematically.

**Illustrative question:**

> Can a model retain useful performance when an expensive input measurement is unavailable?

## Is the Question Worth Investigating?

| Criterion | Questions to ask |
| --- | --- |
| Importance | Who benefits from answering it? |
| Originality | What remains unresolved in the closest literature? |
| Clarity | Can the question be stated precisely? |
| Feasibility | Do we have the necessary data, skills, and resources? |
| Testability | What evidence could support or challenge the idea? |
| Scope | Can we complete a useful investigation within the available time? |

Discuss these judgments with your supervisor or collaborators.

Enthusiasm is useful, but it should be supported by a realistic investigation plan.

## Turn the Question Into a Hypothesis

A hypothesis states an expected relationship and, where possible, the reasoning behind it.

**Weak formulation:**

> We will combine two models to improve performance.

**More informative formulation:**

> We hypothesize that explicitly modeling unreliable inputs will improve robustness because the fusion mechanism can reduce reliance on misleading information.

The second formulation identifies something that can be tested.

## Choose a Solution Strategy

Possible strategies include:

- **Transfer:** Adapt a relevant principle from another setting.
- **Integration:** Combine complementary approaches with a clear technical rationale.
- **Reformulation:** Change the task, objective, or representation.
- **Analysis:** Investigate an existing phenomenon through controlled experiments or theory.

A combination is meaningful when its interaction is justified and evaluated.

## Design the Smallest Useful Experiment

Your first experiment should test the central assumption.

Specify:

1. The hypothesis.
2. A suitable dataset or experimental setting.
3. A meaningful baseline.
4. The variable being changed.
5. Evaluation criteria.
6. Possible alternative explanations.
7. Criteria for continuing, revising, or stopping.

Avoid building the full system before establishing whether its foundation is promising.

## A One-Page Idea Brief

- **Working title:**
- **Research problem:**
- **Why it matters:**
- **Closest existing work:**
- **What remains unresolved:**
- **Hypothesis:**
- **Proposed approach:**
- **Why it might work:**
- **Smallest useful experiment:**
- **Baselines:**
- **Evaluation criteria:**
- **Resources required:**
- **Main risks:**
- **Alternative explanations:**
- **Decision after the first experiment:**

## Using AI for Brainstorming

AI tools can help generate alternatives, clarify assumptions, or suggest questions.

Independently verify:

- References.
- Claims about novelty.
- Technical explanations.
- Dataset suitability.
- Proposed experimental conclusions.

You remain responsible for the research judgment.

## Common Mistakes

- Treating “apply method X to task Y” as a complete contribution.
- Claiming a gap before examining the closest work.
- Adding complexity without a clear hypothesis.
- Changing several factors simultaneously.
- Ignoring evidence against the idea.
- Continuing without a decision point.

## Before You Move On

- [ ] The question is specific and meaningful.
- [ ] I examined closely related work.
- [ ] I can state a testable hypothesis.
- [ ] I have a feasible first experiment.
- [ ] I know what would challenge my hypothesis.
- [ ] I considered alternative explanations.
- [ ] I discussed the scope and risks.

---

## Source and Editorial Note

Adapted into English from **“如何想Idea？”** in the [LAMDA-NeSy Research Starter Kit](https://github.com/LAMDA-NeSy/Research-Starter-Kit).

The original material is credited to **Guo Lanzhe and the LAMDA-NeSy team**. This adaptation includes additional explanations, examples, and checklists.

**English adaptation and editing:** Hussain Ahmad.

---

[← Previous: Reading Papers Critically](03-reading-papers.md) · [Back to the handbook](../README.md) · [Next: Presenting Your Research →](05-presenting-research.md)
