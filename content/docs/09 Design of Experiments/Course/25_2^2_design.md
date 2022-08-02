---
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: null
draft: false
lastmod: "2022-07-09"
series: 
tags: []
title: 25 The 2^2 Design
toc: true
---




<!--more-->

To illustrate the `2 in the power of k designs` we're going to start with the most simplest case That is the two-factor design: the 2 in the power of 2 factorial design. In this example, we're going to evaluate the effect of the concentration of the substrate, factor A, and the concentration of the enzyme, factor B, on the yield of an enzymatic reaction. Both substrate and enzyme are tested at their low levels and high levels ,for substrate: Fifteen and twenty five grams per liter. And for enzyme, one and two grams per liter. The table shows the combination of low and high levels, making the four treatments of this design. The table shows the combination of low and high levels, making the four treatments of this design. In the first line we have A and B at low level, substrate and enzyme at low level; in the second line, substrate that high level and the enzyme at low level; the third line, low and high; And the last experiment, both of them at their high levels. 
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-14 225144.png" style ="float: left" HSPACE="10" VSPACE="10"/>
To generalize this system, we are going to code the low level with -1 and the high level with +1. o generalize this system, we are going to code the low level with -1 and the high level with +1. This way, the table now shows the natural factors and the coded factors. Factor A, substrate, became x_A tested at -1 and +1, where -1 is 15 and +1 is 25 g/L. tested at -1 and +1, where -1 is 15 and +1 is 25 g/L And Factor B, the enzyme, x_B, where -1 and +1 are 1 and 2 g/L. This experiment has 3 replicates. Then we have the total number of runs as 2 the power of k times n, where n is the number of replicates, 2 in the power of 2 times 3: 12 runs. as 2 the power of k times n, where n is the number of replicates, 2 in the power of 2 times 3: 12 runs. It is important to point out that the order in which the 12 runs were taken is random. This is a completely randomized experiment. In the next section we are going to learn how to deal with no randomized designs, but for now, all the statistical approach is valid only for completely randomized designs. 