# AI & Economics of Science Papers — 2026-07-29

## 1. Generative Artificial Intelligence in Scientific Research: Individual Benefits, Collective Risks, and a Framework for Responsible Research with AI [Econ of Science]

**Authors:** Fulvio Castellacci, Tommaso Ciarli, Yuan Gao, Marianna Marino, Giacomo Marzi, Massimo Riccaboni, Maria Savona, Simone Vannuccini
**Date:** July 27, 2026
**Source:** https://arxiv.org/abs/2607.24879
**Summary:** Drawing on an academic roundtable and a fast-growing empirical literature, the authors map how generative AI is reshaping four stages of the research process — funding, task execution, publication and peer review, and downstream use — and find that while AI clearly raises publication volume and citation share, its effect on genuine novelty and breakthrough output is ambiguous or negative. They argue the widening gap between the private returns individual researchers capture and the social returns to the field stems from three distinct mechanisms: information asymmetry, externalities on the shared knowledge base, and depletion of research capacity. To address this they propose "Responsible Research with AI," a four-principle governance framework (disclosure, differentiation, narrative, proportionality) intended to preserve AI's productivity gains while containing systemic risks no individual researcher can manage alone.

## 2. Preprints Without Curation Are Increasingly Cited by Journals [Peer Review & Publication]

**Authors:** Chiaki Miura, Ichiro Sakata
**Date:** July 28, 2026
**Source:** https://arxiv.org/abs/2607.25220
**Summary:** Using citation metadata linking six major preprint servers to a large bibliographic database, the authors show that journal articles increasingly cite preprints directly rather than the peer-reviewed version that later supersedes them, with this behavior growing exponentially since the mid-2010s and peaking at nearly one in five journal articles citing at least one preprint in 2021. The growth cannot be explained by the larger stock of preprints, faster publication cycles, or a handful of outlier highly-cited preprints, and — contrary to expectation — the COVID-19 pandemic coincided with a slowdown rather than an acceleration of the trend. The finding points to a structural shift in scholarly norms, with preprints increasingly treated as legitimate, citable objects independent of formal peer review, raising questions for journals and indexers about how citation policy should adapt.

## 3. Autonomous Scientific Discovery via Iterative Meta-Reflection [AI for Science]

**Authors:** Bingchen Zhao, Sara Beery, Oisin Mac Aodha
**Date:** July 1, 2026
**Source:** https://arxiv.org/abs/2607.01131
**Summary:** The authors present DiscoPER, an LLM-driven agent that conducts open-ended empirical research on a dataset by iteratively writing and executing its own analysis code, rather than pursuing a human-specified research question, with every proposed finding required to pass a statistical test before being accepted. A "meta-reflection" step periodically has the agent review the pattern of findings it has accumulated so far and use that assessment to redirect subsequent exploration into unexamined parts of the search space; on a new multimodal ecological benchmark it recovers 8 of 9 known patterns, outperforming classical causal-discovery and other LLM-guided baselines. The work pushes toward autonomous research-production systems that select their own lines of inquiry, which bears on the economics of science as questions of credit, verification, and research-agenda-setting increasingly involve delegating discovery itself to an algorithm.

## 4. Is ChatGPT as reliable as individual reviewers assessing the quality of published journal articles from PDFs or titles and abstracts? [Peer Review & Publication]

**Authors:** Mike Thelwall, Parveen Ali
**Date:** July 28, 2026
**Source:** https://arxiv.org/abs/2607.25965
**Summary:** The authors benchmark ChatGPT-5.4 against human expert reviewers on scoring the research quality of published journal articles, using several hundred UK departmental quality ratings across three subject panels (allied health, architecture, and library/information science) as ground truth. ChatGPT's scores correlate with expert judgments about as well as individual reviewers correlate with each other, and in one panel the model's agreement with experts was, if anything, slightly higher than reviewers' agreement with one another, though the difference was not statistically significant. Feeding ChatGPT full PDFs rather than just titles and abstracts produced more detailed commentary but no more accurate quality scores, suggesting its apparent depth of reading does not translate into better assessment.

## 5. A genetic algorithm for peer-review panel composition [Peer Review & Publication]

**Authors:** Ferdinando Patat
**Date:** July 14, 2026
**Source:** https://arxiv.org/abs/2607.12757
**Summary:** The author formulates the assignment of expert reviewers to proposal-review panels as a constrained combinatorial optimization problem, balancing each panel's scientific-expertise coverage against demographic diversity across a finite pool of available reviewers. Applying a genetic algorithm to real panel-formation data from the European Southern Observatory's telescope-time proposal process, the method produces panel configurations with substantially lower imbalance than random or ad hoc assignment, with solution quality improving steadily across generations. The paper offers observatories and funding agencies a practical, automatable tool for a task — peer-review panel composition — that shapes how scientific attention and resources get allocated but is rarely optimized systematically.

---

**Note:** This digest supersedes an earlier version written this cycle before arXiv's export API became reachable; with API access restored, the harvest was re-run as specified in Step 2 and turned up three additional qualifying candidates beyond the original two, all now included above. Candidates found but excluded as out of scope or too thin: "An index to quantify scientific debt" (arXiv 2607.23011, a single-paragraph proposal with no empirical validation), a bibliometric-platform classification comparison (arXiv 2607.25499), an LLM-based bibliometrics framework proposal (arXiv 2607.21327), and a study of LLM validation of contested pseudo-scientific claims (arXiv 2607.22513), which falls outside this digest's economics-of-science scope.
