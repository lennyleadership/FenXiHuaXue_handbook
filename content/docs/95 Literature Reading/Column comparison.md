---
authors: Jufang Wu Ludvigsson, et al., Edited by Lenny Lin
categories: Category
date: "2021-12-30"
description: Core-shell Column Comparison
draft: false
lastmod: "2021-12-30"
series: 
tags: [eddy diffusion, longitudianl diffussion, resolution, Core-shell column]
title: Core-shell Column Comparison
toc: true
---

To Compare different core-shell columns.

<!--more-->

## History

Superficially porous particles or so-called core-shell particles have gained considerable attention in separation science applications in the latest decade. They were called pellicular particles at the beginning of their invention by Horvath. These particles are made of a solid silica core surrounded by a layer of porous silica with the intention to reduce the average diffusion paths of analytes across the particles. This type of particle was commercialized by Kirkland though the major breakthrough for modern LC was in 2007 when 2.7 &mu;m superficially porous particles appeared on the market. These particles were made of a 1.7 μm solid silica core and covered with a 0.5 μm porous shell, also referred to as fused-core particles. Since then, sub-3 μm and sub-2 μm core--shell particles have been commercially available from numerous manufacturers with slightly varying core to shell ratio. For instance, 2.6 &mu;m Kinetex particles from Phenomenex consist of 1.9 &mu;m solid core and a 0.35 μm porous silica layer.

## Pro

The exceptional efficiency of columns packed with core-shell particles is comparable with sub-2 μm fully porous particles, yet with much lower backpressure. This makes it practically useful for labs equipped only with conventional LC.

The high efficiency of core-shell columns lies mainly in the reduction of both the longitudinal diffusion B coefficient (-20 to -30%) and the eddy dispersion A term (--0%).

## Cons

1\) at ultra high pressure, the effect of frictional heating causing temperature gradients within the columns could be an issue.  
2) Meanwhile, the quality of column packing also plays a significant role for the performance of narrow bore columns. 3) The smaller the internal diameter of the column, the more critical the extra-column band broadening effects are. In other words, efficiency of columns of 3 mm inner diameter would be less affected by extra-column volume than the narrow bore columns. For Cortecs columns (Waters) of 1.6 m particles, 2.1 mm inner diameter were chosen as they have the same dimension as the fully porous BEH C18, 1.7 μm column (100 × 2.1 mm, tested for comparison).

Consequence, different core-shell columns could affect technology transfer aspects of methods.

## List of Core-shell C_18 Columns

<figcaption><b>Table 1</b>: Core-shell columns tested</figcaption>

<img src = "/docs/images/Screenshot 2021-12-27 155003.png"/>

## Column Characterization Protocols

1) PQRI methodology;  
2) NIST SRM 870 test;  
3) Modified Tanaka test;

Tanaka test assesses selectivity and performance differences between LC columns.

A set of <b>seven</b> selected substances is used to describe <b>retention factor, hydrophobicity, steric selectivity, and silanophilic properties</b>.

Good batch to batch reproducibility of columns are extremely important to develop a robust method for pharmaceutical analysis. <b>Four</b> selected active pharmaceutical ingredients (API) are selected to gain the insight of the batch-to-batch reproducibility of studied core--shell columns. For this test, not only retention factor, but also <b>column efficiency and peak shape</b> of these four APIs are compared for different batches of the same type column. The selected APIs are more representative for the real-life applications than Tanaka test probes. Hence Tanaka protocols were not used for the batch to batch reproducibility test in this study.


### Four API (Active Pharmaceutical Ingredients)

<figcaption><b>Table 2</b>: Structure and relevant pka value of four API</figcaption>

| Compound   | Structure                                                                     | pKa           |
|------------|-------------------------------------------------------------------------------|---------------|
| Metoprolol | <img src = "/docs/images/a17639-metoprolol.gif" width="50%" />                | 9.43          |
| Omeprazole | <img src = "/docs/images/Omeprazole_01.png" width="50%" />                    | 4.27 and 8.76 |
| Amlodipine | <img src = "/docs/images/Chemical-structure-of-amlodipine.ppm" width="50%" /> | 8.97          |
| Felodipine | <img src = "/docs/images/felodipine-structure.png" width="50%" />             | NA            |

### Tanaka Test Results
<figcaption><b>Table 3</b>: Tanaka test results and column back pressure</figcaption>
<img src = "/docs/images/Screenshot 2021-12-27 203946.png"/>

#### Conclusion
1) Kinetex EVO columns have lower retention factors for pentylbenzene and shape selectivity.  
2) Cortecs C18+ distinguish themselves in the high values (lilac) of $\alpha_{C/P}$ and $\alpha_{B/P}$ pH 2.7, which indicates the high acidic silanol activity of this stationary phase and low degree of end capping. This is surprising since Cortecs C18+ is claimed to have the same chemistry as CSH (charged surface hybrid) columns with permanent surface charge.  
3) Poroshell 120 Bonus-PR column is an outlier on the score plot, which is as expected as it is a non-C18 stationary phase. It is a combination of denselyreacted sterically-protected, diisopropyl-C14 groups covalently bonded through an embedded amide functionality to a silica support.    
4) Poroshell EC-C18, 2.7 &mu;m, Kinetex C18 2.6 &mu;m and Cortecs C18 1.6 &mu;m showed the best batch-to-batch reproducibility.
5) Core–shell columns in dimensions of 100×3 mm and of particles 2.6 to 2.7 &mu;m tested in this study do have better or at least the same efficiency compared with <b>fully porous</b> BEH C18, 1.7 &mu;m column, while the backpressure is much lower.  

### PCA Analysis

<img src = "/docs/images/Screenshot 2021-12-27 195414.png"/>
<figcaption><b>Figure 1(A)</b>: Score plot for all columns by Tanaka test results: PC1 (40%), PC2 (36%)</figcaption>


<img src = "/docs/images/Screenshot 2021-12-27 195820.png"/>
<figcaption><b>Figure 1(B)</b>: Loading Plot</figcaption>


<img src = "/docs/images/Screenshot 2021-12-27 200118.png"/>
<figcaption><b>Figure 2(A)</b>: Score plot for columns under isocratic elution (pH 3 and pH 7.4): PC1 (43%), PC2 (21%)</figcaption>


<img src = "/docs/images/Screenshot 2021-12-27 200315.png"/>
<figcaption><b>Figure 2(B)</b>: Loading Plot</figcaption>


<img src = "/docs/images/Screenshot 2021-12-27 201827.png"/>
<figcaption><b>Figure 3(A)</b>:  Score plot of all columns subjected to gradient elution test: PC1 (36%), PC2 (25%)</figcaption>


<img src = "/docs/images/Screenshot 2021-12-27 201516.png"/>
<figcaption><b>Figure 3(B)</b>: Loading plot (where AP for amlodipine,
FP for felodipine, _pH 7 is _pH 7.4, variables without pH indicated are those for pH 3.)</figcaption>

## Source

Jufang Wu Ludvigsson, et al., Core--shell column Tanaka characterization and additional tests using active pharmaceutical ingredients, J. Sep Sci., 2016, 39(23), 4520-4532