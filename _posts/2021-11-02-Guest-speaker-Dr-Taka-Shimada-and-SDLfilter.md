---
toc: true
layout: post
description: Optimising sample sizes for animal distribution analysis using tracking data
categories: [tracking, sample size, utilization distribution, software, guest speaker, Shimada]
title: Guest speaker - Dr Takahiro Shimada and his SDLfilter R package
---

Today we welcomed Dr Takahiro (Taka) Shimada, Principal Conservation Officer, Queensland Government, Australia.

Taka gave us a fascinating presentation about the challenges of estimating the optimum sample size when assessing the area used by animals. Studies using tracking devices such as GPS and acoustic tags, are often constrained by the elevated costs (time and money) of these technologies. For this reason, only a small fraction of the population can be tracked. This raises the question about to what extent the tracks of a few individuals can be representative of the whole population.

With this challenge in mind, Taka and his collaborators developed a probabilistic novel approach for evaluating the adequacy of sample size (i.e. number of tracked animals) when estimating animals' spatial distribution. They proposed to use probabilities to calculate overlap between an animal Utilisation Distribution (UD) with respect to the collective UD of previous animals.

Their approach offers an unprecedented opportunity to evaluate and re-evaluate the minimum sample size required to estimate spatial distributions in tracking studies, and thus optimize the use of tracking devices. Furthermore, their analytical solution can give a much needed measurement of un/certainty to decision makers and managers.

You can read the manuscript describing Shimada and collaborators' new method  [here](https://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/2041-210X.13506). The SDLfilter R package for using their method is available [here](https://github.com/TakahiroShimada/SDLfilter).

From the fruitful conversation during and after Taka presentation, a new feature to estimate confidence intervals has been included in his SDLfilter package.
