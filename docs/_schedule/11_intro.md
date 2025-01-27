---
# Determines which item appears first on the schedule (lowest number (0) appears first)
sequence_id: 2

day: Tuesday, 11th

# Time of the event
time: 10:30 - 11:15

# Title of the event
title: "Intro Talk: The AlgoPerf Benchmark"
subtitle: Motivation, Rules, and Results

# Speaker Info
speaker: Frank Schneider
webpage: /organizers
affil: University of Tübingen
affil_link: https://fsschneider.netlify.app/
# affil2: Buzz University
# affil2_link: https://buzz.edu

# Image
img: ../organizers/frank.jpg
img_link: /organizers

# Abstract
abstract: >
    The goal of the AlgoPerf: Training Algorithms competition is to evaluate practical speed-ups in neural network training achieved solely by improving the underlying training algorithms. In the external tuning ruleset, submissions must provide workload-agnostic hyperparameter search spaces, while in the self-tuning ruleset they must be completely hyperparameter-free. In both rulesets, submissions are compared on time-to-result across multiple deep learning workloads, training on fixed hardware. This talk presents the inaugural AlgoPerf competition's results, which drew 18 diverse submissions from 10 teams. Our investigation reveals several key findings: (1) The winning submission in the external tuning ruleset, using Distributed Shampoo, demonstrates the effectiveness of non-diagonal preconditioning over popular methods like Adam, even when compared on wall-clock runtime. (2) The winning submission in the self-tuning ruleset, based on the Schedule Free AdamW algorithm, demonstrates a new level of effectiveness for completely hyperparameter-free training algorithms. (3) The top-scoring submissions were surprisingly robust to workload changes. We also discuss the engineering challenges encountered in ensuring a fair comparison between different training algorithms. These results highlight both the significant progress so far, and the considerable room for further improvements.
---