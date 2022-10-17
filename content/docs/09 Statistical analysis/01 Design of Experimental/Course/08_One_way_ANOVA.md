---
weight: 8
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: null
draft: false
lastmod: "2022-07-09"
series: 
tags: []
title: One-Way ANOVA
toc: true
---




<!--more-->

For the analysis of variance it is useful to describe the observations using `a statistical model`.   


<center><img src="https://latex.codecogs.com/svg.latex?\space 
y_{ij} = \mu + \tau_i + \epsilon_{ij}" /></center>

<div class="row">
  <div class="column">
  Hypotheses test:  
<center><img src="https://latex.codecogs.com/svg.latex?\space 
H_0: \tau_1 = \tau_2 = ... = \tau_a = 0" /></center>
<center>$H_1: \tau_i \neq 0$ for at least one i</center>
  </div>
  <div class="column">
  <center><img src="https://latex.codecogs.com/svg.latex?\space " title=""/></center>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-09 100429.png" style ="float: left" HSPACE="10" VSPACE="10"/>
  </div>
</div> 

In the effects model Each observation $y_{ij}$ can be represented by an overall mean, $\mu$, plus the effect of the ith treatment, $\tau_i$, plus a random error, $\epsilon_{ij}$. The effects model is not the only model to be used to represent the data. However, it has some intuitive appeal in that the average $\mu$ is a constant, and the treatment effects $\tau_i$ represent the deviation from this constant when the specific treatments are applied. This model is called `single factor analysis of varianc`e or `one-way ANOVA`. As the treatment effects can be considered as a deviation from the overall mean, The hypothesis test for the one way analysis of variance can be expressed in terms of the treatment effect $\tau_i$. In the null hypothesis $\tau_i$ is equal zero for every i. That is the effect of the factor is zero, there is no deviation from the overall mean. In the alternative hypothesis H<sub>1</sub> $\tau_i$ is different from zero for at least one i, meaning the cotton content affects the tensile strength, at least at one level of cotton content. 

<style type = "text/css">
.row {
  margin-left:-5px;
  margin-right:-5px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}

.column {
  float: left;
  padding: 5px; /* space between two tables*/
}

</style>
