---
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: null
draft: false
lastmod: "2022-07-14"
series: 
tags: []
title: 19 Why Using Factorial Design?
toc: true
---




<!--more-->

Why using factorial designs? Which are the advantages of factorial designs? Let's suppose you have an experimental space with factors A and B, and we wish to maximize the response or outcome of the system. To make it easier, let's say that our response is the yield of a chemical process with temperature and pH. Our first approach is testing one factor at a time, and our first experiment will be at 30 degrees and pH 4, and the yield was 25. Now we're going to increase the temperature to 50 degrees and the yield was 15. Now we know that the temperature has a negative effect on the yield. So we'll go back to 30 degrees and test the pH. At 30 degrees and pH 6, the yield is 30, and we know that the pH has a positive effect on the yield. And this is probably our best result. What we have missed is that this system is non-linear and there is an interaction between the temperature and the pH, as shown by the contour lines. 
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-14 211650.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<mark>When testing one-factor-at-a-time, we miss the information about interactions</mark>. And in this case, we have missed the area of the highest yield in our experimental space. By doing a factorial design, with only one more experiment it is possible to increase the information on the true behaviour of the system. Now we know that the temperature has a positive effect at pH 6, but the temperature has a negative effect at pH 4. And the pH has a weak effect at 30 degrees and a strong effect at 50 degrees. A factorial design is always necessary when interactions may be present in the system to avoid misleading conclusions. To optimize a system using one-factor-at-a-time we need luck, to optimize a system using factorial designs we only need method. 