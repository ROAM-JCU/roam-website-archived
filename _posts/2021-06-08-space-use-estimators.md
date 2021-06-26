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

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00001.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00002.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00003.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00004.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00005.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00006.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00007.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00008.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00009.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00010.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00011.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00012.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00013.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00014.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00015.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00016.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00017.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00018.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00019.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00020.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00021.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00022.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00023.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00024.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00025.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00026.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00027.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00028.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00029.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00030.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00031.jpeg)

![]({{ site.baseurl }}/images/2021-06-08-space-use-estimators/roam_sue_00032.jpeg)
