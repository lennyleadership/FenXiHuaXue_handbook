---
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: How to choose a C18 column.
draft: false
lastmod: "2022-02-03"
series: 
tags: [Sensitivity]
title: Choose a C18 Column
toc: true
---

<figcaption><b>Figure </b>: </figcaption>
<img width ="360" height= "200" src = "/docs/images/"/>



<!--more-->

## Stationary phase


<iframe width="360" height="200" src="https://www.youtube.com/embed/xGzOzucTWr4" title="Why are there so many C18 columns" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

While every C18 column comes with a chain of 18 carbon atoms, there can be substantial differences in retention and selectivity depending on the exact column you use.

Initially, many tend to focus on <font color ="blue">carbon load</font> — the amount of carbon bonded to the surface of the particle — to determine whether there will be enough analyte retention, but there are many other factors to consider.

A traditional, end-capped C18 phase, which has about 20%<font color ="red"> carbon load</font>, is a great place to start if you’re not sure where to begin. <font color ="blue">End-capped C18 columns have the advantage of offering the highest hydrophobic retention among C18 phases</font>, while limiting other chromatographic interactions, due to end-capping and <font color ="blue">high surface coverage</font>.

But, what if your mobile phase contains a high percentage of water or your analytes are more polar? Under highly aqueous conditions, a traditional C18 column will undergo a phenomenon known as “phase dewetting”. When this occurs, the hydrophobic C18 chains repel water out of the particle pores, which limits analyte access to the stationary phase. So, in this case, <font color ="blue">an aqueous C18 column</font>, which has about <font color ="blue">15% carbon load</font>, is recommended. <font color ="blue">These phases are compatible with 100% aqueous mobile phases and also provide more retention for polar molecules that need an extra boost</font>. This extra retention comes from a polar modification of the phase that also makes it 100 % water compatible.<a href="#section1">[1]</a>  

Another factor to consider is <font color ="red">pH</font>. While low pHs can improve peak shape and the selectivity of a separation, these highly-acidic conditions can irreversibly damage your stationary phase. <font color ="blue">C18 phases with sterically protected ligands</font> excel in low pH environments.

These bulky side chains protect the phase from being removed from the surface under acidic conditions, but also allows some extra polar interactions of your analytes with the silica surface for unique selectivity. These assets make them perfect candidates for multiclass and pesticide analyses.

So, is a C18 a C18? As you can see, there are many differences between C18 columns, and each have their own advantages. So, rather than selecting one you may be more familiar with, it’s worth taking the time to consider the needs of your analysis before making a choice.


## Column Dimensions


<iframe width="360" height="200" src="https://www.youtube.com/embed/qL6HiMCiJmI" title="Choosing LC Column Dimensions" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

HPLC column dimensions are an important selection during method development as they impact the efficiency, sensitivity, and speed of your analysis. efficiency (refer to the following equation) is directly proportional to column length. This approach has its limitations as doubling column length increases resolution, but only by a factor of 1.4 while also significantly increasing back pressure.   

$
\textrm{efficiency} &Proportional;  \frac{\textrm{length}}{\textrm{particle &nbsp; size}}
$

Short column lengths, such as 50 mm, will give short run times and are ideal for gradient analysis. Long column lengths, such as 250 mm, have more resolving power, but come with the cost of longer analysis time and increased back pressure. When considering your column’s inner diameter, it is important to keep your mode of detection in mind. RI, fluorescence, or UV detectors can handle much higher flow rates than LC-MS. <mark>Conventional LC-MS flow rates are in the range of 0.3-0.6 mL/min</mark>. These flow rates pair well with 2.1 mm and 3.0 mm ID columns. Additionally, <mark>as column diameter is reduced, sensitivity can be improved several fold</mark>, assuming mass on column is kept constant and your instrument is optimized for low-volume columns.  


## Particles of stationary phase <a href="#section2">[2]</a>


<iframe width="360" height="200" src="https://www.youtube.com/embed/cPdg8b0NbV0" title="Choose Your LC Particle" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<font color ="red">Fully porous or superficially porous</font>? 1.8 or 2.7 µm?  90 or 300 $\mathring{A}$? These are only a handful of the choices that are available when you are choosing your LC particle. <font color ="blue">Superficially porous particles</font>, such as Raptor, <font color ="blue">feature a solid, impermeable core enveloped by a thin, porous layer of silica that decreases the diffusion path and reduces peak dispersion</font>. This, in combination with other unique properties resulting from the solid core, allows the use of a 2.7 µm superficially porous particle to achieve the performance of a sub-2 µm fully porous particle while generating less backpressure. If that’s the case, why even consider fully <font color ="blue">porous particles? These particles have more surface area per gram, allowing both additional retention for poorly retained compounds and the ability to inject more mass on column compared to superficially porous particles</font>.

Let’s also consider <font color ="red">particle size</font>. For the same column dimension, if the particle size is reduced by half, the plate number doubles.  However, backpressure also increases by a factor of four. Keeping this in mind, the pressure capabilities of your instrumentation should align with your choice in particle size. Pore size is often overlooked when selecting an LC particle. Small-pore particles have pore sizes ranging from 60–150 $\mathring{A}$ and perform well during separations of small molecules that are less than approximately 1,000 Da. Large-pore particles tend to be used for separation of larger molecules such as proteins. As a general rule, the pore size should be at least three times the size of hydrodynamic diameter of the molecule for easy access to the pores.

Before choosing the particle for your next analytical column, consider the size of your target analytes and whether you need speed, backpressure restrictions, sample capacity, or retention in order to effectively pair your column with your analysis.


## Particle size and pore size 

<figcaption><b>Figure 1</b>: Particle size and pore size</figcaption>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-02-04 095136.png"/>


**<font style="text-transform:uppercase;">Particle size</font>** is the average particle size of the packing in the HPLC column.   

The standard particle size for HPLC columns was 5 µm for a long time, until the mid-1990s, when 3.5 µm became popular for method development. More recently, packings with sub 2.3 µm , including 1.8 µm were developed.

**<font style="text-transform:uppercase;">Pore size</font>** is the average size of a pore in a porous packing.  The pore size of the packing material in your HPLC column is important, since the molecules must 'fit' into the porous structure in order to interact with the stationary phase.  


## How superficially porous particles are synthesized? <a href="#section3">[3]</a>

A coacervation method was reported on a poster by Agilent in 2013 which is used to synthesize <font color ="blue">totally porous</font> silica particles with <font color ="blue">a very narrow particle size distribution</font>.  In the synthesis, a mixture of urea, formaldehyde, and colloidal silica is coacervated under acidic conditions to form spherical particles. The particles are calcined to remove the polymer and then sintered at higher temperature to strengthen the particles.  Agilent modified this method to synthesize <font color ="blue">superficially porous</font> particles (Poroshell 120), in which urea/formaldehyde and sol particles are coacervated around the surface modified solid silica cores that are also added into the coacervation reaction.This procedure is much simpler than the multilayer/multi-multilayer technology as the shell is formed in one step. The critical step is to modify solid core surface with the right chemistry prior to coacervation so that the core surface has a similar chemical reactivity as that of the urea/formaldehyde polymerization. The simpler process leads to a very narrow particle size distribution and more consistent batch-to-batch reproducibility.

Simplified procedure of preparing Poroshell 120.  

1. Core preparation:  
1) 500-600 nm nanoparticles are prepared by modified Stöber process  
2) Cores are continuously grown by adding solutions containing TEOS, ethanol, ammonia, and water into the reaction mixture until they reach the desired size.  

2. Core surface modification:  
1) The cores are bonded with urea-silane first.  
2) The core surface is further modified by grafting urea/formaldehyde polymer, making the surface the same chemical reactivity as coacervation chemistry.  


<figcaption><b>Figure </b>: Core Surface Modification Process as a Key for Success of Coating</figcaption>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-02-04 103015.png"/>


3. Coacervation:
1) The surface modified cores are added into the coacervation mixture of sol particles, urea, formaldehyde under acidic condition. Urea and formaldehyde polymerize and form coacervated particles with the sol particles and the cores, The coating is formed at one step.  
2) The polymers are removed by calcination, and the particles are sintered at elevated temperature and processed to the end.  


<figcaption><b>Figure </b>: Coacervation</figcaption>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-02-04 103343.png"/>


<figcaption><b>Figure </b>: Production Batch-to-Batch of Poroshell 120 over a Two-Year Period </figcaption>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-02-04 103705.png"/>

For further reading on coacervation process, here is a paper published in 2015, <a href = "https://pubmed.ncbi.nlm.nih.gov/26342871/#affiliation-1">Synthesis and optimization of wide pore superficially porous particles by a one-step coating process for separation of proteins and monoclonal antibodies</a> by Wu Chen at Agilent.  

For further reading on layer-by-layer process, here is a paper published in 2014, <a href = "https://pubmed.ncbi.nlm.nih.gov/24856904/">Core-shell particles: preparation, fundamentals and applications in high performance liquid chromatography</a> by Richard Hayes et al. at University of Liverpool, UK and Thermo, UK.  






<p id="section1">[1] WWP2</p>
<p id="section2">[2] <a href="https://www.chromtech.com/pore-size-vs-particle-size-in-hplc-columns">The section comes from a Chromtech source</a></p>
<p id="section3">[3] <a href="https://www.agilent.com/cs/library/posters/public/2013_HPLC_Wu_Chen_Synthesis_of_Superficially_Porous_Particles.pdf">This section comes from an Agilent source</a>


___
<figcaption><b>Figure </b>: </figcaption>
<img width ="360" height= "200" src = "/docs/images/"/>
