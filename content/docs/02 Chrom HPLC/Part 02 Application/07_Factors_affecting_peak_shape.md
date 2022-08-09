---
weight: 7
authors: Agilent Webinar, Edited by Lenny Lin
categories: 
date: "2022-01-03"
description: Factors Affecting Peak Shape
draft: false
lastmod: "2022-01-10"
series: 
tags: [Peak Shape, Sensitivity]
title: Chapter 07 Choosing Columns and Conditions for the Best Peak Shape
toc: true
---


<!--more-->

## Elementary Knowledge of Peak Shape

### [How is peak shape measured?](https://learning.sepscience.com/hubfs/Technical%20Blogs/HPLC_37.pdf)

The tailing factor is determined by drawing a perpendicular line from the peak centre to the baseline of the peak. Then the peak width and the front half-width are measured for the peak at 5% of the height of the peak. The tailing factor is simply the entire peak width divided by twice the front half-width.  
  
The non-pharmaceutical world tends to use the asymmetry factor instead of the tailing factor to measure peak tailing. The asymmetry factor is based on the front and back half-widths of the peak, but these are measured at 10% of the peak height. The asymmetry factor is determined by dividing the back half-width by the front half-width.  


<figcaption><b>Figure </b>: USP Tailing Factor and Asymmetry Factor</figcaption>
<img src = "/docs/images/Screenshot 2021-12-16 094739.png" width="180" height="80"/>


### Problems with Peak Shape

<figcaption><b>Figure </b>: Problems with Peak Shape</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 150535.png"/>

## Factors affecting peak shape.

* Column
  * Silica type/acidity/metal content  
    * Fully hydroxylated silica and silica metal content  
    * Silica silanol ionization  
    * Hydrogen bonding with silica silanols  
  * column bonding  
    * End capping  
    * Type of bonded phase
  * Column packing
    * Pore size/particle size/particle morphology  
    * Formation of voids in the packed bed

* Mobile Phase
  * pH  
  * Buffers  
  * Temperature  
  * Organic modifiers  
  * Mobile phase additives (TEA, TFA, etc.)

* Connecting capillaries and fittings
* System
* Sample

<!--more-->


## Column: Silica Type/ Acidity/ Metal Content

<figcaption><b>Figure 1</b>: Fully hydroxylated and metal free silica reduces acidity</figcaption>
<img src = "/docs/images/Screenshot 2021-12-16 101449.png"/>


<figcaption><b>Figure 2</b>: Improve peak shape for basic compounds with high purity,
fully hydroxylated, low acidity silica such as Rx-SIL</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 132658.png"/>


<figcaption><b>Figure </b>: </figcaption>
<img src = "/docs/images/Screenshot 2022-01-19 093214.png"/>
[source](https://www.agilent.com/cs/library/eseminars/Public/Column_Choices_Feb2008.pdf)


<figcaption><b>Figure 3</b>: Improve peak shape with ZORBAX StableBond with Rx-SIL </figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 131945.png"/>


## Column: Silica silanol ionization

It is controlled by mobile phase. Ionized silanols ($\small{\textrm{SiO}}^-$) will ion-exchange with protonated bases ($\small{\textrm{R}}_3\small{\textrm{NH}}^+$) which can cause tailing and method variability. This occurs most often at mid pH where silanols are ionized. Some mobile phase additives can be added to the mobile phase to reduce these interactions.

$$
\textrm{SiO}^-\textrm{Na}^+ + \textrm{R}_3\textrm{NH}^+\quad \rightleftharpoons\quad \textrm{SiO}^-\textrm{N}^+\textrm{R}_3 + \textrm{Na}^+
$$


## Column: Hydrogen bonding with silica silanols

It is controlled by mobile phase. Unprotonated acids can compete for $\textrm{H}^+$ with protonated silanols. This can occur at low pH. Some mobile phase additives can be added to the mobile phase to reduce these interactions.

$$
\textrm{-SiOH}\ + \textrm{RCOO}^-\quad \rightleftharpoons\quad \textrm{-SiO}^-\, \textrm{  ...}\, \textrm{   H}^+\ +\ \textrm{...}\  ^-\textrm{OOCR}
$$


## Column: Column bonding and endcapping

* Bonded phases with endcapping
  * Most RP columns are endcapped.  
  * Eclipse XDB columns are double endcapped.  
  * Double and triple endcapping minimizes the number of unreacted silanols and potential peak tailing interactions.  
* Bonded phases with embedded polar groups
  * Bonus-RP provides unique silanol shielding reducing peak tailing for basic compounds
* Bonded phases for high pH
  * Extend-C18 is stable at high pH
  * Basic compounds can not ion-exchange with the silica thereby reducing peak tailing
* Bonded phases for high aqueous
  * SB-Aq is more “wettable” improving analyte interactions and peak shape 

  
### ZORBAX Bonding Technology

* All purpose phases  
  * StableBond  
  * Eclipe XDB  
  * Exlipse Plus  
* Rx-Silica support  
  * Ultra-pure  
  * Spherical, consistent pore size  
  * Fully-hydroxylated  
  * Sol gel maximizes strength and lifetime  
* Application targeted phases  
  * Bonus-RP  
  * Extend  


<figcaption><b>Figure </b>: Match Method pH and Column Choice - Choose the Best Bonded-Phase for Each pH Range</figcaption>
<img src = "/docs/images/Screenshot 2022-01-19 114907.png"/>


### ZORBAX StableBond Bonding

* Superior low pH stability – down to pH 1  
* Non-endcapped for selectivity and lifetime  
* Patented sterically protecting bonding  
* 5 different selectivities - C18, C8, CN, Phenyl, C3  
* Ideal for most sample types at low pH  


<figcaption><b>Figure </b>: StableBond Reaction to Make a Sterically-Protected Surface</figcaption>
<img src = "/docs/images/Screenshot 2022-01-19 115355.png"/>

<b>Note</b>: R could also be Diisopropyl silanes or diisobutyl silanes (C18)  

* 5 Different bonded phases compared  
* Analysis time of each run is only 2 minutes  
* Comparison done in optimum % organic  
* The fast runs mean a comparison can be done even if you have a good separation on the C18  
* More chances to optimize!


<figcaption><b>Figure </b>: Bonded Phase Selectivity Differences in 30% ACN</figcaption>
<img src = "/docs/images/Screenshot 2022-01-19 120036.png"/>


<figcaption><b>Figure </b>: Traditional Stationary Phase Bonding and Endcapping Reaction</figcaption>
<img src = "/docs/images/Screenshot 2022-01-19 120331(2).png"/>


### ZORBAX Eclips Plus & Eclipse XDB  

* Improved peak shape for basic compounds – especially at intermediate pH  
* Double endcapped – with two different reagents for more complete silanol coverage  
* Good for all sample types – acid, base, neutral  
* Wide useable pH range – pH 2-9  
* Pore size: XDB 80$\mathring{A}$, Plus 95$\mathring{A}$  

<figcaption><b>Figure 4</b>: Eclipse XDB structure</figcaption>
<img src = "/docs/images/Screenshot 2022-01-19 121056.png" width="360" height="160"/>


<figcaption><b>Figure </b>: Selectivity of Polar Phases Provides Optimum Separation of Steroids Versus Non-Polar C18/C8</figcaption>
<img src = "/docs/images/Screenshot 2022-01-19 121406.png"/>


<figcaption><b>Figure 5</b>: A comparison of Eclipse Plus C18 and another C18 column</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 194520.png"/>

Note: TEA stands for triethylamine. [Triethylamine is used to mask free silanol groups](https://www.researchgate.net/post/How_Triethilamine_works_on_a_compound_separation_in_a_reversed_phase_column_C182) on the HPLC column and therefore it improves peak shape of the analytes.


<figcaption><b>Figure 6</b>: Double endcapped Eclipse XDB-C18 comparing with single endcapped C18 from a different manufacturer</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 205543.png"/>

Bonded phases such as StableBond (which is not endcapped but has bulky side chain groups) sterically protect siloxane bonds from hydrolytic attack at low pH. SB columns are not endcapped to provide stability, lifetime, and reproducibility under acidic conditions.

### Bonus-RP

Bonded phases with embedded polar groups (Bonus-RP, Polaris-Amide-C18) or endcapped with polar groups, provide unique silanol shielding, reducing peak tailing for basic compounds.

* Good peak shape for basic compounds  
* Polar alkyl-amide bonded phase  
* Unique selectivity  
* Enhanced low pH stability with sterically protecting bonding  
* Triple endcapped  


<figcaption><b>Figure 7</b>: Bonus-RP structure</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 114113.png" width="180" height="80"/>


<figcaption><b>Figure 8</b>: Separation of Small Molecule Anorectics on ZORBAX Bonus-RP and Traditional Alkyl Phase</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 114319.png"/>


### Poroshell 120 HPH

Bonded phases that are stable at a high pH (Poroshell 120 HPH and ZORBAX Extend C18) minimize the interaction of basic compounds with free silanols, which reduces peak tailing.

Poroshell HPH-C18 with hybridized particle surface and double endcapping is designed to withstand high pH with good peak shape.

<figcaption><b>Figure 9</b>: Poroshell 120 HPH-C18</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 204555.png"/>

### ZORBAX Extend-C18 for high pH

ZORBAX Extend-C18 is designed to withstand high pH with good peak shape.

-   Superior high pH stability - up to pH 11.5 with silica particles.  
-   Excellent reproducibility.  
-   Patented bidentate, C18 bonding.  
-   Double endcapping.

<figcaption><b>Figure 10</b>: ZORBAX Extend-C18 structure</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 111451.png" width="180" height="80"/>


<figcaption><b>Figure 11</b>: Extend-C18 improves retention and peak shape of basic compounds at high pH - The retention of this sample of basic compounds increases at high pH on ZORBAX Extend-C18</figcaption>

<img src = "/docs/images/Screenshot 2022-01-10 110652.png"/>

-   Bonded phases that are more "wettable" in high aqueous mobile phases improve chromatography - both peak shape and retention reproducibility.  
-   A "wettable" bonded phase is one that does not fold over or collapse in a high aqueous mobile phase.  
-   These types of bonded phases can have polar endcapping or polar groups in the bonded phase, or other modifications to increase polarity.  
-   The SB-Aq column is an alkyl chain with more polar character that a typical C18 column.


<figcaption><b>Figure 12</b>: Procainamides on Hydrophobic-C8 Column - Inconsistent retention in high aqueous mobile phase with typical C18/C8 columns</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 110056.png"/>

## Column: column packing: Pore size

To get good peak shape, select column pore size according to the size of analyte molecules, large molecules needs large pore sizes.

-   To separate proteins and peptides, select wide-pore (300 $\mathring{A}$ and larger) column.

-   For more rapid mass transfer and improved efficiency of large peptides and proteins at higher flow rates, select superficially porous Poroshell 300 columns.

-   For small molecules as well as peptides for improved efficiency at higher flow rates, select superficially porous Poroshell 120 columns.

-   For small molecules, select small-pore totally particle columns.


<figcaption><b>Figure 13</b>: The size of a molecule in solution determines which pore size column is best</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 104559.png"/>

-   The narrower peak width indicates unrestricted access to the pores.

## Column: column packing: Poroshell particle technology

-   Superficially porous, solid core particles with a porous outer layer - they provide both improved throughput and higher resolution.

-   Superior peak shapes for faster, more accurate, results due to high-purity silica and advanced bonding chemistries.

-   Poroshell 120, 4 μm columns can provide higher efficiency at higher flow rates compared to 5 μm totally porous columns.

-   Poroshell 120, 2.7 μm columns can achieve similar efficiencies as sub-2 μm totally porous columns with substantially less pressure.

<figcaption><b>Figure 14</b>: The structures of superficially porous particles</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 214008.png"/>


<figcaption><b>Figure 15</b>: The structures of fully porous and superficially porous
particles (Poroshell 120, 2.7 &mu;m columns)</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 213441.png"/>

-   Poroshell 120, 1.9 μm columns can achieve superior efficiencies over totally porous sub-2 μm columns.

## Column: column packing: Formation of void in the column

<figcaption><b>Figure 16</b>: Formation of void in the column</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 214847.png"/>

## Mobile Phase: pH

<figcaption><b>Figure 17</b>: These basic compounds have good peak shape when the pH is lowered and the silica silanols are protonated</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 104227.png"/>

<figcaption><b>Figure 18</b>: Effect of pH on peak shape at or near the sample pKa</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 224048.png"/>

## Mobile Phase: Buffer

<figcaption><b>Figure 19</b>: Buffered mobile phases enhance retention, resolution, and peak shape</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 224249.png"/>


<figcaption><b>Figure 20</b>: Increasing buffer concentration decreases tailing factor (Tf)</figcaption>
<img src = "/docs/images/Screenshot 2022-01-03 224611.png"/>

## Mobile Phase: Temperature

<figcaption><b>Figure 21</b>: Temperature</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 053602.png"/>

## Mobile Phase: Organic modifiers

<figcaption><b>Figure 22</b>: Organic Modifiers</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 054821.png"/>

## Mobile Phase: Mobile phase additives (TEA, TFA, etc.)

<figcaption><b>Figure 23</b>: Mobile Phase Additives</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 055110.png"/>


<figcaption><b>Figure 24</b>: Mobile Phase Additives</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 055349.png"/>

-   Both acetic acid and TFA (trifluoroacetic acid) act as competing acids.  
-   TFA can be used at a lower concentration and is the preferred choice.

## Connecting capillaries and fittings

<figcaption><b>Figure 25</b>: Capillary Tubing Dimentions</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 055852.png"/>

-   Improper fittings can lead to broad, split and tailing peaks.  
-   Different manufacturers supply different types of fittings.  
-   Use fittings recommended for your system.  
-   Agilent LLC systems use Swagelok-type fittings for many instrument connections.

## Fittings

<figcaption><b>Figure 26</b>: Different fitting types have different stem lengths</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 060553.png" />

## Fitting Connections

Poor-fitting connections:

-   will broaden or split peaks or cause tailing  
-   will typically affect all peaks, but especially early eluting peaks  
-   Can cause of carry-over

<figcaption><b>Figure 27</b>: Poor-fitting Connections</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 061219.png" width="180" height="80"/>


<figcaption><b>Figure 28</b>: Poor-fitting Connections</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 061312.png"/>

## Detector Lamp Performance

<figcaption><b>Figure 29</b>: Detector Lamp Performance</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 070622.png"/>


<figcaption><b>Figure 30</b>: DAD Setting - Choose the Right Sampling Rate</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 071114.png"/>

## System related factors: Flow cells

<table><thead><tr class="header"><th><p>Flow Cell <br />
Volume / Pathlength</p></th><th><p>UV Signal/Noise</p></th><th><p>Chrom. Resolution</p></th><th><p>Application</p></th></tr></thead><tbody><tr class="odd"><td><p>13 &amp;mu;L / 10 mm</p></td><td><p>+++</p></td><td><p>+</p></td><td><p>for highest sensitivity and linearity 4.6 - 3 mm ID, 2.7, 3.5, 5 &amp;mu;m columns</p></td></tr><tr class="even"><td><p>5 &amp;mu;L / 6 mm</p></td><td><p>++</p></td><td><p>++</p></td><td><p>Best compromise of sensitivity &amp; selectivity HPLC/UPHPLC, 1.8 to 5 &amp;mu;m 4.6 - 1 mm ID columns</p></td></tr><tr class="odd"><td><p>1.7 &amp;mu;L / 6 mm</p></td><td><p>+</p></td><td><p>+++</p></td><td><p>For highest resolution UHPLC, 1.8, 2.7 &amp;mu'm 2.1 - 1 mm ID columns</p></td></tr><tr class="even"><td></td><td></td><td></td><td></td></tr></tbody></table>

Other flow cells include:

-   Max-light cartridge cells for Infinity DAD  
-   500 nL for capilary LC  
-   80 nL for nano LC
-   0.6 mm for Prep LC

<figcaption><b>Figure 31</b>: Match flow cell volume to chromatographic peak widths</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 072844.png"/>


<figcaption><b>Figure 32</b>: Match flow cell volume to column</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 073720.png"/>

## Sample-related Factors: Sample Load

Sample overload may cause peak fronting/broadening/splitting/doubling.

-   Peak fronting from sample overload - more sample than can effectively partition, results in some sample preceding the rest of the peak  
-   Reduce sample load to eliminate the problem

<figcaption><b>Figure 33</b>: Sample Overload</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 080227.png"/>

## Sample-related Factors: Sample solvent strength

<figcaption><b>Figure 34</b>: Strong injection solvent may cause poor peak shape</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 090525.png"/>


<figcaption><b>Figure 35</b>: Peak splitting when injecting a large volume of sample in a solvent stronger than the mobile phase</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 090723.png"/>

## Sample-related Factors: Sample cleanliness

-   Dirty samples can partially clog the column inlet frits, causing split peaks.  
-   Chemical contamination from the sample can reside on the column and cause secondary interactions with analytes, resulting in peak tailing and broad peaks.  
-   Physical and chemical filtration can minimize these problems.

<figcaption><b>Figure 36</b>: Column contamination from the samples causing peak tailing</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 091335.png"/>

## Sample-related Factors: Metal complexation

-   Analytes that can complex with metals may show poor peak shape.  
-   Both tailing and fronting may result from metal complexation.  
-   Metals are present in LC system, column, tubing, fitting ferrules, frits, etc.
-   Column packed with high purity silica eliminates silica as a source of metals.

<figcaption><b>Figure 37</b>: Metal sensitive compounds can chelate</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 092442.png"/>

Hint: Look for lone pair of electrons on $\textrm{O}_2$ or $\textrm{N}_2$ which can form 5 or 6-membered ring with metal.

<figcaption><b>Figure 38</b>: Acid wash can improve peak shape</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 094304.png"/>


<figcaption><b>Figure 39</b>: Both fronting and tailing are evident on purpurin before the acid wash</figcaption>
<img src = "/docs/images/Screenshot 2022-01-10 103014.png"/>


## Guidelines for Improved Peak Shape

-   Select columns based on high purity fully hydroxylated silica such as InfinityLab Poroshell line of columns as well as ZORBAX Eclipse Plus, StableBond, Eclipse XDB, Bonus-RP and Extend-C18.  
-   Select double or triple endcapped columns for mid pH or difficult basic compounds.  
-   Select special bonded phases (InfinityLab Poroshell 120 HPH, ZORBAX Bonus-RP, ZORBAX Extend-C18) for better peak shape at mid and high pH.  
-   Select wide-pore columns for high molecular weight analytes.  
-   Use spring loaded fittings such as InfinityLab Quick Connect and Quick Turn together with appropriate size connecting capillaries.  
-   Use buffered low pH mobile phases to reduce secondary interactions.  
-   Use 20 - 50 mM buffered mobile phases at every pH.
-   Use mobile phase additives when needed.  
-   Do sample cleanup.  
-   Check sample solvent and its strength.  
-   Use optimized flow rate and data collection rate.


## Checklist for Method Development and Better Separation
* First gather info of analyte  
  * How much is pKa?
    It will determine the column type to select.(options: encapped.  )  
    For Basic compounds, select:  
    
    > 1) fully hydroxylated, low acidity column, such as Rx-SIL, ZOBAX StableBond with Rx-SIL.  
    > 2) Bonus-RP provides unique silanol shielding reducing peak tailing for basic compounds.  
    > 3) Basic compounds can not ion-exchange with Extend-C18.  
    > 4) Eclipse XDB at intermediate pH (note: refer to mobile phase pH).  
    > 5) Poroshell 120 HPH.  
    
    For for all sample types – acid, base, neutral, select:
    
    > Eclipse XDB  
    
  * How big is the molecule?  
    It will determine the column pore size.  
    > Select wide-pore column for large molecules.  
    
    
* General guidance
  * Use mobile phase additives to reduce silica silanol ionization at mid pH.
  * Use mobile pahse additives to reduce hydrogen bonding with silica silanol at low pH.  
  * Beware of consistence among batches of columns because void in the column will be formed.  


## Observations:   
* Basic compounds can be run with low pH and Eclipse XDB column.   
* Buffered mobile phases enhance retention, resolution, and peak shape (figure #19, to be #21).   
* Change mobile phase B (organic solvent).    


## Resource
[Choosing Columns and Conditions for the Best Peak Shape](https://lcms.labrulez.com/labrulez-bucket-strapi-h3hsga3/dont_lose_It_getting_your_peaks_in_shape_july162020_fb574fd5b6/dont-lose-It-getting-your-peaks-in-shape-july162020.pdf)

[previous version](https://www.agilent.com/cs/library/eseminars/Public/secrets%20of%20good%20peak%20shape%20in%20hplc.pdf)