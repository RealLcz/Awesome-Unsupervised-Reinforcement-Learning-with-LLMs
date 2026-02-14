# Awesome Unsupervised Reinforcement Learning with LLMs
This repo is a collection of latest papers and repos of unsupervised RL methods for LLMs

## Overview

### Learning with internal rewards

[Right Question is already half the answer: Fully Unsupervised LLM reasoning incentivization](https://arxiv.org/abs/2504.05812)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/QingyangZhang/EMPO)

NeurIPS 2025 spotlight. This paper introduces EMPO, an unsupervised RL method aiming at minimizing the semantic entropy of the context，who holds the belief that minimizing entropy on unlabeled data can improve classification accuracy by encouraging model confidence.

[Learn to Reason without External Rewards](https://openreview.net/forum?id=OU9nFEYR2M)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/sunblaze-ucb/Intuitor)

ICLR 2026 poster. This paper introduces an unsupervised metric called **self-certainty**, which demonstrates a better performance than token-level entropy and self-consistency when the response length is getting longer.


### Self-play Paradigm

[TTRL: Test-time Reinforcement Learninng](https://arxiv.org/abs/2504.16084)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/PRIME-RL/TTRL)

NeurIPS 2025 poster. This paper introduces a voting mechanism.

[Absolute Zero: Reinforced Self-play Reasoning with Zero Data](https://arxiv.org/pdf/2505.03335)  [![GitHub Repo stars](https://img.shields.io/badge/Github-Repo-blue?logo=github)](https://github.com/LeapLabTHU/Absolute-Zero-Reasoner)



### Other Relavant Interesting Researches
[Martingale Score: An Unsupervised Metric for Bayesian Rationality in LLM Reasoning](https://arxiv.org/abs/2512.02914) 

NeurIPS 2025 poster. This paper intruduces a metric called **Martingale**, which aims to test whether the LLMs are stuck in belief entrenchment.
