---
# Determines which item appears first on the schedule (lowest number (0) appears first)
sequence_id: 1

day: Wednesday, 12th

# Time of the event
time: 10:15 - 11:00

# Title of the event
title: Invited Talk I
subtitle: How does Gradient Descent Work?

# Speaker Info
speaker: Jeremy Cohen
webpage: http://cs.cmu.edu/~jeremiac
affil: Flatiron Institute
affil_link: https://www.simonsfoundation.org/people/jeremy-cohen/
# affil2: Buzz University
# affil2_link: https://buzz.edu

# Image
img: ../speakers/JeremyCohen.jpg
img_link: http://cs.cmu.edu/~jeremiac

# Add the abstract property
abstract: |
  Optimization is the engine of deep learning, yet the theory of optimization has had little impact on the practice of deep learning. Why? In this talk, we will first show that traditional theories of optimization fail to explain the convergence of the simplest optimization algorithm — deterministic gradient descent — in deep learning. Whereas traditional theories assert that gradient descent converges because the curvature of the loss landscape is "a priori" small, in reality gradient descent converges because it *actively avoids* high-curvature regions of the loss landscape.  Understanding this behavior requires Taylor expanding to third order, which is one order higher than normally used in optimization theory.  While the "fine-grained" dynamics of gradient descent involve chaotic oscillations that are difficult to analyze, we will demonstrate that the "time-averaged" dynamics are, fortunately, much more tractable.  We will show that our time-averaged analysis yields highly accurate quantitative predictions in a variety of deep learning settings.  Since gradient descent is the simplest optimization algorithm, we hope that this analysis can set the stage for a mathematical theory of optimization in deep learning.  This talk is based partly on works by Alex Damian and Eshaan Nichani.
---