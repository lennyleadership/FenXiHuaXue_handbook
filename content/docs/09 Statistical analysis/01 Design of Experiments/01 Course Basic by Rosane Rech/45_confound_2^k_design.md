---
weight: 45
title: 45 Confounding a 2^k Design in Blocks
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
Section 7: Blocking a Factorial Design

<!--more-->
---

We have just seen that when it is not possible to **run a factorial design in homogeneous conditions, we can run `each replicate` in a block**. However, sometimes even a complete replicate doesn't fit in one block.  
<div class = "row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 183242.png" style ="float: left" HSPACE="10" VSPACE="10"/>
In this case, we can use a technique called `confounding` to split the complete replicate in two or more blocks.  The determination of confounding means that certain effects, usually high-order interactions, will be indistinguishable, or confounded with the blocks.
</div>
<div class = "row">
<img width ="180" height= "100" src = "/docs/images/Screenshot 2022-08-04 191940.png" style ="float: left" HSPACE="10" VSPACE="10"/>Let's take the following example. Imagine a single replicate of a <b>2<sup>2</sup></b> design, we have four treatments. (1), a, b and ab. However, we have a limitation. The equipment allows only two runs at a time. This way we have to split the four treatments in two blocks and each set of two runs will be one block. But how can we divide four treatments in two blocks? 
</div>
To help with doing a smart choice we are going to use the table of plus and minus signs for the <b>2<sup>2</sup></b> design. As the name says, the table of plus and minus signs shows the plus and minus signs of the treatments for calculating the factorial effects of the main factors and interactions.  
<div class = "row">
<img width ="270" height= "150" src = "/docs/images/Screenshot 2022-08-04 184301.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="270" height= "150" src = "/docs/images/Screenshot 2022-08-04 184115.png" style ="float: left" HSPACE="10" VSPACE="10"/>
</div>

<img width ="270" height= "150" src = "/docs/images/Screenshot 2022-08-04 184344.png" style ="float: left" HSPACE="10" VSPACE="10"/>

The first column presents the treatments. In the second column we have the identity column with only plus signs; and then we have the main effects columns. In this case, factor A and factor B. The plus and minus signs in this main effect columns are the same ones of the coded variables. For factor A the treatments were a is at high level, a and ab, have a plus sign, and the treatments where A is at low level, treatments (1) and b, the treatments have a minus sign. And the same applies for factor B. A is at low level, treatments one and B, the treatments have a minus sign. And the same applies for factor B. Now, the interaction AB. The signs of the column AB can be given by the multiplication of the signs of factor A and factor B for each treatment.  

<div class="row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 190649.png" style ="float: left" HSPACE="10" VSPACE="10"/>
For treatment (1): minus times minus is a plus. For treatment a plus times minus is a minus; for B, minus and plus is a minus; and AB, plus plus we have a plus. 
</div>


<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 192800.png" style ="float: left" HSPACE="10" VSPACE="10"/>  
As you have probably guessed`already, the table of plus and minus signs is used to calculate the contrasts. Contrast of A (<em>C<sub>A</sub></em>) is given by ab plus a minus b minus (1). Contrast of B (<em>C<sub>B</sub></em>): ab plus b minus b minus one; and contrast of AB (<em>C<sub>AB</sub></em>): ab plus one minus a minus b. When we calculated the contrast of AB some lessons ago, I haven't explained how the treatment signs were chosen, but now you know it. They come from the table of plus and minus signs. 


Let's now split the treatments in two blocks.  
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 192624.png" style ="float: left" HSPACE="10" VSPACE="10"/>
As a first attempt, let's use the order in the table to divide the treatments. In `block one` we will have treatment (1) and treatment a, and then `block two`: treatment b and treatment ab. `The contrast of the blocks` (<em>C<sub>Block</sub></em>) can be calculated by the difference between the blocks. In this case ab plus b, minus a minus (1). 

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 202157.png" style ="float: left" HSPACE="10" VSPACE="10"/>
If you look carefully at `the contrast of the block` (<em>C<sub>Block</sub></em>) is equal to the contrast of the main factor B, meaning that the blocks are confounded with factor B. We cannot distinguish the effect of the blocks from the effect of factor B. Confounding the blocks with main effects is, by far, the worst way of splitting a design. **Blocks must never be confounded with main effects**. 
<br>  
Then how can we do with? How can we divide these four treatments in two blocks? If we cannot confound the blocks with the main effects, in this case, the only choice that we have is confound the blocks with the interaction AB, meaning that we are going to make the contrast of the blocks to be equal to the contrast of AB.  
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 202430.png" style ="float: left" HSPACE="10" VSPACE="10"/>
Thus block one will be formed by treatments (1) and ab, the treatments with the plus sign in the AB column; and block two by treatments a and b, the treatments with the minus sign in the AB column. Now the contrast of the blocks are ab plus (1) minus a minus b, the same contrast of the interaction AB. Now the blocks are confounded with the interaction AB and not with a main effect.  
