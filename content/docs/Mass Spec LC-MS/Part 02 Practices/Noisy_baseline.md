---
authors: edited by Lenny Lin
categories:
date: "2022-07-07"
description: null
draft: false
lastmod: "2022-07-07"
series:
tags: [Baseline]
title: Noisy Baseline
toc: true
---


<!--more-->

**Situation**  
The attached picture is the baseline from an injection of blank ACN into 2.1x100 mm BEH column. The original mobile phase A in 0.05% TFA, but I found the baseline is very noisy. To make sure it is not the TFA problem, I used pure water instead.  

Mobile phase A: pure water   
Mobile phase B: ACN   
Detector: UV at 272nm @ 20Hz.  

The gradient is initial 98%A, 1.8min 98%A, 6min 35% A, 11min 10%A, 14.5min 10% A, 15min 98%A, 18min 98%A.  

It is very hard to believe that water and ACN will produce such a noisy baseline, especially for the "peak" at 9.7 minutes, which has a 0.02 UV absorbance. If scaled up the same gradient and run on a regular HPLC with a regular C18 column, it is fine.  

The column is clean and in good condition. I also try the same gradient on another BEH column, the same noisy baseline obtained.  

Anyone see this problem before?  