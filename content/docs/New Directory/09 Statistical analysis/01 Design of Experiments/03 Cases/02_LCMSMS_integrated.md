---
weight: 99
title: 
authors: Lenny Lin
categories: 
tags: []
description: null
draft: false
date: "2022-10-27"
lastmod: "2022-10-27"
series: 
toc: true
---

<!--more-->
---


A LC-MS/MS instrument composes of two components: a UPLC chromatography with a sample introduction system, and a triple quadruple mass spectrometer. A mass spectrometrist takes sensitivity, resolution, interference, and so on into consideration. They start with default instrumental parameters of each component, then fine-tune them to reach the best output they could get in a requested time frame.  These parameters could be: flow (*F*), gradient (*G*), and injection volume (*V*<sub>inj</sub>) of the UPLC chromatography; cone voltage (*E*<sub>com</sub>), collision energy (*E*<sub>col</sub>) of the mass spectrometer.

The method was optimized with respect to four responses: separation of peaks (Sep), peak area (*A*<sub>peak</sub>), length of the analysis (*T*) and the signal to noise ratio (S/N). A quadratic model, namely central composite face (CCF) featuring 29 runs was used instead of a less powerful linear model