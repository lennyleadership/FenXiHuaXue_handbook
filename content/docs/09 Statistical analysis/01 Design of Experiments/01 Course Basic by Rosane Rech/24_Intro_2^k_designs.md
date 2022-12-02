---
weight: 24
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: null
draft: false
lastmod: "2022-07-09"
series: 
tags: []
title: 24 Introduction to 2^k Designs
toc: true
---




<!--more-->

`The 2 in the power of k` factorial designs are special cases of the general factorial design, where we have k factors that are being studied at two levels each. 
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-14 222859.png" style ="float: left" HSPACE="10" VSPACE="10"/>
These factors can be numeric like temperature, pH and concentration or can be categorical or qualitative, like two different procedures or the presence or absence of a component. Each one of these factors is tested at two levels each: the low level and the high level.   

Let's recall the example of the previous section when we had the effects of the route and the hour of the day when the total time to commute from home to work. We studied two leaving times, 7 a.m. and 8 a.m. and two routes, route 1 and route 2, in the total commute time in minutes. The leaving time is a numeric factor: I can leave 7 a.m., I can leave 8 a.m, or I can leave any time between seven and eight, like 7:30. However, the route is a categorical factor: I can use either Route 1 or Route 2. There is nothing between. There is no route 1 and 3/4.   

If the factors are analyzed at two levels each, a complete replicate of the design requires `2 in the power of k runs`. That's why it is called `two in the power of k factorial designs`. 
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-14 223321.png" style ="float: left" HSPACE="10" VSPACE="10"/>
Let's take the example of two factors: temperature and substrate concentration, the design will involve 4 experiments, k is equal 2. If I add a third factor, like the pH, the temperature-substrate design will be tested at pH 5 and ph 7.5, If I add a third factor, like the pH, the temperature substrate design will be tested at pH 5 and pH 7.5, And I will have 8 experiments: `2 in the power of 3`. If I add a fourth factor, like the stirring rate, the eight experiments of the pH, temperature and substrate design will be tested at the two stirring rates: 200 rpm and 400 rpm; and I have 16 experiments: 2 in the power of 4.   

Finally, if I study two types of substrate, like glucose and sucrose, the 16 experiments will become 32, `two in the power of five`. In this example, we have four numerical factors temperature, substrate concentration, pH and stirring rate, and one categorical factor, the substrate type. The substrate can be either numerical or categorical. If I am studying the substrate concentration, I have a numerical factor. If I am studying the substrate type, I have a categorical factor. 
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-14 223638.png" style ="float: left" HSPACE="10" VSPACE="10"/>
The 2 in the power of k factorial designs are very useful in the early stages of the work when we have many factors to be investigated, they are called `factor screening experiments` and <mark class = "lemon">they are usually followed by optimization designs</mark>. 
