---
authors: Rick Lake, edited by Lenny Lin
categories: 
date: "2022-01-03"
description: Van Deemter Equation
draft: false
lastmod: "2021-12-27"
series:
tags: [particle size, columns, Band broadening, Van Deemter equation, resolution]
title: Chapter 02 Van Deemter Equation - Small Particle Size Column 
toc: true
---

How do small particle size columns increase sample throughput?

<!--more-->
---

The Van Deemter equation is an empirical formula describing the relationship between plate height (H, the length needed for one theoretical plate) and linear velocity (µ) (Figure 1).  The Van Deemter equation is governed by three cumulative terms: (<b>A</b>) eddy diffusion, (<b>B</b>) longitudinal diffusion, and (<b>C</b>) mass transfer. 

The plate height H is a measure of column efficiency. Smaller plate height values corresponds to greater peak efficiencies, as more plates, or analyte partitioning, can occur over a fixed length of column.  A loss in peak efficiency can be observed as a wider analyte band, and therefore, these three terms can be viewed as factors that contribute to band broadening.  

<b>Figure 1</b> illustrates the effect of these terms, both individually and cumulatively. <b>Eddy diffusion</b>, the <b>A</b> term, is caused by a turbulence in the solute flow path and is mainly unaffected by flow rate.   
<b>Longitudinal diffusion</b>, or difference, the <b>B</b>, term, is the movement of an analyte molecule outward from the center to the edges of its band. Higher column velocities will limit this outward distribution, keeping the band tighter.   
<b>Mass transfer</b>, the <b>C</b> term, is the movement of analyte, or transfer of its mass, between the mobile and stationary phases. Through this type of diffusion, increased flows have been observed to widen analyte bands, or lower peak efficiencies.  

<figcaption><b>Figure 1</b>: The Van Deemter Equation describes the relationship between column flow rate and peak efficiency, referred to as band broadening.</figcaption>
<img src = "/docs/images/figure-article-phar3267-01.jpg"/>  

Decreasing particle size has been observed to limit the effect of flow rate on peak efficiency—smaller particles have shorter diffusion path lengths, allowing a solute to travel in and out of the particle faster. Therefore the analyte spends less time inside the particle where peak diffusion can occur. <b>Figure 2</b> illustrates the Van Deemter plots for various particle sizes. We notice that as the particle size decreases, the curve becomes flatter, or less affected by higher column flow rates. Smaller particle sizes yield better overall efficiencies, or less peak dispersion, across a much wider range of usable flow rates.  

<figcaption><b>Figure 2</b>: Smaller particle sizes yield higher overall peak efficiencies and a much wider range of usable flow rates.</figcaption>
<img src = "/docs/images/figure-article-phar3267-02.jpg"/>


If we look at an empirically determined Van Deemter plot of efficiency versus flow rate, when using a 1.9µm particle size Pinnacle DB column (<b>Figure 3</b>), the benefit is apparent—column efficiency does not diminish when flow rate increases, as denoted by the relatively flat slope of the curve. Peak efficiency was comparable even when the flow was increased to 1mL/min. This illustrates the most considerable affect that small particles have on chromatographic separations—a much wider range of usable flow rates translates into significantly faster analysis times. This benefit, coupled with a shorter column length needed for similar resolution, allows much higher sample throughput, without the compromising the chromatographic quality of the analytical method.

<figcaption><b>Figure 3</b>: An empirically determined Van Deemter plot shows that column efficiency does not diminish as flow rate increases on a 1.9 µm particle size Pinnacle DB column — significantly reducing analysis time and increasing sample throughput.</figcaption>
<img src = "/docs/images/figure-article-phar3267-03.jpg"/>

___
Explain in my words: An analyte molecule moves along a column with three behaviour pattern: 1) turbulent diffusion (Eddy diffusion), 2) longitudinal diffusion, 3) mass transfer.

* Turbulent diffusion (涡流扩散): Solute molecules will take different paths through the stationary phase at random.[^1]
[^1]: https://en.wikipedia.org/wiki/Eddy_diffusion  

<iframe width="320" height=auto src="https://www.youtube.com/embed/p2KvzK81s2g" title="Fundamentals of HPLC 28 - Describing Eddy Diffusion" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>    

<iframe width=auto height=auto src="https://www.youtube.com/embed/Izg8Xd4Wsek" title="Fundamentals of HPLC 29 - Eddy Diffusion and Flow" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  


  
<figcaption><b>Figure 4</b>: Eddy Diffusion </figcaption>   
<img src = "/docs/images/Screenshot 2021-12-23 202120.png"/>  


<figcaption><b>Figure 5</b>: Eddy Diffusion</figcaption>
<img src = "/docs/images/Screenshot 2021-12-23 202323.png"/> 


<figcaption><b>Figure 6</b>: Eddy Diffusion</figcaption>
<img src = "/docs/images/Screenshot 2021-12-23 202556.png"/> 

Figure 4 - 6 are downloaded from http://www.ecs.umass.edu/cee/reckhow/courses/772/slides/772l14p.pdf.

<a href = "https://www.restek.com/row/technical-literature-library/articles/how-do-small-particle-size-columns-increase-sample-throughput/">Resource</a>  


* Longitudinal diffusion: Analyte diffuses out from the center to the edges. If the velocity of the mobile phase is high then it decreases the effects of longitudinal diffusion.  


<figcaption><b>Figure 7</b>: Longitudinal (Molecular) Diffusion</figcaption>
<img src = "/docs/images/Screenshot 2021-12-23 203557.png"/> 

A YouTube video ^[https://www.youtube.com/watch?v=wG5nDzKuGDU] ^[https://www.youtube.com/watch?v=gdaAassaAaA] explains the longitudinal diffusion. 

* Mass transfer: The analyte takes a certain amount of time to equilibrate between the stationary and mobile phase. If the velocity of the mobile phase is high, and the analyte has a strong affinity for the stationary phase, then the analyte in the mobile phase will move ahead of the analyte in the stationary phase. The band of analyte is broadened. The higher the velocity of mobile phase  is, the worse the broadening becomes.


<figcaption><b>Figure 8</b>: Mass transfer</figcaption>
<img src = "/docs/images/Screenshot 2021-12-23 203858.png"/> 


<figcaption><b>Figure 9</b>: Smaller particle sizes yield higher overall peak efficiencies and a much wider range of usable flow rates</figcaption>
<img src = "/docs/images/Screenshot 2021-12-16 123231.png"/> 

A YouTube video ^[https://www.youtube.com/watch?v=u7EPAPQDLlY] ^[https://www.youtube.com/watch?v=KXg4FrRiEq0] explains the mass transfer.

Source ^[https://www.restek.com/row/technical-literature-library/articles/how-do-small-particle-size-columns-increase-sample-throughput/]
