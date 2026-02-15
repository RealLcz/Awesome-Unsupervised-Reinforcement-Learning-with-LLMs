# Awesome Unsupervised Reinforcement Learning with LLMs
This repo is a collection of latest papers and repos of unsupervised RL methods for LLMs

## Overview

### Learning with internal rewards

[Right Question is already half the answer: Fully Unsupervised LLM reasoning incentivization](https://arxiv.org/abs/2504.05812)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/QingyangZhang/EMPO)

NeurIPS 2025 spotlight. This paper introduces EMPO, an unsupervised RL method aiming at minimizing the semantic entropy of the context，who holds the belief that minimizing entropy on unlabeled data can improve classification accuracy by encouraging model confidence.

[Learn to Reason without External Rewards](https://openreview.net/forum?id=OU9nFEYR2M)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/sunblaze-ucb/Intuitor)

ICLR 2026 poster. This paper introduces an unsupervised metric called **self-certainty**, which demonstrates a better performance than token-level entropy and self-consistency when the response length is getting longer.

[The Unreasonable Effectiveness of Entropy Minimization in LLM Reasoning](https://arxiv.org/pdf/2505.15134)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/shivamag125/EM_PT)

NeurIPS 2025 poster. This paper introduces three methods, all of which aim to minimize the entropy. The difference between them is that they take a role in different stage.


### Self-play Paradigm

[TTRL: Test-time Reinforcement Learninng](https://arxiv.org/abs/2504.16084)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/PRIME-RL/TTRL)

NeurIPS 2025 poster. This paper introduces a voting mechanism.

[Absolute Zero: Reinforced Self-play Reasoning with Zero Data](https://arxiv.org/pdf/2505.03335)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/LeapLabTHU/Absolute-Zero-Reasoner)

Arxiv 2025-05-06. This paper introduces a self-play RL paradigm for code tasks. Surprisingly, it shows remarkable performance on math tasks, which proves the model's outstanding generalization ability.

[SSR-Zero: Simple Self-Rewarding Reinforcement Learning for Machine Translation](https://arxiv.org/pdf/2505.16637)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/Kelaxon/SSR-Zero) 

Arxiv 2025-06-20. This paper introduces SSR-Zero, specifically designed for Machine Translation, which is a fully online method and relies solely on self-judging rewards(Let the trained model simultaneously take a role in **Actor** and **Judge**.).

### Other Relavant Interesting Researches
[Martingale Score: An Unsupervised Metric for Bayesian Rationality in LLM Reasoning](https://arxiv.org/abs/2512.02914) 

NeurIPS 2025 poster. This paper intruduces a metric called **Martingale**, which aims to test whether the LLMs are stuck in belief entrenchment.

[Spurious Rewards: Rethinking Training Signals in RLVR](https://arxiv.org/abs/2506.10947)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/ruixin31/Spurious_Rewards)

Arxiv 2025-06-12. This paper demonstrates that spurious or weak rewards can also significantly improve Qwen2.5 families' reasoning performance. However, this methods fail when it is adopted to Olmo and LLaMA. Thus, this work highlights the importance of testing across multiple models with differing pretraining distributions, and testing across multiple different baselines, such as format and random rewards, when evaluating reinforcement learning techniques.
