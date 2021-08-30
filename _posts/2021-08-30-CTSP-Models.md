# CTSP models and variograms

---
toc: true
layout: post
description: Introducing continuous-time stochastic process (CTSP) models and fitting these to variograms.
categories: [space-use]
title: Movement Models and Variogram Fitting
---

Most long-term animal tracking provides location estimates at discrete time points, but do not provide information on behaviour and movement between these estimates. Continuous-time stochastic process (CTSP) models provide statistical prediction of dispersal based on the known location of the individual or object. 
In analyses such as home range calculation, it is important to account for the correct level of autocorrelation in the data to avoid over or under fitting and present a realistic estimation of spatial use. In this workshop ROAM members presented [overviews](https://github.com/ROAM-JCU/roam-summaries/blob/main/summaries/ROAM_continuous_time_movement_models.pdf) of a variety of CTSP models. Basic models like Brownian Motion do not assume range residency of an animal, assuming instead that movement is random and dispersal unlimited. More complex models can assume range residency and autocorrelation in both time and space to give a more realistic estimation of space use.
The R package [ctmm](https://cran.r-project.org/web/packages/ctmm/index.html) provides a simple method to visualise movement data and identify CTSP models that best fits the data. By plotting the autocorrelation structure of telemetry data in a [variogram](https://cran.r-project.org/web/packages/ctmm/vignettes/variogram.html), CTSP models can be overlaid to identify the most appropriate model. Methods introduced by this package can also automate the process to identify models that fit a variety of different datasets. Additionally, ctmm’s author Dr Christian Fleming has created simple [animated explanations](https://www.youtube.com/watch?v=5S45TD4bnp8) of the models that can be used to calculate home ranges.
