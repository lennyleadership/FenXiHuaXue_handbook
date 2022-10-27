---
weight: 1
title: Introduction
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

## The benefit of design of experiments 

A mass spectrometrist performs numerous experiments to find solutions to many aspects of a LC-MS/MS method, such as specificity, matrix effect, sensitivity, resolution, recovery, interference, and so on.  They would firstly do some experiments to explore potential opportunities to get the direction of solutions, then optimize instrumental parameters to fine-tune them to achieve the expected method performance.  The design of experiments (DoE) is a methodology for the mass spectrometrist in the exploration and optimization stages to control errors among experimental replicates, reveal the interactions between instrumental parameters, screen out insignificant parameters, and perform less number of experiments.  The decision of planning the new experiment at the next step is backed up by the statistical analysis of previous experiment.  As a result, the mass spectrometrist would have a clear direction of performing experiments in developing a method; gain better inside out of instrumentation along the way; be proficient to develop more methods.


## The techniques of design of experiments

The mass spectrometrist could encounter the following questions:   
1) Select the best solid phase sorbent among some potential candidates.  Careful experiment plan with one-way ANOVA would be a solution.  When different washing solvents or eluting solvents are involved, two-way ANOVA will alter one-way ANOVA.
2) Fine-tune the multiple ESI parameters of the mass spectrometer.  The fractional factorial design would be a solution.  The mass spectrometrist starts off with an initial set of parameters, pick a new interested change (level) of each parameter.  Instead of performing experiments of the combination of all levels of parameters, they will do experiments of a portion of the combination. 



## The commercially available software
Some software for design of experiments were mentioned in research papers, such as:

<a href = "https://www.statgraphics.com/centurion-overview" target="_blank" rel="noopener noreferrer">Statgraphics Centurion XVI</a> (Statgraphics Technologies, Inc.)


## Application to LC-MS/MS

A LC-MS/MS instrument composes of two components: a UPLC chromatography with a sample introduction system, and a triple quadruple mass spectrometer. A mass spectrometrist takes sensitivity, resolution, interference, and so on into consideration. They start with default instrumental parameters of each component, then fine-tune them to reach the best output they could get in a requested time frame.  These parameters could be: flow (*F*), gradient (*G*), and injection volume (*V*<sub>inj</sub>) of the UPLC chromatography; cone voltage (*E*<sub>com</sub>), collision energy (*E*<sub>col</sub>)

## The workflow

