# AI & Economics of Science Papers — 2026-08-15

## 1. Prestige over merit: An adapted audit of LLM bias in peer review [Peer Review & Publication]

**Authors:** Anthony Howell, Jieshu Wang, Luyu Du, Julia Melkers, Varshil Shah
**Date:** August 11, 2026 (originally posted September 18, 2025)
**Source:** https://arxiv.org/abs/2509.15122
**Summary:** The authors adapt a resume-style audit-study design to scholarly peer review, building a multi-role LLM simulation that plays editor and reviewer on identical manuscripts while randomizing the author's institutional prestige, gender, and race. Revealing author identity lowers rejection recommendations by roughly a quarter relative to blind review, with institutional prestige the dominant driver: low-prestige affiliations receive lower quality scores in every field tested, and female authors at low-prestige institutions fare worst of all. The authors trace the effect to prestige-linked priors baked into training data, including synthetic CVs the model generates that mirror real status hierarchies, and argue this is a caution against informal LLM use in review.

## 2. Co-leading Teams Drive Scientific Novelty in Large-scale Research Infrastructures [Econ of Science]

**Authors:** Mingze Zhang, Yizhan Li, Hao Peng, Zexia Li
**Date:** August 13, 2026
**Source:** https://arxiv.org/abs/2608.13195
**Summary:** Using machine-learning classification over 273,109 publications from 76 large-scale research infrastructures worldwide, the authors ask how staff scientists' role in visiting-user teams relates to the novelty of the resulting research. Papers where in-house staff formally co-lead rather than merely assist earn a clear novelty premium, which peaks when user and staff contributions are roughly balanced and then fades — a pattern the authors read as a form of epistemic lock-in. The ideal arrangement also shifts with experience: newcomers gain from any staff participation, while experienced users need staff to co-lead to keep generating novel work, a finding with direct implications for how facilities structure user-staff collaboration.

## 3. Patterns of Research Funding Across Research Subjects: The Case of NSERC [Econ of Science]

**Authors:** Rabeeh Parhizkari, Gita Ghiasi
**Date:** August 11, 2026
**Source:** https://arxiv.org/abs/2608.11484
**Summary:** This study tracks how Canada's NSERC has allocated research funding across subject areas over time, testing whether funding systems reinforce cumulative advantage in already-prominent fields. Pure sciences and mathematics subjects have generally seen declining funding shares, while social sciences and medical sciences — which started from a lower per-grant baseline — have gained ground. The authors frame the results as evidence for funders to weigh when designing allocation policies that aim to be both effective and equitable across disciplines.

## 4. Translation Readiness Index: Measuring the Semantic Proximity of Research to Patented Science [Econ of Science]

**Authors:** Paul X. McCarthy, Rasika Amarasiri, Xian Gong
**Date:** June 30, 2026 (updated August 11, 2026)
**Source:** https://arxiv.org/abs/2606.31102
**Summary:** The authors build a text-based metric, the Translation Readiness Index, that scores a paper's likely path toward patented, commercializable science using only its title and abstract, trained by contrasting patent-linked papers against comparable non-patent papers from the same journals. Patent-linked papers consistently use more action-oriented, invention-style language, letting the model distinguish them with reasonable accuracy (ROC-AUC 0.774), and higher scores independently correlate with industry co-authorship, inventors' patent histories, and university-industry collaboration rates. The tool is pitched as an early-stage screening aid for universities, funders, and investors trying to spot translational potential before licenses or startups materialize.

## 5. A Graph Approach to the Academic Publishing Network: A Heterogeneous Model and Structural Screening over OpenAlex Open Data [Peer Review & Publication]

**Authors:** Robert Šamárek, Radek Martinek
**Date:** August 11, 2026
**Source:** https://arxiv.org/abs/2608.10774
**Summary:** Moving beyond single-number metrics like the h-index or impact factor, the authors model the academic publishing ecosystem as a heterogeneous graph of works, authors, institutions, journals, and topics built on open OpenAlex data, then apply community detection and anomaly screening to surface irregular publishing patterns. Tested against a university's own citation network and against a second corpus with known ground truth (journals delisted by Scopus and DOAJ), a naive approach produced spurious signals driven by journal prominence, but after controlling for that confound, breadth of disciplinary scope emerged as a genuinely robust red flag, and a PageRank-style prestige measure proved far harder to game than simple citation counts. The authors release the method as an open-source, reproducible toolkit intended to flag candidates for human review rather than issue automated verdicts.
