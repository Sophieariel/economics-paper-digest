# AI & Economics of Science Papers — 2026-08-14

## 1. Prestige over merit: An adapted audit of LLM bias in peer review [Peer Review & Publication]

**Authors:** Anthony Howell, Jieshu Wang, Luyu Du, Julia Melkers, Varshil Shah
**Date:** September 18, 2025 (v1); revised August 11, 2026
**Source:** https://arxiv.org/abs/2509.15122
**Summary:** The authors adapt a resume-style audit-study design to scholarly peer review, building a multi-role LLM simulation (editor/reviewer) that evaluates identical manuscripts under randomized author identities across the physical, biological, and social sciences. Revealing author identity lowers rejection recommendations by roughly 25% relative to blind review despite unchanged content, with institutional prestige the dominant driver — low-prestige affiliations receive lower quality scores in every field, and the penalty compounds for women at low-prestige institutions. Synthetic-CV probes suggest the bias traces to prestige-linked priors embedded in training data, a caution against informal LLM use in review pipelines.

## 2. BibTeX Citation Errors in Scientific Publishing Agents: Evaluation and Mitigation [AI for Science]

**Authors:** Delip Rao, Chris Callison-Burch
**Date:** April 3, 2026 (v1); revised August 8, 2026
**Source:** https://arxiv.org/abs/2604.03159
**Summary:** The authors benchmark three frontier search-enabled LLMs (GPT-5, Claude Sonnet-4.6, Gemini-3 Flash) on generating BibTeX citations for 931 papers, finding that only about half of entries are fully correct despite roughly 84% average field-level accuracy, with accuracy dropping sharply for papers published after each model's training cutoff. They identify two dominant failure modes — wholesale entry substitution and isolated field corruption — showing that even search-augmented agents lean heavily on unreliable parametric memory rather than verified retrieval. Their proposed fix, a two-stage pipeline that separates search from revision (released as the open-source tool clibib), raises fully-correct entries to 78%, indicating that integration architecture matters as much as raw model capability for trustworthy AI-assisted scholarly writing.

## 3. Patterns of Research Funding Across Research Subjects: The Case of NSERC [Econ of Science]

**Authors:** Rabeeh Parhizkari, Gita Ghiasi
**Date:** August 11, 2026
**Source:** https://arxiv.org/abs/2608.11484
**Summary:** Using Canada's NSERC grant records, the authors track how research funding has shifted across natural-science and engineering subfields, testing whether funders' pursuit of scientific output reinforces cumulative advantage toward already-prominent fields. They find funding has stagnated or declined for many pure-science and mathematics subjects, while social-science and medical-science areas — which started from a lower per-grant baseline — have seen rising funding over time. The results give funding agencies a subject-level view of where allocation is drifting, informing tradeoffs between efficiency and equity in science-budget design.

## 4. Translation Readiness Index: Measuring the Semantic Proximity of Research to Patented Science [Econ of Science]

**Authors:** Paul X. McCarthy, Rasika Amarasiri, Xian Gong
**Date:** June 30, 2026 (v1); revised August 11, 2026
**Source:** https://arxiv.org/abs/2606.31102
**Summary:** The authors build a text-based "Translation Readiness Index" that scores a paper's likelihood of leading to a patent using only its title and abstract, training embeddings on over 20,000 papers that contrast patent-linked work against comparable non-patent papers from the same journals. Patent-linked papers consistently use more action-oriented "language of invention," and the resulting score (ROC-AUC 0.77) correlates with real translational signals such as industry co-authorship, authors' patent histories, and university-level industry collaboration intensity. The tool offers funders, universities, and investors a cheap early-stage screen for commercially promising research well before licenses, startups, or patents materialize.

## 5. A Semantic Geometry for Uncovering Paradigm Dynamics via Scientific Publications [Econ of Science]

**Authors:** Jinchang Liu, Qingshan Zhou, Hongkan Chen, Yi Bu
**Date:** April 16, 2026 (v1); revised August 10, 2026
**Source:** https://arxiv.org/abs/2604.15150
**Summary:** The authors propose a geometric framework that measures how far a paper sits, in semantic space, from both the literature it draws on and the literature that later cites it, classifying papers as consolidating, exploratory, or balanced. This semantic-distance measure explains divergent citation dynamics: consolidating work accumulates citations quickly because it lowers comprehension costs, while exploratory work diffuses slowly due to higher "paradigm conversion costs," and small teams are more likely to produce exploratory departures while large teams gravitate toward consolidation. The framework offers a scalable, text-based way to monitor how scientific fields change direction over time.
