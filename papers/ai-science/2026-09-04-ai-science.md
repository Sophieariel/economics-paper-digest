# AI & Economics of Science Papers — 2026-09-04

## 1. Guiding LLM Peer Reviewers: The Impact of Score Anchors on Review Evidence and Accuracy [Peer Review & Publication]

**Authors:** Judita Preiss, Yunhan Yang
**Date:** September 1, 2026
**Source:** https://arxiv.org/abs/2609.01905
**Summary:** Using 98 REF-style research outputs with expert human reference scores, the authors test what happens when an LLM reviewer is given an "oracle" score to anchor its review, comparing the evidence it cites against a no-guidance baseline. They find that supplying the correct score improves scoring accuracy without the model simply parroting the number back, but the anchor also reshapes the review's rationale — models incorporate human-identified strengths more readily than human-identified weaknesses. The asymmetry suggests LLM-assisted evaluation is not neutral scaffolding: how reviewers are guided changes which evidence surfaces, with implications for how such tools should be audited before use in research assessment.

## 2. Beyond Human-Likeness: Mapping the Scientific Critique Profiles of LLMs and Human Reviewers [Peer Review & Publication]

**Authors:** Yunhan Yang, Mike Thelwall, Guoxiu He
**Date:** September 1, 2026
**Source:** https://arxiv.org/abs/2609.01895
**Summary:** Rather than asking whether LLM peer reviews sound human, the authors annotate ICLR 2025 human and LLM-generated reviews with five argumentation and cognitive-complexity frameworks to compare what critique functions each actually performs. Human reviewers focus more on scientific framing and revision guidance and raise higher-order weaknesses, while LLM reviews show more explanatory depth and formal argument structure; prompting the model to act like an expert narrows some gaps but mostly amplifies its existing tendencies rather than making it human-like. The findings argue for treating LLM review as a functionally distinct complement to human judgment rather than a substitute, since the two produce systematically different kinds of critique.

## 3. Citing Less Critically: LLMs Reshape the Rhetoric and Reach of Scientific Citation [Peer Review & Publication]

**Authors:** Yixuan Liu, Lin Chen, Zhuoqi Liu, Jianglin Lu, Dakota Murray
**Date:** September 1, 2026
**Source:** https://arxiv.org/abs/2609.01432
**Summary:** Using a masked-citation task across six LLMs and over 1,700 top NLP papers, the authors generate counterfactual citation sentences and compare them to what human authors actually wrote, classifying rhetorical intent and measuring social distance via a 20-million-edge coauthorship network. They find LLMs cite prior work less critically than humans, disproportionately favor older and already-popular papers even when drawing contrasts, and lean more on socially distant authors rather than close collaborators. As LLMs become embedded in scientific writing, the authors argue these patterns could gradually flatten critical engagement while amplifying existing visibility biases in the literature.

## 4. Tracing high-profile attention to questionable research as a case for funder due diligence [Science Policy]

**Authors:** Federica Silvi, Leslie D. McIntosh
**Date:** August 31, 2026
**Source:** https://arxiv.org/abs/2608.30613
**Summary:** Starting from a known "authorship-for-sale" paper-mill network exposed in 2022, the authors trace nearly 2,000 associated publications forward into policy documents, clinical guidelines, and patents, and follow the funding and publishing careers of 278 implicated authors. They find dozens of these papers still shape policy and clinical guidance and hundreds are cited in patents, while a quarter of the papers link to grants — and more than 90% of the authors kept publishing, with almost a quarter still winning grants, well after the exposure became public. The authors argue funders should weight authorship and network structure, not just citation and attention metrics, when deciding who to fund.

## 5. Do Large Language Models Favour Any Research Topics? [Econ of Science]

**Authors:** Mike Thelwall
**Date:** August 31, 2026
**Source:** https://arxiv.org/abs/2609.00323
**Summary:** Testing whether LLMs used to estimate journal-article quality carry topical biases, the author scores 73,489 health and life-sciences articles with two open LLMs and compares the words associated with high- and low-scoring papers. GPT-OSS-120B favors articles about viruses, genes, and cells and disfavors surveys, patients, and students, while Gemma 3 27B rates machine-learning research more favorably — a divergence that itself proves at least one model carries topic-level bias — and scores also shift depending on whether the model sees titles/abstracts or full text. The result is a caution against using LLM scores as a stand-in for peer judgment in research evaluation without first checking for these biases.
