---
toc: true
layout: post
description: Learning more about Movement-based Kernel Density Estimate (MKDE) and the Autocorrelated Kernel Density Estimate (AKDE).
categories: [space-use]
title: Diving into 3rd-gen space use estimators
---

A corollary from our last meeting is that many methods for estimating space use are static and do not account for spatial or temporal autocorrelation in the data. For this reason, we were interested in learning a bit more about two of the third-generation space use estimators: the Movement-based Kernel Density Estimate (MKDE) and the Autocorrelated Kernel Density Estimate (AKDE). Both are based on similar principles of applying a movement model to our location data as the first step in generating a utilization distribution. In this meeting we worked through an example of each of these with Kyana’s tortoise data in R. 

