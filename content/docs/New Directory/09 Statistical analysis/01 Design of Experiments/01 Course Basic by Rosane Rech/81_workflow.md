---
weight: 81
title: Workflow
authors: Lenny Lin
categories: 
tags: []
description: null
draft: false
date: "2022-10-27"
lastmod: "2022-10-27"
series: 
toc: true
---


<!--more-->
---

Workflow to study the effect of several factors.  


Step #1:  
Define the resolution, two levels of each factor, the number of factors, and the number of runs.  
Determine the response.


Step #2:  
Create and run a fractional factorial design using an R package. (use FrF2 package, or AlgDesign package)
always *use* (what is the right word?) the highest possible resolution.  


Step #3:  
View the output of the design, and finalize the design plan.


Step #4:  
Run the experiment and collect data.  

no replicate.


Step #5: 
build a linear model for the main parameters and two-parameter interactions (or central composite face quadratic model).  
(difficult term: aliased to each other. explain it in plain language)
visualize the effect of the main parameters and two-parameter interactions with Daniel plot. segregate parameters by their significance.

Remove insignificant parameters from the model and run the model again. Select significant main parameters and the two-parameter interactions.




