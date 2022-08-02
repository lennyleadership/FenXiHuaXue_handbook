---
authors: edited by Lenny Lin
categories: Category
date: null
description: 
draft: false
lastmod: "2022-05-17"
series:
tags: []
title: IPO Optimization Procedure
toc: true
---


<!--more-->

In general, peak picking is done for each individual data file but for retention time correction and grouping multiple data files are necessary.  

The optimization procedure splits the parameters by applying a semi sequential approach.   

1) Peak picking parameters are optimized.  
2) The retention time correction and grouping parameters are simultaneously optimized.   
3) Grouping results in peak groups by combining peaks with similar masses and retention times from different LC-MS runs.  

Simultaneous optimization of retention time correction and grouping is necessary because grouping is required for the assessment of the retention time correction step, which in turn can improve the grouping. This semisequential approach additionally decreases the overall computing time. The different levels for the XCMS parameters are determined by a design of experiments approach. Box-Behnken designs (BBD) serve as basis to generate the DoEs. BBD is a three level incomplete factorial design for fitting a second order response surface model. Three levels denote that for each parameter three different evenly spaced values are tested. The two outer values define a range, the middle value a center point. In contrast to a full factorial design, BBD does not test all factorial combinations, making it highly efficient [19]. For the default levels used by IPO in the first DoE see Additional file 1. To evaluate the result of the DoE, one score for peak picking and one score for retention time correction and grouping is used. 
