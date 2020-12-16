# White-Box Analysis over Machine Learning: Modeling Performance of Configurable Systems - Supplementary Material

## Abstract
Performance-influence models can help stakeholders understand how and where configuration options and their interactions influence the performance of a system. With this understanding, stakeholders can debug performance and make deliberate configuration decisions. Current black-box techniques to build such models combine various sampling and learning strategies, resulting in trade offs between measurement effort, accuracy, and interpretability. We present Comprex, a white-box approach to build performance-influence models for configurable systems, combining insights of local measurements, dynamic taint analysis to track options in the implementation, compositionality, and compression of the configuration space, without using machine learning to extrapolate incomplete samples. Our evaluation on 4 widely-used open-source projects demonstrates that Comprex builds similarly accurate performance-influence models to the most accurate and expensive black-box approach, but at a reduced cost and with additional benefits from interpretable and local models.

## Source Code

- [Comprex](https://github.com/miguelvelezmj25/Comprex/tree/asej20)
- [Subject Systems](https://github.com/miguelvelezmj25/performance-mapper-evaluation)