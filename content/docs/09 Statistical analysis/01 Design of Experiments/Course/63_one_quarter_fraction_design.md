---
weight: 63
title: 63 One-Quarter Fraction Design
authors: edited by Lenny Lin
categories: 
tags: []
description: null
draft: false
date: "2022-10-24"
lastmod: "2022-10-24"
series: 
toc: true
---
Section 9: Highly Fractionated Designs 

<!--more-->
---

     

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 133324.png" HSPACE="10" VSPACE="10"/> 
</div>
For a large number of factors, it is useful to use a smaller fraction of a 2^k design.  Let's consider, for instance, a one-quarter fraction of the 2^5 design, namely 2^(5-2) design.  To build the one-quarter design, the first step is to write down a basic design consisting of the runs associated with a full factorial in k-2 factors.  In the case of a 2ˆ(5-2) design, it is a full 2^3 design with eight runs. So here we have our  well known full 2^3 design with the eight runs. The next step is to write the two additional columns, D and E, by using the design generators. But how to choose the design generators?  Let's use the highest order interaction ABC to generate column D:  the signs of column D are obtained by the product of the signs of columns A, B, and C.  And finally, we need to write column E. As we now have a new highest order interaction,  let's use it for column E: the signs of column E will be the product  of columns A, B, C, and D. Clearly, we have a problem:  column E has only positive signs! 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 133549.png" HSPACE="10" VSPACE="10"/> 
</div>
Why? In one-quarter or smaller fractional designs,  we must use more than one design generator or identity to write the columns, and in  these cases, all combinations between the design identities are also identities. In this example,  we have identity I3 that results from the product between identity I1 and identity I2.  Now we know why column E is the third identity in this design.  
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 133721.png" HSPACE="10" VSPACE="10"/> 
</div>
So how to choose the design generators for one-quarter or smaller fractional designs?  The truth is we don't choose.
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 133958.png" HSPACE="10" VSPACE="10"/> 
</div>
there are several published designs with the highest design  resolution possible for a certain combination of a number of factors and a number of runs; also,  all DoE software have specific functions to do it. The following table shows some examples of  fractional designs, their design generators, and resolution.  Choosing a fractional design is a compromise among the number of factors we wish to study,  the number of tests we can perform, and the type of information we aim to get.
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 134103.png" HSPACE="10" VSPACE="10"/> 
</div>
As a general rule, the higher the resolution, the better.  Resolution III designs have main factors aliased with two-factor interactions, making it impossible to distinguish between them and potentially resulting in misleading conclusions. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-24 134228.png" HSPACE="10" VSPACE="10"/> 
</div>
In resolution IV designs, we can easily distinguish the significant main factors;  however, the two-factor interactions are aliased to each other. They can be handy as a screening  experiment to choose, for instance, which factors will be used in an optimization design.
</div> 



<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/imagesScreenshot 2022-10-24 134342.png/" HSPACE="10" VSPACE="10"/> 
</div>
And finally, we have resolution V and higher designs. In these,  we can draw reliable conclusions on both main effects and two-factor interactions.  
</div> 

<br>Let's now see how to use R to build two-level fractional designs.  Please download the txt file with the R code, and let's jump to R.
