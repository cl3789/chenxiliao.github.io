---
title: "CTP-LLM: Clinical trial phase transition prediction using large language models"
collection: publications
category: conferences
permalink: /publication/CTP_LLM
excerpt: 'We proposed CTP-LLM, a LLM powered framework to predict Clinical Trial Outcome Prediction.'
date: 2024-08-20
venue: 'arxiv'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2408.10995'
citation: 'Reinisch, M., He, J., Liao, C., Siddiqui, S., & Xiao, B. (2024, December). Ctp-llm: Clinical trial phase transition prediction using large language models. In 2024 IEEE International Conference on Bioinformatics and Biomedicine (BIBM) (pp. 3667-3672). IEEE.'
---

New medical treatment development requires multiple phases of clinical trials. Despite the significant human and financial costs of bringing a drug to market, less than 20% of drugs in testing will make it from the first phase to final approval. Recent literature indicates that the design of the trial protocols significantly contributes to trial performance. We investigated Clinical Trial Outcome Prediction (CTOP) using trial design documents to predict phase transitions automatically. We propose CTPLLM, the first Large Language Model (LLM) based model for CTOP. We also introduce the PhaseTransition (PT) Dataset; which labels trials based on their progression through the regulatory process and serves as a benchmark for CTOP evaluation. Our fine-tuned GPT-3.5- based model (CTP-LLM) predicts clinical trial phase transition by analyzing the trial’s original protocol texts without requiring humanselected features. CTP-LLM achieves a 67% accuracy rate in predicting trial phase transitions across all phases and a 75% accuracy rate specifically in predicting the transition from Phase III to final approval. Our experimental performance highlights the potential of LLM powered applications in forecasting clinical trial outcomes and assessing trial design.