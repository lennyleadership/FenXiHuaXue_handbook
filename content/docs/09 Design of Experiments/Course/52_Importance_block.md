---
weight: 52
title: 52 Importance of Block
authors: edited by Lenny Lin
categories: 
tags: []
description: null
draft: false
date: "2022-01-03"
lastmod: "2022-08-02"
series: 
toc: true
---




<!--more-->
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 223823.png" style ="float: left" HSPACE="10" VSPACE="10"/>
But why blocking is important? Let's go back to the beginning of our problem. We have two batches of raw material to run this 2ˆ4 factorial design. However, let's suppose we have skipped that class about blocks and then we decided to distribute the raw material randomly among the runs. And this is not the bad decision at the first glance. Here we have the raw material randomly distributed. However, Batch A is still of low quality, and the results are 20 units lower. So let's reduced by 20 units all the results from batch A, and now we have our final results to analyze. As an exercise, you can use R to analyze this example. The response is the FR2 column in the data file. I will skip directly to the results.  

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 224025.png" style ="float: left" HSPACE="10" VSPACE="10"/>
If we run a complete analysis of variance with main factors, two-factor interactions, three-factor interactions and a four-factor interaction. We cannot calculate the F-zero and the p-values, as we don't have residuals, but we can take a look and the sum of squares. And here there are some pretty high sum of squares, and some three-factor interactions have a substantially high sum of squares. However, we already know that three-factor interactions are rare. This way, these high sum of squares in the three-factor interactions is a symptom that probably something is wrong.   
<br>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 224212.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 224443.png" style ="float: left" HSPACE="10" VSPACE="10"/>
After performing backwards elimination, we can have the final analysis of variance table. Here we can see that only the stirring rate and the interaction temperature and concentration were significant. We have missed most of the significant factors and interactions. But why does this happen? If we compare this new analysis of variance with the analysis of variance from the blocks, we can see that the big difference is in the mean squares of the residuals. The mean squares of the residuals of this new analysis of variance is 7.5 times higher. Thus, all the F_zeros are lower and the p-values are higher in this new analysis of variance. This is happening because the batches of raw material are an important source of variability that when randomly distributed are embedded in the residuals. However, when using blocks, we are able to withdraw some known source of variabilities, as the raw material, from the error. This way the error is lower and we can see the significant effects of the main factors and interactions. 