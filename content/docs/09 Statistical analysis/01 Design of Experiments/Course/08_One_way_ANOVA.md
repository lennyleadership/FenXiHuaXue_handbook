---
weight: 8
title: 08 One-Way ANOVA
authors: edited by Lenny Lin
categories: 
tags: []
description: null
draft: false
date: "2022-01-03"
lastmod: "2022-07-09"
series: 
toc: true
---

Section 2: Experiments with a single factor


<!--more-->
---

For the analysis of variance it is useful to describe the observations using `a statistical model`.   



<div class="row">
  <div class="column_left">
\begin{equation}
y_{ij} = \mu + \tau_i + \epsilon_{ij}
\end{equation}

Hypotheses test:
\begin{equation}
H_0: \tau_1 = \tau_2 = ... = \tau_a = 0
\end{equation}

\begin{equation}
H_1: \tau_i \neq 0
\end{equation}    
  </div>
  <div class="column_right">
  <img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-09 100429.png" style ="float: right" HSPACE="10" VSPACE="10"/>
  </div>
</div> 

<br>
In the effects model Each observation y<sub>ij</sub> can be represented by an overall mean, &mu;, plus the effect of the ith treatment, $\tau_i$, plus a random error, $\epsilon_{ij}$. The effects model is not the only model to be used to represent the data. However, it has some intuitive appeal in that the average &mu; is a constant, and the treatment effects $\tau_i$ represent the deviation from this constant when the specific treatments are applied. This model is called `single factor analysis of varianc`e or `one-way ANOVA`. As the treatment effects can be considered as a deviation from the overall mean, The hypothesis test for the one way analysis of variance can be expressed in terms of the treatment effect $\tau_i$. In the null hypothesis $\tau_i$ is equal zero for every i. That is the effect of the factor is zero, there is no deviation from the overall mean. In the alternative hypothesis H<sub>1</sub> $\tau_i$ is different from zero for at least one i, meaning the cotton content affects the tensile strength, at least at one level of cotton content. 


---
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<script>
    MathJax = {
        chtml: { displayAlign: 'left' }
    };
</script>