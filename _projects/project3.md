---
title: "CryptoLLM - Large Language Models for Cryptography Assistance 🛡️🔐🔑"
date: 2024-05-17
tags: [LLM, cryptography, fine tuning]
layout: projects_page
link_code: "https://github.com/ReboreExplore/cryptographic_llm"
---

Real-life mathematical problems require a combination of natural language understanding, logical thinking, and computational skills. Cryptography is one such complicated field of computer science that requires a good blend of natural understanding and mathematical reasoning skills. Current tools for solving such problems are limited in their ability to either understand and interpret only natural language or only excel in mathematical computations if inputted in a specific format. Large Language Models (LLMs) have shown great promise in solving a wide range of problems by understanding and generating human-like text. However, the currently popular LLMs like GPT-3.5, llama series etc., show suboptimal performance in solving mathematical problems. It is mostly due to the lack of specialized training data and the design of arithmetic problems which has a single correct answer with multistep reasoning. In this project, we design a LLM-based assistant for cryptography problems. We also propose a novel crypto dataset, CryptoQA which is curated from popular academic textbooks and resources and is publicly available. Four versions of finetuned models (CryptoLLMs) are also trained for solving cryptographic problems. The first two models are fine-tuned on an already math-tuned and a general-purpose LLM respectively using the CryptoQA dataset. The other two versions are fine-tuned in two stages - first on a publicly available math dataset and then on the CryptoQA dataset. A qualitative behavioral analysis of the fine-tuned models is conducted and is made publicly available for experimentation and research.

Key features include:
- CryptoQA dataset for cryptography problems
- CryptoLLM models for solving cryptography problems
- Fine-tuning and evaluation of LLMs for cryptography
- Qualitative behavioral analysis of the models