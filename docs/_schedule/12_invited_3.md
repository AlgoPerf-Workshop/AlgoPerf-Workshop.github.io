---
# Determines which item appears first on the schedule (lowest number (0) appears first)
sequence_id: 5

day: Wednesday, 12th

# Time of the event
time: 13:30 - 14:15

# Title of the event
title: Invited Talk III
subtitle: Stochastic-Gradient-based Algorithms for Nonconvex Constrained Optimization and Learning

# Speaker Info
speaker: Frank E. Curtis
webpage: https://coral.ise.lehigh.edu/frankecurtis/
affil: Lehigh University
affil_link: https://coral.ise.lehigh.edu/frankecurtis/
# affil2: Buzz University
# affil2_link: https://buzz.edu

# Image
img: ../speakers/FrankECurtis.jpg
# img_link: https://web.stanford.edu/~udell/

# Add the abstract property
abstract: |
  This talk focuses on recent work by my research group and collaborators on the design and analysis of stochastic-gradient-based algorithms for solving nonconvex constrained optimization problems.  Our primary motivation is to offer better alternatives to regularization methods (also known as penalty or soft-constraint methods) for inducing structure in a solution or incorporating prior knowledge in a learning problem.  Instead, our algorithms are designed to solve constrained problems directly.  (Such methods are sometimes referred to as hard-constraint methods.)  Even though soft-constraint and hard-constraint methods can be seen to be equivalent, in some sense, using classical penalty function theory, their performance in practice is radically different.  Therefore, our aim has been to design such methods such that they are computationally efficient and have rigorous convergence and worst-case complexity guarantees.  Our numerical experiments with physics-informed learning and fair supervised learning problems have been encouraging, but we expect that our proposed strategies could also be successful beyond the settings we have considered so far.  The talk will also touch upon possible connections between our approach and reduced-space methods for training and/or fine-tuning machine learning models.
---