---
weight: 56
title: 56 Using the Defining Relation for the Aliases
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


<br>
<div class = "row">
  <div class= "column_right" style="width:450px;">
  <img src = "/docs/images/Screenshot 2022-10-24 101340.png" HSPACE="10" VSPACE="10"/> 
</div>
We actually don't need to write down the contrast to determine the aliases, we can use the defining relation of the design.
</div> 


<br>
<div class = "row">
  <div class= "column_right" style="width:450px;">
  <img src = "/docs/images/Screenshot 2022-10-24 101603.png" HSPACE="10" VSPACE="10"/> 
  <img src = "/docs/images/Screenshot 2022-10-24 101835.png" HSPACE="10" VSPACE="10"/> 
</div>
However, to do it we need first to learn some properties of the table of plus and minus signs. Any column multiplied by the identity column remains the same, the identity column has only plus signs, anything multiplied by plus one remains the same. Any multiplication of two different columns will give the interaction column like column A times column B is equal to the column AB. Any column multiplied by itself is the column to the square that is the identity because minus one to the square is plus one and plus one to the square is plus one. The resulting column has only plus signs this way for example column A times column AB is column A to the square times column B, A to the square is the identity times column B this is equal to column B A times AB is equal to B. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:450px;">
  <img src = "/docs/images/Screenshot 2022-10-24 102634.png" HSPACE="10" VSPACE="10"/> 
</div>
These properties can be used to determine the aliases without writing the contrasts. let's see how to do it for a two in the power of three minus one design with identity ABC. <b><font class = "font_upper">The aliases of A</font></b>: column A is equal to column A times the identity but in this design the identity is ABC then we have A times ABC that is A to the square times BC that is the identity times BC that is equal to BC A is alias to BC and when we calculate the effect of A we are indeed estimating the effect of A plus the effect of the interaction BC.  

In the same way, <b><font class = "font_upper">the aliases of B</font></b>: B is equal to B times the identity, B times ACB, B to the square times AC, identity times AC. We have that B is alias to AC. And when we calculate the effect of B, we are indeed calculating the effect of B plus the effect of the interaction AC. 

And finally for <b><font class = "font_upper">factor C</font></b>. C is alias to AB and when we calculate the effect of C we are indeed estimating the effect of C plus the interaction AB. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:450px;">
  <img src = "/docs/images/Screenshot 2022-10-24 102934.png" HSPACE="10" VSPACE="10"/> 
</div>
Let's now summarize this design. A <u>two in the power of three minus one</u> design with defining relation ABC involves treatments a, b, c, and abc. The aliases will be A with BC, B with AC, and C with AB. And the effects: the estimated effect of A is the effect of A plus the effect of BC, And in the same way, B is B plus AC, and C is C plus AB. This design with the treatments with plus signs in the ABC column is called <u>the principal fraction</u> of the design. 
</div> 

<br>
<div class = "row">
  <div class= "column_right" style="width:450px;">
  <img src = "/docs/images/Screenshot 2022-10-24 103321.png" HSPACE="10" VSPACE="10"/> 
</div>
Another way of doing a half-fraction of a two the power of three design is using <u>identity -ABC</u>. In this case, we are running the treatments with a minus sign in the ABC column. Treatments (1), ab, ac, and bc. By using the defining relation we can show that the aliases are: A with -BC, B with -AC, and C with -AB. meaning that when we estimate the effect of A, we are indeed estimating the effect of A minus the effect of the interaction BC. The effect of B minus the interaction AC, and the estimated effect of C is C minus the effect of the interaction AB. This design is called the complementary fraction of the design. 
</div> 