# Finding Research Papers

> A good literature search helps you understand existing knowledge, identify unresolved questions, and choose a useful direction for your research.

## What You Should Achieve

By the end of your initial search, you should be able to identify:

- The main questions studied in your area.
- Representative and closely related papers.
- Common methods, datasets, and evaluation practices.
- Important limitations and disagreements.
- Questions that require further investigation.

Build a focused reading collection rather than an unmanageable archive.

## 1. Define Your Search Question

Begin with a specific question, even if it is preliminary.

**Broad interest:**

> Multimodal learning for healthcare.

**More focused question:**

> How do multimodal prediction models handle missing clinical or imaging inputs?

Break the question into searchable concepts:

| Concept | Example search terms |
| --- | --- |
| Task | prediction, classification, diagnosis |
| Method | multimodal learning, fusion |
| Limitation | missing modality, incomplete inputs |
| Application | healthcare, medical imaging |

Try synonyms and alternative terminology. Different research communities may describe similar problems differently.

## 2. Find a Few Seed Papers

A seed paper provides an entry point into the literature.

Useful seeds include:

- A well-organized survey.
- A foundational study.
- A paper closely matching your question.
- A widely used dataset or benchmark paper.
- A recommendation from your supervisor or an experienced researcher.

Start with a small collection. Understand its main ideas before expanding your search.

### Check Each Seed Paper

Ask:

1. Is it relevant to my question?
2. Does it explain the research background clearly?
3. Does it identify important related work?
4. Are its methods and evidence described sufficiently?
5. What should I read next because of it?

## 3. Follow Relevant Conferences and Journals

Identify where researchers in your area publish.

Examples of established AI conference communities include:

| Area | Examples |
| --- | --- |
| Machine learning | ICML, NeurIPS, ICLR |
| Natural language processing | ACL, EMNLP |
| Computer vision | CVPR, ICCV, ECCV |
| General artificial intelligence | AAAI, IJCAI |
| Data mining | KDD |

Your specific topic may require additional domain venues. Healthcare AI, for example, also draws on medical imaging, biomedical informatics, and clinical research.

Venue reputation can help you discover work, but assess each paper through its question, methods, and evidence.

## 4. Follow the Citation Network

A relevant paper connects you to both earlier and later research.

### Search Backward

Read its references to find:

- Foundational methods.
- Earlier definitions.
- Dataset descriptions.
- Closely related approaches.

### Search Forward

Find papers that cite it to discover:

- Extensions.
- Alternative methods.
- Reproductions.
- Critiques.
- Updated evaluations.

Record why each new paper matters. Avoid following references without a clear purpose.

## 5. Follow Researchers and Research Groups

When a paper is especially relevant, examine the authors’ broader work.

Useful sources include:

- Researcher and laboratory homepages.
- Google Scholar profiles.
- DBLP and Semantic Scholar.
- Project pages.
- Public code repositories.
- Research talks and presentations.

Following a group’s sequence of studies can reveal how a research question developed over time.

## 6. Search Through Datasets, Code, and Benchmarks

Research communities often organize around shared resources.

Explore:

- Dataset websites.
- Benchmark documentation.
- Evaluation leaderboards.
- Baseline implementations.
- Model repositories.
- Related repository issues and discussions.

### Read Leaderboards Carefully

Before comparing reported scores, check:

- Are the data splits identical?
- Is external training data used?
- Are supervision and annotation requirements comparable?
- Are metrics computed in the same way?
- Are computational resources substantially different?

Use leaderboard entries to discover papers, then examine the actual experimental conditions.

## 7. Keep a Search Log

A search log helps you revisit decisions and avoid repeating the same search.

| Field | What to record |
| --- | --- |
| Research question | What you want to understand |
| Search terms | Keywords and synonyms |
| Source | Database, proceedings, or repository |
| Search date | When you performed the search |
| Relevant papers | What you retained and why |
| Remaining questions | What the search has not resolved |

> This introductory workflow is not a complete systematic-review protocol. Formal reviews require an appropriate methodology.

## 8. Organize Your Reading Collection

Use a reference manager or another searchable system.

For each priority paper, retain:

- Bibliographic details.
- A stable source link or identifier.
- The research question.
- Its relevance to your project.
- Reading status.
- Your notes.

Useful tags include task, method, dataset, and evaluation setting.

Maintain two separate queues:

- **To scan:** potentially relevant papers.
- **To study:** papers requiring detailed reading.

## A Practical Search Exercise

1. Write your research question in one sentence.
2. Identify three or four searchable concepts.
3. Find one useful survey and several closely related studies.
4. Follow their references and citing papers.
5. Build a comparison table.
6. Record what remains unresolved.

| Paper | Question | Method | Data | Main limitation | Relevance |
| --- | --- | --- | --- | --- | --- |
| Paper A | | | | | |
| Paper B | | | | | |
| Paper C | | | | | |

## Common Mistakes

- Searching only one phrase or one source.
- Reading only recent work.
- Assuming citation count establishes quality.
- Collecting papers without recording their relevance.
- Treating generated summaries as substitutes for the original papers.
- Claiming a research gap before checking closely related studies.

## Before You Move On

- [ ] I have useful seed papers.
- [ ] I searched alternative terms.
- [ ] I explored references and citing papers.
- [ ] I identified relevant research groups.
- [ ] I examined important datasets and benchmarks.
- [ ] My priority papers are organized.
- [ ] I can explain what remains unclear.

---

## Source and Editorial Note

Adapted into English from **“如何找论文？”** in the [LAMDA-NeSy Research Starter Kit](https://github.com/LAMDA-NeSy/Research-Starter-Kit).

The original material is credited to **Guo Lanzhe and the LAMDA-NeSy team**. This adaptation includes additional explanations, examples, and checklists.

**English adaptation and editing:** Hussain Ahmad.

---

[← Previous: Understanding Research](01-understanding-research.md) · [Back to the handbook](../README.md) · [Next: Reading Papers Critically →](03-reading-papers.md)
