---
weight: 43
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: null
draft: false
lastmod: "2022-07-09"
series: 
tags: []
title: 
toc: true
---

`randomization` is the design technique that we can use to guard against unknown or uncontrolled nuisance factors.  
`blocking` is the design technique we can use to eliminate the effect of a knowed and controlled nuisance factor.

<!--more-->
---
In any experiment, the variability arising from `a nuisance factor` can affect the results. Nuisance factors are factors that probably affect the results, but we are not interested in their effect. Sometimes a nuisance factor is unknown and uncontrolled. We don't know that the factor exists, and it may even be changing levels while we are conducting the experiment. They are responsible for `the experimental error`. And **`randomization` is the design technique that we can use to guard against these nuisance factors**. That's why we have been working with `completely randomized designs`.   

However, sometimes `a nuisance factor` is known and can be controlled, like batches of a raw material. We know that they can affect the results, but we cannot choose one batch and use it forever. It's just going to finish eventually. And **`blocking` is the design technique we can use to eliminate the effect of a nuisance factor**. To illustrate the general idea, let's take the example of 2ˆ2 design where we evaluated the effect of the concentration of the substrate and the concentration of the enzyme on the yield of an enzymatic reaction. 
<div class="row">
  <div class="column">
  <figure>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-02 122134.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<figcaption><b>Figure 1</b>: Evaluate the effect of the concentration of the substrate and concentration of the enzyme on the yield of an enzymatic reaction</figcaption>
</figure>
  </div>
</div>
It was considered a completely randomized design, meaning that the order in which the twelve runs were made was random. Or, the 12 runs were made at the same time. However, let's suppose it's not possible to run the 12 assays at the same time. And running the 12 assays, one-at-a-time, in a random order will take too long. However, the experimental apparatus allows to run four assays at the same time. This way, instead of running all assays homogeneously, we are going to split the experiment,the 12 assays, in three blocks of four assays, and the complete replicate will be run in each block.  This way,the 12 assays, in three blocks of four assays, and the complete replicate will be run in each block.  This way, the variability, or noise, or experimental error, is not homogeneously distributed in the whole experiment anymore, but is concentrated in the blocks.  

<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-08-02 124847.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<figcaption><b>Figure 2</b>: Blocking a replicated 2<sup>k</sup> factorial design</figcaption>

This non-homogeneity will increase the mean squares of the error and impair the statistical analysis of the main factors and interactions we are interested in. To avoid this to happen, we are going to calculate the effect of the blocks in `the analysis of variance`. `The replicates` or `block`s will be the third factor in the experimental design. Let's use R-Studio to to analyze this 2ˆ2 blocked design. Please download the csv file with the data, the txt file with the R-code the txt file with the R-code and let's change to R to analyze it. 
