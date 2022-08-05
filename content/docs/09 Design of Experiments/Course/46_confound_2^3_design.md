---
weight: 46
title: 46 Confound a 2^3 Design
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

The same idea can be applied to confound a two in the power of three design in two blocks. Here we have the table of plus and minus signs for a two in the power of three design. We have the identity column with only plus signs, the columns with the main effects, with a plus sign for the high levels and the minus signs for the low levels. And then we have the columns of the interaction effects: column AB can be given by column A times column B, column AC by A times C, BC by B times C, And finally, the column of the three factor interaction ABC is given by column A times column B, times column C. 
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 204958.png" style ="float: left" HSPACE="10" VSPACE="10"/>
The signs of the three-factor interaction can be also given by column A times column BC, or column B times column AC or column C times column AB. be also given by column A times column BC, or column B times column AC or column C times column AB.   

Now, let's go to our problem. We need to run at two in the power of three design, eight treatments, but the experimental apparatus allows only four runs at the time. This way, we have to split the eight treatments in two blocks with four runs each. As a general rule, we will always confound `the highest-order interaction` with the blocks. In this case, the interaction ABC will be confounded with the blocks. We are going to make the contrast of the blocks equal to the contrast of ABC. 
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-04 205332.png" style ="float: left" HSPACE="10" VSPACE="10"/>
Then we are going to have one block with all the treatments that have a plus sign in the ABC column: treatments a, b, c and abc, and the other block will have all the treatments with a minus sign in the ABC column: treatments (1), ab, ac, and bc. Now the contrast of the blocks are equal to the contrast of ABC. 