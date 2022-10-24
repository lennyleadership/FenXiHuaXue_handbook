---
weight: 54
title: 54 Introduction to Fractional Designs
authors: edited by Lenny Lin
categories: 
tags: []
description: null
draft: false
date: "2022-10-23"
lastmod: "2022-10-23"
series: 
toc: true
---
Section 8: Fractional Designs

<!--more-->
---
<div class = "row">
  <div class= "column_right" style="width:540px; height: auto">
  <img src = "/docs/images/Screenshot 2022-10-23 220931.png" HSPACE="10" VSPACE="10"/>  
</div>
A complete replicate of a 2 in the power of 5 design requires 32 runs, with a total of 31 degrees of freedom, from which 5 degrees of freedom are related to main effects, we have 10 degrees of freedom related to two factor interactions, and the remaining 16 degrees of freedom are related to higher-order interactions.  
</div>  

<br>
<div class = "row">
  <div class= "column_right" style="width:540px; height: auto">
  <img src = "/docs/images/Screenshot 2022-10-23 221506.png" HSPACE="10" VSPACE="10"/>  
</div>
When we have a 2 in the power of 6 design, we need 64 runs for a complete replicate, with a total of 63 degrees of freedom, from which 42 are related to higher-order interactions. In these cases, assuming that the high order interactions are negligible, the information on main effects and low-order interactions can be obtained by running only a fraction of the complete design.
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 221951.png" HSPACE="10" VSPACE="10"/>  
</div>
Fractional designs are widely used mainly as a screening experiments, that are experiments in which many factors are being considered and objective is to identify those factors that have a large effect on the response. The notation is 2 in the power of <em>k</em> minus <em>p</em>, where <em>k</em> is the number of factors and <em>p</em> is the number of times that the design was divided in half. For example, a 2 in the power of 4 minus 1 design means a 1/2 fraction of a 2 in the power of k design with 4 factors, in a total of eight runs. A 2 in the power of 6 minus 2 design means 1/4 of a 2 in the power of K design with six factors, with a total of 16 runs.  
</div>  

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 222554.png" HSPACE="10" VSPACE="10"/>  
</div>
There are some key ideas behind the fractional factorial designs. The first is the sparsity of effects principle, that we have already used in the single replicate designs: the systems are dominated mainly by main effects and low order interactions, so we can use the high order interactions to estimate the error. Then we have the projection property: fractional designs can be projected into stronger designs in the subset of significant factors. For example, a single replicate of a 2 in the power of 5 minus 1 design where two factors are not significant, becomes a replicated two in the power of three design.   
</div>  
 
<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 222730.png" HSPACE="10" VSPACE="10"/>  
</div>
And finally: the sequential experimentation it is possible to run 2 or more fractional designs to build, sequentially, a larger design, sometimes a complete design.   
</div>  
