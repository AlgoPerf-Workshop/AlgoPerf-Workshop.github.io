---
# Determines which item appears first on the schedule (lowest number (0) appears first)
sequence_id: 4

day: Tuesday, 11th

# Time of the event
time: 11:15 - 12:00

# Title of the event
title: "Spotlight Talk I: External Tuning Track Winner"
subtitle: Scaling Beyond Diagonal Preconditioners for Training Neural Networks At-Scale

# Abstract
abstract: >
    Over the past decade, diagonal scaling-based adaptive subgradient methods like AdaGrad and Adam(W) have been widely adopted for neural network training due to their simplicity, linear memory requirements, and robustness to hyperparameter tuning. However, full-matrix preconditioned adaptive subgradient methods, which offer superior performance, are often hindered by their quadratic memory and cubic computational complexity. Recent advances in approximate Kronecker factorization-based methods, including K-FAC and Shampoo, offer a promising alternative, achieving faster convergence than diagonal approximation-based methods while remaining computationally tractable. This talk provides an overview of the Shampoo algorithm and presents our distributed PyTorch implementation, highlighting key heuristics, performance optimizations, and systems/scalability developments that enable efficient training of million- and billion-parameter models. We will also share key insights and learnings from our AlgoPerf PyTorch Shampoo submission, including generalizable configurations and future research directions.

# Speaker Info
speaker: Anna Cai & Michael Shi
webpage: https://www.linkedin.com/in/a-cai/
affil: Meta AI
affil_link: https://hjmshi.github.io/
# affil2: Buzz University
# affil2_link: https://buzz.edu

# Image
img: ../speakers/anna.jpeg
img_link: https://www.linkedin.com/in/a-cai/
---