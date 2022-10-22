---
weight: 3
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: Chromatographic Performance Evaluation
draft: false
lastmod: "2022-01-03"
series:
tags: []
title: Chromatographic Performance Evaluation
toc: true
---


<!--more-->

## Resolution

Resolution is defined as the distance between two adjacent peak apexes, divided by the average base width of both peaks. It is represented by the equation:

$ R = \frac{(T_2 - T_1)}{0.5(W_1 + W_2)} $



<img width="320" height=auto src = "/docs/images/Screenshot 2022-01-14 223344.png"/>


Resolution is dependant on three other variables, the column efficiency N, the capacity factor k’ and the selectivity α.

Decreasing N decreases the resolution because peak width increases. Increasing N increases resolution because peak width decreases.

Decreasing k’ sharpens the peaks but decreases resolution. Increasing k’ broadens the peaks but improves resolution.  

Increasing α increases resolution. One peak moves relative to the other. Likewise, decreasing α decreases resolution.


## Column Efficiency (N)

Column efficiency, or the theoretical plate count, is a measure of peak band spreading. The lower the level of band spreading, the higher the column efficiency and vice versa.

<b>Important</b>: The column efficiency figure quoted on the supplied certificate of analysis is actually the efficiency for the column AND HPLC system. If the efficiency calculation is repeated on a different instrument when the column is new, it is very likely that there will be a difference between the certificated value of N and your new calculated value of N. This difference is not due to the column but the instrument.  


<figcaption><b>Table </b>: Column Efficiency</figcaption>
<img width="320" height=auto src = "/docs/images/Screenshot 2022-01-14 224138.png"/>


## Tailing Factor (T)

Tailing factor is a measure of the symmetry of a peak. A peak’s tailing factor is measured using the following equation:

$T = \frac{W_{0.05}}{2f}$  
Where $ W_{0.05} = $ peak width at 5% height  
f = distance from peak front to apex point at the baseline  



<img width="160" height=auto src = "/docs/images/Screenshot 2022-01-14 225106.png"/>


## Capacity Factor (k)

Capacity factor is a measure of the retention of an analyte relative to the column void volume, $V_0$. It is measured using the following equation:

$ k = \frac{V_1 - V_0}{V_0} $

Where $V_0 =$ Column void volume  
$V_1 =$ Retention volume of peak



<img width="320" height=auto src = "/docs/images/Screenshot 2022-01-15 123928.png"/>


<b>Important</b>: The column void volume can be measured by injecting a compound that will be unretained by the column packing. Typical compounds used include uracil (RP) and toluene (NP).

Changes in capacity factor that occur both with standard and sample mixes are likely to be due to <font color = "blue">changes in the column, temperature or mobile phase composition</font>.  

Changes in capacity factor that occur only in the sample mix and not the standard mix are most likely to be due to the composition of the sample.  

Capacity factor is affected by <font color = "blue">changes in mobile phase, operating temperature, analyte retention characteristics and changes to the surface chemistry of the column</font>.  

<b>Note</b>: Capacity factor will change by up to 10% for a 5 °C rise in column temperature.  


## Selectivity ($\alpha$)

Selectivity is a measure of the relative retention of two adjacent peaks in a chromatogram. It can be calculated using capacity factors or retention volumes:  



<img width="320" height=auto src = "/docs/images/Screenshot 2022-01-15 125917.png"/>


$ \alpha = \frac{k_2}{k_1} = \frac{V_2 - V_0}{V_1 - V_0} $

Where $K_1 = V_1$ capacity factor  
 $K_2 = V_2$ capacity factor  
 $V_0 =$ void volume  
 $V_1 =$ peak 1 retention time  
 $V_2 =$ peak 2 retention time  
 
Selectivity can be affected by <font color = "blue">changes in mobile phase composition, temperature and column chemistry</font>.

Changes in selectivity that occur both with standard and sample mixes are most likely to be due to <font color = "blue">changes in the column, temperature or mobile phase composition</font>.

Changes in selectivity that occur only in the sample mix and not the standard mix are most likely to be due to the composition of the sample. 
 
 

## Source

https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf




____


