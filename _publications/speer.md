---
title: "SPEER: Sentence-Level Planning of Long Clinical Summaries via Embedded Entity Retrieval"
collection: publications
excerpt: "We fine-tune opensource LLMs (Mistral-7B-Instruct and Zephyr-7B-β) on the task and find that they generate incomplete and unfaithful summaries. To increase entity coverage, we train a smaller, encoder-only model to predict salient entities, which are treated as content-plans to guide the LLM. To encourage the LLM to focus on specific mentions in the source notes, we propose SPEER: Sentence-level Planning via Embedded Entity Retrieval. Specifically, we mark each salient entity span with special “{{ }}” boundary tags and instruct the LLM to retrieve marked spans before generating each sentence. Sentence-level planning acts as a form of state tracking in that the model is explicitly recording the entities it uses. We fine-tune Mistral and Zephyr variants on a large-scale, diverse dataset of ~167k in-patient hospital admissions and evaluate on 3 datasets. SPEER shows gains in both coverage and faithfulness metrics over non-guided and guided baselines."
date: 2024-01-04
paperurl: https://arxiv.org/pdf/2401.02369
venue: CoLM
---
