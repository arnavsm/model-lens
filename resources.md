# Resources for Mechanistic Interpretability

## Table of Contents
- [Resources for Mechanistic Interpretability](#resources-for-mechanistic-interpretability)
  - [Table of Contents](#table-of-contents)
  - [Tutorial](#tutorial)
  - [History](#history)
  - [Code](#code)
    - [Library](#library)
    - [Codebase](#codebase)
    - [Starter Code](#starter-code)
  - [Survey](#survey)
  - [Video](#video)

## Tutorial

* **Concrete Steps to Get Started in Transformer Mechanistic Interpretability** [[Neel Nanda's blog]](https://www.neelnanda.io/mechanistic-interpretability/getting-started)
* **Mechanistic Interpretability Quickstart Guide** [[Neel Nanda's blog]](https://www.neelnanda.io/mechanistic-interpretability/getting-started)
* **ARENA Mechanistic Interpretability Tutorials by Callum McDougall** [[website]](https://arena-ch1-transformers.streamlit.app/)
* **200 Concrete Open Problems in Mechanistic Interpretability: Introduction by Neel Nanda** [[AlignmentForum]](https://www.alignmentforum.org/s/yivyHaCAmMJ3CqSyj)
* **Transformer-specific Interpretability** [[EACL 2023 Tutorial]](https://projects.illc.uva.nl/indeep/tutorial/)

## History

* **Mechanistic?** [[BlackBoxNLP workshop at EMNLP 2024]](https://arxiv.org/abs/2410.09087)
  * This paper explores the multiple definitions and uses of "mechanistic interpretability," tracing its evolution in NLP research and revealing a critical divide within the interpretability community.

## Code

### Library

* **TransformerLens** [[github]](https://github.com/neelnanda-io/TransformerLens)
  * A library for mechanistic interpretability of GPT-style language models
* **CircuitsVis** [[github]](https://github.com/alan-cooney/CircuitsVis)
  * Mechanistic Interpretability visualizations
* **baukit** [[github]](https://github.com/davidbau/baukit)
  * Contains some methods for tracing and editing internal activations in a network.
* **transformer-debugger** [[github]](https://github.com/openai/transformer-debugger)
  * Transformer Debugger (TDB) is a tool developed by OpenAI's Superalignment team with the goal of supporting investigations into specific behaviors of small language models. The tool combines automated interpretability techniques with sparse autoencoders.
* **pyvene** [[github]](https://github.com/stanfordnlp/pyvene)
  * Supports customizable interventions on a range of different PyTorch modules
  * Supports complex intervention schemes with an intuitive configuration format, and its interventions can be static or include trainable parameters.
* **ViT-Prisma** [[github]](https://github.com/soniajoseph/ViT-Prisma)
  * An open-source mechanistic interpretability library for vision and multimodal models.
* **pyreft** [[github]](https://github.com/stanfordnlp/pyreft)
  * A Powerful, Parameter-Efficient, and Interpretable way of fine-tuning
* **SAELens** [[github]](https://github.com/jbloomAus/SAELens)
  * Training and analyzing sparse autoencoders on Language Models
* **Mechanistic Interpretability Toolbox** [[github]](https://github.com/adamcasson/mechanistic-interpretability)
  * A toolbox built around PyTorch and PyTorch Lightning designed to facilitate mechanistic interpretability research on small models and toy tasks

### Codebase

* **mamba interpretability** [[github]](https://github.com/Phylliida/mamba_interp)

### Starter Code

* **Interpretability Starter Templates**
  * [[github]](https://github.com/apartresearch/interpretability-starter)
  * Contains starter templates and tools for interpretability research, including EasyTransformer for exploring phenomena within language models.

* **Mechanistic Interpretability Projects**
  * [[github]](https://github.com/ayyucekizrak/Mechanistic-Interpretability)
  * Focuses on understanding induction heads and QK circuits in transformer-based models like GPT-2. Developed as part of the AI Alignment Course.

* **Awesome LLM Interpretability**
  * [[github]](https://github.com/cooperleong00/Awesome-LLM-Interpretability)
  * A curated list of resources related to interpretability, including libraries like TransformerLens, CircuitsVis, and others that support mechanistic analysis.

## Survey

* **A Survey on Sparse Autoencoders: Interpreting the Internal Mechanisms of Large Language Models** [[arxiv2503]](https://arxiv.org/abs/2503.05613)
* **Representation Engineering for Large-Language Models: Survey and Research Challenges** [[arxiv2502]](http://arxiv.org/abs/2502.17601)
* **Toward Transparent AI: A Survey on Interpreting the Inner Structures of Deep Neural Networks** [[SaTML 2023]](https://ieeexplore.ieee.org/abstract/document/10136140) [[arxiv 2207]](https://arxiv.org/abs/2207.13243)
* **Neuron-level Interpretation of Deep NLP Models: A Survey** [[TACL 2022]](https://aclanthology.org/2022.tacl-1.74)
* **Explainability for Large Language Models: A Survey** [[TIST 2024]](https://dl.acm.org/doi/10.1145/3639372) [[arxiv 2309]](https://arxiv.org/abs/2309.01029)
* **Opening the Black Box of Large Language Models: Two Views on Holistic Interpretability** [[arxiv 2402]](http://arxiv.org/abs/2402.10688)
* **Usable XAI: 10 Strategies Towards Exploiting Explainability in the LLM Era** [[arxiv 2403]](http://arxiv.org/abs/2403.08946)
* **Mechanistic Interpretability for AI Safety -- A Review** [[arxiv 2404]](http://arxiv.org/abs/2404.14082)
* **A Primer on the Inner Workings of Transformer-based Language Models** [[arxiv 2405]](https://arxiv.org/abs/2405.00208)
* **A Practical Review of Mechanistic Interpretability for Transformer-Based Language Models** [[arxiv 2407]](http://arxiv.org/abs/2407.02646)
* **Internal Consistency and Self-Feedback in Large Language Models: A Survey** [[arxiv 2407]](https://arxiv.org/abs/2407.14507)
* **The Quest for the Right Mediator: A History, Survey, and Theoretical Grounding of Causal Interpretability** [[arxiv 2408]](https://arxiv.org/abs/2408.01416)
* **Attention Heads of Large Language Models: A Survey** [[arxiv 2409]](https://arxiv.org/abs/2409.03752) [[github]](https://github.com/IAAR-Shanghai/Awesome-Attention-Heads)

*Note: These Alignment surveys discuss the relation between Interpretability and LLM Alignment.*

* **Large Language Model Alignment: A Survey** [[arxiv 2309]](https://arxiv.org/abs//2309.15025)
* **AI Alignment: A Comprehensive Survey** [[arxiv 2310]](https://arxiv.org/abs/2310.19852) [[github]](https://github.com/PKU-Alignment/AlignmentSurvey) [[website]](https://alignmentsurvey.com/)

## Video

* **Neel Nanda's Channel** [[Youtube]](https://www.youtube.com/@neelnanda2469)
* **Chris Olah - Looking Inside Neural Networks with Mechanistic Interpretability** [[Youtube]](https://www.youtube.com/watch?v=2Rdp9GvcYOE)
* **Concrete Open Problems in Mechanistic Interpretability: Neel Nanda at SERI MATS** [[Youtube]](https://www.youtube.com/watch?v=FnNTbqSG8w4)
* **BlackboxNLP's Channel** [[Youtube]](https://www.youtube.com/@blackboxnlp)