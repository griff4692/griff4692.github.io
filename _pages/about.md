---
permalink: /
title: "Griffin Adams"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me

I am an LLM Researcher with a Ph.D. in Computer Science from Columbia University, an M.S. from Carnegie Mellon University, and a B.A. from Dartmouth College. My expertise lies in training and evaluating Large Language Models (LLMs) on large-scale, real-world data, with a focus on biomedical and clinical applications. My work aims to bridge the gap between cutting edge research (synthetic data, efficient inference, extending inference compute, etc.) and practical applications.

# Research Focus

My research addresses key challenges in long-context language modeling, particularly on noisy datasets. I've developed new methods for:

- Dataset curation from real-world data ([ClinSum, NAACL '21](https://aclanthology.org/2021.naacl-main.382/))
- Synthetic data for self-correction ([Reference Revision, EMNLP '22](https://aclanthology.org/2022.findings-emnlp.296/))
- Offline RL ([Summary Calibration, ACL '23](https://aclanthology.org/2023.acl-long.587/))
- Knowledge distillation for domain transfer learning ([ClinDistill, MLHC '23](https://proceedings.mlr.press/v219/adams23a.html))
- Planning algorithms ([SPEER, CoLM '24](https://arxiv.org/abs/2401.02369))
- Scaling inference compute ([Plan-Guided Best-of-N, ACL '23](https://aclanthology.org/2023.acl-long.151/), [Chain of Density, EMNLP '23](https://aclanthology.org/2023.newsum-1.7/))
- Graphical models for representation learning ([Latent Meaning Cells, MLHC '20](https://pubmed.ncbi.nlm.nih.gov/34790898/))

# Current Work

I'm currently focused on reducing the cost of long-context inference. I developed [Cold Compress](https://github.com/AnswerDotAI/cold-compress/), an open-source library for KV cache compression. Cold Compress implements complex KV cache eviction methods with static computational graphs, which are fully torch compilable. The end result is a toolkit that strikes a balance between simplicity and performance, making it both accessible to all and performant enough for experimentation.

I'm committed to developing models that can effectively handle extended contexts on noisy, real-world data. Please reach out if you'd like to chat about scaling inference-time compute for non-reasoning tasks, making RAG pipelines more friendly to noisy data, or enabling long-context modeling on consumer hardware.