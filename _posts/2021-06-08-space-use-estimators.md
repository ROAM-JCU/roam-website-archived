---
toc: true
layout: post
description: A review on some of the common methods of space use estimation for animal movement.
categories: [space-use]
title: Space-use estimators
---

Thank you to everyone who presented at our meeting on space-use estimators. 

We have compiled the presentations and now have this lovely guide to a few of the common methods (below). 

One takeaway from the meeting is that many of these methods are static and do not account for spatial or temporal autocorrelation in the data. 

For this reason, we are interested in learning a bit more about two of the third-generation space use estimators: the Movement-based Kernel Density Estimate (MKDE) and the Autocorrelated Kernel Density Estimate (AKDE). 

Both of these are based on similar principles of applying a movement model to our location data as the first step in generating a utilization distribution. 

For the next meeting we are going to work through an example of each of these with Kyana’s tortoise data in R. 

Please bring your laptops with R installed, your lunch and your thinking caps.
 
See you there!

## ROAM summary on space-use estimators

![](../_posts/2021-06-08-space-use-estimators/roam_sue_00001.jpeg)

![](/_posts/2021-06-08-space-use-estimators/roam_sue_00002.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00003.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00004.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00005.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00006.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00007.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00008.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00009.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00010.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00011.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00012.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00013.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00014.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00015.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00016.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00017.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00018.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00019.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00020.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00021.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00022.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00023.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00024.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00025.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00026.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00027.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00028.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00029.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00030.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00031.jpeg)

![](2021-06-08-space-use-estimators/roam_sue_00032.jpeg)
