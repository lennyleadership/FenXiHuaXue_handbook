---
weight: 1
title: "DoE Approach: ESI of LC-MS/MS Optimization"
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

## The Challenges of Developing a LC-MS/MS Method 

A mass spectrometrist performs numerous experiments to find solutions to many aspects of a LC-MS/MS method, such as specificity, matrix effect, sensitivity, resolution, recovery, interference, and so on.  The design of experiments (DoE) is a tool for the mass spectrometrist to plan, perform experiments, interpret data, and get output effectively.

A LC-MS/MS instrument composes of two components: a UPLC chromatography with a sample introduction system, and a triple quadruple mass spectrometer. A mass spectrometrist takes sensitivity, resolution, interference, and so on into consideration. They start with default instrumental parameters of each component, then fine-tune them to reach the best output they could get in a requested time frame.  These parameters could be: flow (*F*), gradient (*G*), and injection volume (*V*<sub>inj</sub>) of the UPLC chromatography; co

We adjust the ESI (electrospray ionization) parameters of a LC-MS/MS to increase the sensitivity of analytes during the method development and validation stage.

There are many parameters, such as: gas temperature, gas flow, sheath gas temperature, sheath gas flow, capillary voltage, nozzle voltage, and nebulizer pressure. 


## How to optimize the ESI parameters?
two approaches:  
1) one parameter at a time.  
It is empirical, but it overlooks the interactions between parameters.  The design of experiments approach can overcome it. Furthermore, when the lack of standards is a critical limitation for method development, the statistical approach is especially useful. [^1]   

2) Design of experiments approach


## Commercially available software
<a href = "https://www.statgraphics.com/centurion-overview" target="_blank" rel="noopener noreferrer">Statgraphics Centurion XVI</a> (Statgraphics Technologies, Inc.)

R packages

## Reference

[^1]: Moreiras, G., Leão, J. M., & Gago-Martínez, A. (2018). Design of Experiments for the Optimization of Electrospray Ionization in the LC-MS/MS Analysis of Ciguatoxins. <i>Journal of Mass Spectrometry</i>. doi:10.1002/jms.4281
