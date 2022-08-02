---
authors:
categories: null
date: "2022-03-10"
description: null
draft: false
lastmod: "2022-03-10"
series: null
tags: null
title: Part 1 Restek Retention Gaps
toc: true
---

<style type="text/css">
/* */
.column {
  float: left;
  width: 50%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}

</style>

<!--more-->

Part1: Using Retention Gaps in GC

Jaap de Zeeuw, International GC Consumables Specialist, Restek Corporation  


Guard columns and retention gaps are used widely in gas chromatography (GC). Many users have difficulty understanding the difference between these two products, even though there is a significant difference in application. Retention gaps mainly are used for focusing the sample components when introducing a large (liquid) sample directly onto the column. Guard columns are used to protect the analytical column from contamination. When using a retention gap system, the retention gap will also act as a guard column, but its primary function is to create a focusing effect.

Guard columns and retention gaps both must be coupled to the analytical column, and this connection introduces a potential point of risk. A new approach is to integrate the retention gap directly into the analytical column. By applying a “segment” coating technology the stationary phase can be deposited in a certain part of the column allowing a deactivated section at the beginning. Column coupling is not required and maintenance is greatly simplified. In Part 1 of this article we will explore retention gaps and build a foundation for a comparison to guard columns. In Part 2, we will review guard columns and discuss the new segment coating technology.


## Use of retention gaps

In today’s laboratory, GC methods must be simple, fast, and low detection limits are required. Besides that, sufficient precision must also be obtained. It all starts by introducing the sample in the smallest possible injection band and making the band migrate through the capillary with minimal loss of the target components. With on-column injection a liquid sample is directly introduced into the capillary column as a liquid while the capillary column is kept at a temperature 10-15°C below the boiling point of the solvent. During this process the sample components are spread in an unreproducible way over the first 20-100cm of capillary while the solvent is evaporating. Parameters like injection speed, carrier gas flow, temperature of solvent and column, type of solvent, and pressure all will affect the injection band width. Additionally, when nonbonded stationary phases are used, the direct contact with liquids will result in a distortion of the stationary phase film and very short column lifetime. The majority of today’s stationary phases, like the Rtx and Rxi phases, are immobilized by cross- and surface bonding techniques.

Figure 1: Retention gaps are used to focus components in a tight band at the beginning of the analytical column.  

<div class="row">
      <div class="column">
        <img width ="360" height= "200" alt='' src = "/docs/images/figure-article-gnar3272-01.jpg" />
      </div>
      <div class="column">
        <p> a) Sample introduction: liquid film of solvent and sample are deposited in the first length of capillary.<br /> 
b) Oven temperature is increased (temp. program run): solvent and target compounds are vaporized and travel unretained through retention gap.<br />
c) When target compounds come in contact with the stationary phase, they are refocused on the analytical column, resulting in a narrow initial band width.</p>
      </div>
</div>






For proper application of the on-column injection technique, the use of retention gaps is essential [1,2]. The retention gap consists of a 1-3m length of deactivated capillary that is positioned in front of the analytical column. All the processes described will still take place, but now the components are distributed over the retention gap. When the oven temperature is increased the sample components will start to move (there is very little retention…that’s why it’s called a retention “gap”). When reaching the analytical column, the components will focus in the stationary phase resulting in a narrowing of injection band width (Figure 1). As these retention gaps are mainly used for on-column injection, the inside diameter is usually 0.32mm up to 0.53mm since the needle of an on-column syringe must be able to enter the retention gap. For coupling the retention gaps to the analytical column, we need generally coupling devices that can deal with different diameter capillary tubing.


## Retention gaps and splitless injection

While on-column injection minimizes discrimination and provides the best quantitative data, especially for thermolabile components, it can be challenging to perform. Many laboratories will choose a splitless method for ease of use. For splitless injection we generally do not require a retention gap. The sample is injected in a hot injection port, evaporated, and transported with a carrier gas flow of approximately 1mL/min into the capillary. The amount of solvent vapor that enters the column per unit time is much smaller than with on-column injection. Although with splitless injection the oven temperature is also 10-15°C below the boiling point of the solvent, there is little chance of the solvent condensing. The high concentration of solvent entering the capillary column will cause a strong focusing effect for the components, generating a narrow injection band. If, in splitless injection, a method is used where the initial (injection) oven temperature is much lower than the boiling point of the solvent, the risk of solvent condensation (forming a liquid plug) will increase. This can cause unwanted broadening of the injection band. Coupling a retention gap will also fix this problem.  


## Wettability of the retention gap  

An important factor for good performance is the wettability of the retention gap surface. It is critical that the solvent spread evenly over the surface. This means that nonpolar solvents (hexane, methylene chloride, isooctane, benzene) require non/intermediate deactivated retention gaps and more polar solvents (methanol) will require polar deactivated retention gaps. If the polarity of the retention gap and solvent do not match, the solvent will form droplets inside the capillary. The carrier gas will “push” this droplet along the retention gap into the analytical column. The result is a broadened injection and possibly even peak splitting.


## Retention gaps for large volume injection  

Instead of injection of 1µl on a 1-2m retention gap, one can also inject much larger amounts on much longer retention gaps. Here we talk about large volume injection technique where retention gaps of 8-10m are used. Such retention gaps can be loaded with 100-200µl of sample. Injection must be slow to allow the solvent to evaporate while passing through the retention gap. With large volume injection, detection limits can be reduced a factor of 100. The technique requires some skill to optimize all the injection parameters. Additionally, the large volume retention gaps do pollute relatively quickly due to the large amounts of sample introduced.

Guard columns and retention gaps are useful tools to the practicing chemist and it is important to understand the difference between them. In Part 2 of this article we will review guard columns and discuss a new segment coating technology that allows retention gaps and guard columns to be built directly into the analytical column tubing. This new technology eliminates column coupling, substantially reducing analytical problems related to leaks and dead volume.


## References
1. Grob, K., Journal of Chromatography 237:15 (1982).  
2. Hinshaw J., LC/GC Europe 17(9): 460–466 (2004).