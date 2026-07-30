# AI & Economics of Science Papers — 2026-07-31

## 1. Can AI agents conduct open-ended AI research? Early evidence from two case studies [AI for Science]

**Authors:** Peter Kirgis, Sayash Kapoor, Andrew Schwartz, Stephan Rabanser, David Africa, Konstantinos Voudouris, Viet Nguyen, Toby Pilditch, Magda Dubois, Harry Coppock, Cozmin Ududec, Nitya Nadgir, Matilda Orona, Tilman Bayer, Derrick Chan-Sew, Yue Ling, Abhishek Shetty, Helen Toner, Gillian Hadfield, Seth Lazar, Steve Newman, Shoshannah Tekofsky, Rishi Bommasani, Arvind Narayanan
**Date:** July 29, 2026
**Source:** https://arxiv.org/abs/2607.27191
**Summary:** The authors introduce "shadow evaluations": frontier AI agents are given six days and thousands of dollars of compute to tackle the central open-ended research question of an unpublished NeurIPS submission, and the paper's actual authors then grade the output — a design meant to escape both narrow verifiable benchmarks and the noisy, overloaded blind peer-review pipeline. Across two case studies, agents executed all the required engineering without human help but failed to make meaningful progress on the underlying research question, and both resulting papers were unambiguously rejected by their original authors. The authors trace the failures to five recurring problems — misjudging the bar for publishable work, uncreative responses to design flaws, poor backtracking from dead ends, weak resource awareness, and drifting from instructions — suggesting current agents can automate the engineering of AI research but not yet its judgment-driven core.

## 2. Bias at the Borderline: Who Gets the Benefit of the Doubt in Peer Review? [Peer Review & Publication]

**Authors:** Hazem Ibrahim, Talal Rahwan, Yasir Zaki
**Date:** July 28, 2026
**Source:** https://arxiv.org/abs/2607.26280
**Summary:** Using the complete public review record of ICLR 2019-2025 (31,711 submissions, 10,416 of them borderline), the authors test whether area chairs' discretionary accept/reject calls on tied-score papers favor authors from top-25 institutions, WEIRD countries, or all-male teams. They find borderline papers without a top-institution author are accepted 0.5-1.6 percentage points less often at identical reviewer scores, a gap that replicates out-of-sample in a pre-registered 2026 cohort and is concentrated almost entirely among submissions whose institutional identity leaked via a pre-decision arXiv preprint. A pre-registered battery of 27 outcome tests (citations, novelty, disruption, eventual publication venue) finds no evidence the disadvantaged group's papers were actually better — pointing to statistical discrimination based on revealed institutional prestige rather than area chairs correctly compensating for noisy scores, the exact failure mode double-blind review is meant to prevent.

## 3. The Ghost Couple: Correlated LLM Name Priors and Their Haunting of the Web and Academic Publishing [Peer Review & Publication]

**Authors:** Michał Brzozowski, Neo Christopher Chung
**Date:** June 1, 2026 (v1); revised July 29, 2026
**Source:** https://arxiv.org/abs/2606.02184
**Summary:** The authors show that when large language models invent fictional expert names, they don't just default to individually likely names but generate correlated, model-family-specific "ghost" ensembles (Claude consistently pairs "Elena Vasquez" with "Marcus Chen," Gemini with "Aris Thorne" and "Lena Petrova," and so on), with the pattern shifting at each model release in a way that leaves a dateable fingerprint. They trace a real-world consequence: on Zenodo, the CERN-operated repository that issues real DataCite DOIs, they identify 1,655 records ghost-authored by these fictional names, citing nonexistent journals with server timestamps proving deliberate backdating, all carrying legitimate DOIs that any citation-indexing scholarly database would ingest. The finding is a concrete, scalable channel by which AI-generated fabrication can contaminate the formal scholarly record — with ghost names also seeding synthetic "research groups" on ResearchGate — raising the cost of verifying authorship and provenance in AI-saturated publishing infrastructure.

## 4. The hidden structure of innovation networks [Econ of Science]

**Authors:** Lorenzo Emer, Anna Gallo, Mattia Marzi, Andrea Mina, Tiziano Squartini, Andrea Vandin
**Date:** January 15, 2026 (v1); revised July 29, 2026
**Source:** https://arxiv.org/abs/2601.10224
**Summary:** Using patent data in AI, biotechnology, and semiconductors, the authors map both inventor-level (co-inventorship) and organization-level (co-ownership) collaboration networks and compare a standard modularity-maximization clustering method against a Bayesian stochastic-block-model approach that can detect local hierarchies. They find inventor networks are denser and more tightly clustered around small recurring teams nested inside broader institutional structures, while organization networks show a cleaner role-based architecture in which a few bridging firms coordinate more peripheral ones, with both layers exhibiting local core-periphery structure. Citation-based innovation output is highly concentrated in a handful of the discovered clusters across every sector and method, and the Bayesian approach recovers this concentration more faithfully than modularity maximization — implying that standard network-clustering tools used in innovation-policy analysis may be missing the hierarchical structure that actually drives where inventive impact accumulates.

## 5. Statistical realism is not evidence that LLMs can estimate treatment effects in social science experiments [AI for Science]

**Authors:** Zonghan Li, Feng Ji
**Date:** April 2, 2026 (v1); revised July 27, 2026
**Source:** https://arxiv.org/abs/2604.02458
**Summary:** Researchers increasingly use LLMs to simulate human survey respondents and estimate treatment effects when real experiments are costly, typically validating these simulations by checking "statistical realism" — how closely simulated responses resemble real human response distributions. Testing this proxy directly across three cross-national experiments (up to 62 countries and tens of thousands of participants) and three LLMs, the authors find only a weak correlation between statistical realism and actual treatment-effect accuracy, and that optimizing model, prompt, or population choice for realism can make treatment-effect estimates worse rather than better. The divergence is largest for behavioral (as opposed to attitudinal) outcomes, where models appear to extrapolate behavior from attitude patterns, leading the authors to argue that realism and treatment-effect accuracy are distinct estimation targets that must be validated separately before LLM-simulated experiments are used to inform real research or policy decisions.
