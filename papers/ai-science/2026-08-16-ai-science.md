# AI & Economics of Science Papers — 2026-08-16

## 1. Prestige over merit: An adapted audit of LLM bias in peer review [Peer Review & Publication]

**Authors:** Anthony Howell, Jieshu Wang, Luyu Du, Julia Melkers, Varshil Shah
**Date:** Originally posted September 18, 2025; revised (v2) August 11, 2026
**Source:** https://arxiv.org/abs/2509.15122
**Summary:** The authors adapt a resume-style correspondence audit to peer review, building a multi-role LLM simulation that acts as editor and reviewer on high-quality manuscripts across the physical, biological, and social sciences while randomizing the disclosed author identity. Revealing author identity lowers rejection recommendations by about a quarter relative to the baseline rate despite unchanged content, and institutional prestige turns out to be the dominant driver, penalizing low-prestige affiliations in every field studied — with female authors at low-prestige institutions faring worst of all. Synthetic CVs generated for the same profiles show large prestige-linked disparities baked into the models, suggesting the bias stems from status priors embedded in training data rather than genuine quality differences.

## 2. Co-leading Teams Drive Scientific Novelty in Large-scale Research Infrastructures [Econ of Science]

**Authors:** Mingze Zhang, Yizhan Li, Hao Peng, Zexia Li
**Date:** August 13, 2026
**Source:** https://arxiv.org/abs/2608.13195
**Summary:** Analyzing 273,109 publications from 76 large-scale research infrastructures worldwide, the authors use a machine-learning classifier to sort papers by how staff scientists are integrated into external user teams: absent, participating, or co-leading. Teams where staff scientists formally co-lead — rather than merely participate — produce a clear novelty premium over user-only teams, and that premium peaks when user and staff contributions are roughly balanced rather than lopsided. The ideal arrangement also shifts with experience: newcomer teams gain the most from staff participation alone, while experienced users need staff to co-lead in order to keep generating novel work, a pattern with direct implications for how big science facilities structure collaborations.

## 3. Patterns of Research Funding Across Research Subjects: The Case of NSERC [Econ of Science]

**Authors:** Rabeeh Parhizkari, Gita Ghiasi
**Date:** August 11, 2026
**Source:** https://arxiv.org/abs/2608.11484
**Summary:** Using Canada's NSERC funding data, the authors track how research funding has shifted across subject areas within the natural sciences and engineering over time. They find that many pure-science and mathematics subfields have seen funding decline in recent years, while social science and medical science areas — which started from a lower base of funding per grant — have seen steady increases. The authors frame this as evidence that funding allocation can reinforce cumulative advantage for some fields while reshuffling priority toward others, with implications for how funding agencies should design more equitable allocation policies.

## 4. Translation Readiness Index: Measuring the Semantic Proximity of Research to Patented Science [Science Policy]

**Authors:** Paul X. McCarthy, Rasika Amarasiri, Xian Gong
**Date:** Originally posted June 30, 2026; revised (v2) August 11, 2026
**Source:** https://arxiv.org/abs/2606.31102
**Summary:** The authors build a text-based "Translation Readiness Index" that predicts how likely a paper is to lead to a patent, using only its title and abstract and training on over 20,000 papers matched against patents for the same invention. They find that patent-linked papers consistently use action-oriented, invention-style language versus the more observational framing of non-patent papers, letting the model distinguish the two with strong accuracy (ROC-AUC 0.77). At the institutional level, the index correlates significantly with real university-industry collaboration, positioning it as an early-stage screening tool that funders and technology-transfer offices could use to flag promising research well before patents or licenses materialize.

## 5. Auditable AI-Assisted Research Writing: An Engineering Discipline with Pre-Registered Process Observation [AI for Science]

**Authors:** Yang Zhou, Chengqun Yu
**Date:** August 11, 2026
**Source:** https://arxiv.org/abs/2608.10858
**Summary:** Rather than trying to detect AI involvement in a paper after the fact, the authors propose an engineering discipline for making AI-assisted research auditable while it happens — combining version-control "sealing" with tamper-evident lineage, provenance tracking, automated compliance gates that log every refusal, and separation of roles across different models. They pre-register metric cards ahead of time to instrument adherence, then apply the framework prospectively to a live research project, where its own pre-registered stopping rule triggered a halt after a confirmatory test returned "No-Go." The authors release the underlying package so third parties can independently recompute every reported metric, positioning this as an early template for accountable AI-assisted research rather than a finished standard.
