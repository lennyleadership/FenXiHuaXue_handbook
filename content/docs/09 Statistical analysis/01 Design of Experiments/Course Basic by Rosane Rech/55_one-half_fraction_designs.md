---
weight: 55
title: 55 One-Half Fraction Designs
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
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 224515.png" HSPACE="10" VSPACE="10"/>  
</div>
Let's take a look at the one-half fraction designs. Consider that we have three factors of interest. The complete design involves two in the power of three, eight runs. However, imagine that it is not possible to perform the eight runs. We have a limitation of budget or time or raw material or anything else. The solution then is to run a one half fraction of the two in the power of three design that are four treatments and the question is how to choose these four treatments? We are going to use the table of plus and minus signs of the two the power of three design to help us in choosing the treatments. In a way similar to splitting the design in blocks, we are going to use the factorial effect of the highest order interaction, in this case ABC, to choose the treatments.  
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 225212.png" HSPACE="10" VSPACE="10"/> 
</div>
Let's then start by choosing the treatments with a plus sign in the ABC column treatments a, b, c, and abc. In this case, ABC is called the generator or the word of the design and looking carefully, we are going to realize that in this particular design the ABC column is equal to the identity column with only plus signs; and the relation identity equal to ABC is called <u>the defining relation</u> of the design.
</div> 
 
<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 225523.png" HSPACE="10" VSPACE="10"/> 
</div>
Let's now take a look in the contrasts in this design. <u>The contrast of the main factor A</u> <i>C<sub>A</sub></i> is given by a minus b minus c plus abc. <u>The contrast of B</u> <i>C<sub>B</sub></i> by minus a plus b minus c plus abc, and <u>the contrast of C</u> <i>C<sub>C</sub></i> minus a minus b plus c plus abc. Now <u>the contrast of the interaction AB</u> <i>C<sub>AB</sub></i> is given by minus a minus b plus c plus abc, and this one is equal to <u>the contrast of C</u> <i>C<sub>C</sub></i> . In this design <u>the contrast of the interaction AB</u> <i>C<sub>AB</sub></i> is equal to <u>the contrast of the main factor C</u> <i>C<sub>C</sub></i> . For <u>the contrast of AC</u> <i>C<sub>AC</sub></i> minus a plus b minus c plus abc, it is equal to <u>the contrast of B</u> <i>C<sub>B</sub></i> , and in the same way <u>the contrast of the interaction BC</u> <i>C<sub>BC</sub></i> : a minus b minus c plus abc, is equal to the contrast of <u>the main factor A</u> <i>C<sub>A</sub></i> . 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 231232.png" HSPACE="10" VSPACE="10"/> 
</div>
Now we can use the contrasts to calculate the effects and the sum of squares. The effect of A is given by the contrast of A divided by 2 in the power of k minus p minus 1 times n, where n is the number of replicates. As the contrast of A is equal to the contrast of BC, the estimated effect of A is equal to the estimated effect of BC. We say that A and BC are aliases, and when we estimate the effect of A we are indeed estimating the effect of A plus the effect of the interaction BC. 
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 231433.png" HSPACE="10" VSPACE="10"/> 
</div>
It is impossible to separate the effect of A from the effect of BC. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:540px;">
  <img src = "/docs/images/Screenshot 2022-10-23 231543.png" HSPACE="10" VSPACE="10"/> 
</div>
In the same way, B and AC are aliases and C and AB are aliases. This is when we estimate the effect of B we are estimating the effect of B plus the effect of the interaction AC, and when we calculate the effect of C we are calculating the effect of C plus the effect of the interaction AB.  
</div> 
