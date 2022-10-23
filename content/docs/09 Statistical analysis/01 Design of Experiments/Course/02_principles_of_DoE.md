---
weight: 2
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: null
draft: false
lastmod: "2022-07-08"
series: 
tags: []
title: 02 Introduction
toc: true
---



<!--more-->

The statistical design of experiments refers to the process of planning the experiment. So the appropriate data will be collected and analyzed by statistical methods, resulting in invalid and objective conclusions. When the problem involves data that are subject to experimental errors, statistical methods are the only objective approach to the analysis. The design of experiments is based on three basic principles. Randomization, replication, and blocking.  

Randomization means that both the allocation of experimental material and the order in which the individual runs will be performed are randomly determined.  

Let's take the example of a cooker that wishes to develop the best apple pie. First, the cooker goes to the market and buys a batch of apples. Then he uses half of the apples to make an apple pie using recipe one and the other half to make a pie using recipe two. However, he had made the pie with recipe one two days after buying the apples, while the pie with recipe two seven days after buying the apples. The apples where at a different ripening stage. Now, if there are differences between the pies, it can be because of the recipe, but also because of the ripening stage of the apples. <mark>The allocation of experimental material was not randomized</mark>.   

Randomization is the cornerstone underlying the use of statistical methods in the experimental design. It assures that the errors are independently distributed among the runs.  

Replication. Replication means `an independent repeat run` of each factor combination.  

If the cooker from the previous example get some apples and use them to make a batch of three pies using recipe one, does the cooker have three replications of the apple pie with recipe one? <mark>No, these are not replications, they are repeated measures</mark>. Replication means `an independent repeat run` of each factor combination. To have `three replications`, the cooker has to do one pie using recipe one, then another one from scratch, And then a third one from scratch again. Now the cooker has `three independent replications`.   

The replications reflect the sources of variability of the system. In this case, how much the pies of the same recipe differ from each other.  

Blocking. Blocking is used to eliminate the variability transmitted by nuisance factors.  

Imagine that the cooker can only make two pies each day. Then, he buys a batch of apples and makes one pie using recipe one and one pie using recipe two. Another day, The cooker again buys a batch of apples and makes one pie using recipe one and one pie using recipe two. In this case, the pies are divided into blocks. Each block is a different batch of apples at a different day.  

Generally, a block is a set of relatively homogeneous experimental conditions. The concept and the use of blocks in the design of experiments will be discussed in deep in Section 7 of this course. 
