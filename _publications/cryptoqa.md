---
sort_key: 3
title: "CryptoQA: A Large-scale Question-answering Dataset for AI-assisted Cryptography"
authors: "M. Elfares, P. Reisert, T. Dietz, <strong>M. Barman</strong>, A. Zaki, R. Küsters, A. Bulling"
venue: "arXiv preprint arXiv:2512.02625"
year: 2025
links:
  arxiv: "https://arxiv.org/abs/2512.02625"
  code: "https://github.com/ReboreExplore/cryptographic_llm"
affiliations:
  - "Universität Stuttgart"
  - "Collaborative Artificial Intelligence Group"
keywords:
  - "LLM fine-tuning"
  - "cryptography"
  - "question answering"
  - "dataset curation"
description: |
  Built an LLM-based assistant for cryptography problems, which need a blend of natural-language
  understanding and multistep mathematical reasoning that general-purpose LLMs handle poorly.
  Curated CryptoQA, a dataset drawn from academic textbooks and resources, and fine-tuned four
  CryptoLLM variants — starting from both a math-tuned and a general-purpose base model, with
  single-stage and two-stage (math dataset, then CryptoQA) fine-tuning — then ran a qualitative
  behavioural analysis of base vs. fine-tuned models.

  - CryptoQA: a public dataset of cryptography questions
  - Four fine-tuned CryptoLLM model variants
  - Two-stage fine-tuning recipe (general math → cryptography)
  - Qualitative analysis of base vs. fine-tuned reasoning behaviour
---
