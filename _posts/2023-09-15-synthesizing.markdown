---
layout: post
title:  "Synthesizing Interpretable Control Policies through Large Language Model Guided Search"
venue: "arXiv preprint arXiv:2410.05406"
date: 2024-10-02 17:45:25 +00:00
image: /images/interpretable-llm.png
categories: Research
author: "Carlo Bosio"
authors: "<strong>Carlo Bosio</strong>, Mark W. Mueller"
arxiv: https://arxiv.org/abs/2410.05406
video: https://youtu.be/7T7yRGya-q8
abstract: "The combination of Large Language Models (LLMs), systematic evaluation, and evolutionary algorithms has enabled breakthroughs in combinatorial optimization and scientific discovery. We propose to extend this powerful combination to the control of dynamical systems, generating interpretable control policies capable of complex behaviors. With our novel method, we represent control policies as programs in standard languages like Python. We evaluate candidate controllers in simulation and evolve them using a pre-trained LLM. Unlike conventional learning-based control techniques, which rely on black box neural networks to encode control policies, our approach enhances transparency and interpretability. We still take advantage of the power of large AI models, but leverage it at the policy design phase, ensuring that all system components remain interpretable and easily verifiable at runtime. Additionally, the use of standard programming languages makes it straightforward for humans to finetune or adapt the controllers based on their expertise and intuition. We illustrate our method through its application to the synthesis of an interpretable control policy for the pendulum swing-up and the ball in cup tasks. We make the code available at https://github.com/muellerlab/synthesizing_interpretable_control_policies.git" 
bibtex: |
  @article{bosio2024synthesizing,
  title={Synthesizing Interpretable Control Policies through Large Language Model Guided Search},
  author={Bosio, Carlo and Mueller, Mark W},
  journal={arXiv preprint arXiv:2410.05406},
  year={2024}
  }
id: "paper-interpretable"
---
Encoding control policies as programs in Python and evolving them using LLMs.