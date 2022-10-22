---
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: Column Caring and Protection
draft: false
lastmod: "2022-02-01"
series: 
tags: [Good Practice, Column, Trifluoroacetic Acid, Buffer, Ion Pairs]
title: Column Caring and Protection
toc: true
---

It talks about column caring, protection, cleaning, and regeneration.
<!--more-->

## Column Conditioning

### Restek Guide

<iframe width="360" height="200" src="https://www.youtube.com/embed/JYaLzRUxI7s" title="Column Conditioning" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The column is not going to be ready to use right out of the box unless the mobile phase you're using exactly matches our storage solvent. The certificate of analysis has the storage solvent listed. Most of our columns are stored in solvents that are greater than a 50% organic content.  Here is the procedure of conditioning:  
1) If you're using an organic mobile phase that's different from the storage solvent, you want to first flush the column with 10% or 20% less organic content. Do this for about 10 column volumes and then change over to the solvent that you're going to be using for your method.  
2) If you're using buffers in your method, after about 10 column volumes, switch over to the mobile phase you're going to be using with the buffer included, and then again flush about 10 column volumes. Watch for the baseline to stabilize in pressure because that lets you know the column is equilibrating.   
3) Do one or two conditioning injections before running your samples. That’s a good way to kind of prime the column.  

<table style="width:100%;">
<caption style="text-align:left", align = "top"><b>Table 3: Column Volumn Equations</b></caption>
<colgroup><col style="width: 40%" /><col style="width: 60%" />
</colgroup>
<thead>
  <tr style="text-align:left" class="header">
    <th><p>Type of Columns</p></th>
    <th><p>Equation</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
  <tr class="odd">
    <td><p>Fully Porous
    </p></td>
    <td><p>$V = 0.68 \times \pi \times r^2 \times L $
    </p></td>
  </tr>
  <tr class="even">
    <td><p>Superficially Porous
    </p></td>
    <td><p> $V = 0.50 \times \pi \times r^2 \times L $
    </p></td>
  </tr>
</tbody>
</table>


## Column Connection


<iframe width="360" height="200" src="https://www.youtube.com/embed/bXJ1TCOLe98" title="Connection your LC column" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Connecting an LC column is a seemingly simple task, though there are a few considerations to ensure a <font color ="blue">leak-free, zero-dead-volume</font> connection. I always begin by inspecting the fittings that will be screwed into the column body. If using a PEEK fitting, for standard HPLC pressures be sure that your tubing is cut square and the fitting threads are in good shape. Many times, I even swap out a traditional PEEK fitting for a hand-tight EXP fitting. The nice thing about the EXP fittings is that the PEEK/titanium non-swaged ferrule allows for repeated installations without compromising the high-pressure seal. When making the shift to UHPLC, the EXP fittings can be used at pressures greater than 1000+ bar using a wrench and an extra quarter to half turn.

Once you’ve chosen the appropriate fittings, be sure to check your column label for flow direction and insert your fitting into the column end. I like to push the tubing into the column as I’m securing the fitting—this <font color ="blue">ensure that a zero-dead-volume connection is made</font>. After your column is connected, turn on your pump’s flow and be confident you’ve made a leak-free connection!


## Column Care

### Sigma-Adrich Guide  

#### Deterioration

Regardless of whether the column contains a bonded reversed or normal phase, ion exchange, affinity, hydrophobic interaction, size exclusion, or resin/silica based packing, the most common problem associated with analytical columns is <font color ="blue">deterioration</font>. <font color ="blue">Symptoms of deterioration are poor peak shape, split peaks, shoulders, loss of resolution, decreased retention times, and high back pressure</font>. These symptoms indicate contaminants have accumulated on the frit or column inlet, or there are voids, channels, or a depression in the packing bed.

Deterioration is more evident in higher efficiency columns. For example, a 3 micron packing retained by 0.5 micron frits is more susceptible to plugging than a 5 or 10 micron packing retained by 2 micron or larger frits. Proper column protection and sample preparation are essential to getting the most from each column.

Overloading a column can cause poor peak shapes and other problems.

#### Deactivation

Samples and mobile phases containing very strongly polar solvents, such as water or alcohols, can deactivate uncoated silica HPLC columns. 

[Source Sigma-Aldrich](https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/hplc-troubleshooting-guide?gclid=Cj0KCQiA_8OPBhDtARIsAKQu0gYR2a-bKGOUhDIj6CVZCut9t27HPzLqFqcyZBg51Yp8La_Ecue7cw0aAkZDEALw_wcB#injector-Injection-solvents)


## Column Protection

### Sigma-Adrich Guide  

Although not an integral part of most equipment, mobile phase inlet filters, pre-injector and pre-column filters, and guard columns greatly reduce problems associated with complex separations. We recommend that all samples be filtered through 0.45 μm or 0.2 μm syringe filters. We strongly recommend the use of guard columns.

Filters and guard columns prevent particles and strongly retained compounds from accumulating on the analytical column. The useful life of these disposable products depends on mobile phase composition, sample purity, pH, etc. As these devices become contaminated or plugged with particles, pressure increases and peaks broaden or split. As an example, Figure 1 presents a clear case for the use of guard columns.  


<figcaption><b>Figure 1</b>: Supelguard Columns Prolong the Lifespan of Your Analytical Columns</figcaption>
<img src = "/docs/images/Screenshot 2022-02-01 184016.png"/>

[Source Sigma-Aldrich](https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/hplc-troubleshooting-guide?gclid=Cj0KCQiA_8OPBhDtARIsAKQu0gYR2a-bKGOUhDIj6CVZCut9t27HPzLqFqcyZBg51Yp8La_Ecue7cw0aAkZDEALw_wcB#injector-Injection-solvents)


### Restek Guide


<iframe width="360" height="200" src="https://www.youtube.com/embed/vnMtEybkBUo" title="Column Protection" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 

Because guard columns will add some extra column volume to your separation, you might consider to minimize the thickness of filter.  


## Column Cleaning

### Thermo Guide
In all instances, the volume of solvent used is 40 – 60 column volumes unless otherwise stated.  

The column efficiency, capacity factor etc. should be measured at the start and end of the clean-up procedure to ensure that it has been performed successfully and has improved the column performance.   

Ensure that no buffers/samples are present on the column and that the solvent used prior to the clean up is miscible with the first wash solvent.  

After the clean up, ensure that the test mobile phase is compatible with the last solvent in the column.  

[Source Thermo](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)

### Shodex Guide

When a column is deteriorated by the foreign substances remaining in the column or adsorbed by the packing material, the substances might be washed out by the procedure described below. However, sometimes the procedure is not suffcient to regenarate the column and, in such case, it is necessary to replace the column with a new one. And, even if the column can be regenarated, the column performance may be not so good as before. After cleaning the column, be sure to replace the in-column solvent to the normal solvent. The use of a guard column at the up-stream of the main column is recommended to prevent the main column from the deterioration by the foreign substances. When a guard column is used, first, the guard column will be deteriorated by the foreign substances and it is possible to prevent the main column from the deterioration by replacing the guard column regularly.  

When cleaning a guard column, be sure to disconnect the main column before the cleaning. If a guard column and a main column are connected in series and the cleaning procedure is performed, foreign substances in the guard column may move to the main column and, as the consequence, the main column may be deteriorated.



<img src = "/docs/images/Screenshot 2022-01-17 092900.png"/>


[Source Shodex](https://www.shodex.com/en/da/01/05.html)


## Reversed Phase Media

### Thermo Guide
1. Flush with HPLC grade water; inject 4 aliquots of 200 µL DMSO during this flush  
2. Flush with methanol  
3. Flush with chloroform  
4. Flush with methanol  


Note: Normal Phase Media, Anion Exchange Media, Cation Exchange Media, Protein Size Exclusion Media are not included.  Details can be found in the source.

[Source Thermo](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)


## Column Regeneration

### Galak Guide

The main purpose of the regeneration of the C18/C8 HPLC column is to remove the impurities out of the HPLC column.

#### When do we need the regeneration of the HPLC column?

After prolonged use, <font color ="blue">the column pressure rises, or peak trailing occurs</font>.

#### Main steps for the regeneration of C18/C8 column

Before cleaning the column, disconnect the column from the detector and allow the cleaning solvent to flow into the recovery vessel.

Sometimes the column can be backflushed for cleaning to allow contaminants to flow out of the column. Cleaning the column requires the use of a stronger solvent than the mobile phase. The minimum volume for the solvent used to clean the analytical column is 10 column volume.

To clean the column in the opposite direction, proceed as follows.

-   Disconnect the column from the detector. Then leaving the tubing at the end of the column and place it in a beaker that receives the liquid.
-   Rinse with a mobile phase without buffer salts (water/organic phase) firstly.
-   Then rinse with 100% organic phase (methanol and acetonitrile).
-   Check that the pressure returns to normal, and if not, proceed to the next step.
-   Discard the column or consider washing with stronger conditions. E.g. 75% Acetonitrile/25% Isopropanol, 100% Isopropanol, 100% Dichloromethane, 100% Hexane.

Estimated column volume for different columns:

<table style="width:100%;"><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup>
<thead>
<tr class="header"><th><p>Column Size (mm x mm)</p></th><th><p>Column Volume (mL)</p></th></tr>
</thead>
<tbody>
<tr class="odd"><td style="text-align: center; vertical-align: middle;"><p>250 x 4.6</p></td><td style="text-align: center; vertical-align: middle;"><p>≈2.5</p></td></tr>
<tr class="even"><td style="text-align: center; vertical-align: middle;"><p>150 x 4.6</p></td><td style="text-align: center; vertical-align: middle;"><p>≈1.5</p></td></tr>
<tr class="odd"><td style="text-align: center; vertical-align: middle;"><p>150 x 4.0</p></td><td style="text-align: center; vertical-align: middle;"><p>≈1.13</p></td></tr>
<tr class="even"><td style="text-align: center; vertical-align: middle;"><p>150 x 3.0</p></td><td style="text-align: center; vertical-align: middle;"><p>≈0.64</p></td></tr>
<tr class="odd"><td style="text-align: center; vertical-align: middle;"><p>150 x 2.1</p></td><td style="text-align: center; vertical-align: middle;"><p>≈0.28</p></td></tr>
<tr class="even"><td style="text-align: center; vertical-align: middle;"><p>100 x 2.1</p></td><td style="text-align: center; vertical-align: middle;"><p>≈0.21</p></td></tr>
<tr class="odd"><td style="text-align: center; vertical-align: middle;"><p>50 x 4.6</p></td><td style="text-align: center; vertical-align: middle;"><p>≈0.50</p></td></tr>
<tr class="even"><td style="text-align: center; vertical-align: middle;"><p>30 x 4.6</p></td><td style="text-align: center; vertical-align: middle;"><p>≈0.30</p></td></tr>
</tbody>
</table>

**Notice**:

* Whether hexane or methylene chloride is used, it must be rinsed with isopropanol before use or before resuming the reversed-phase mobile phase.  
* Buffer salts may precipitate and cause backpressure within the column. Pass the column slowly with hot water to remove the precipitation.  
* A rinse solution containing propanol will generate higher operating pressures due to increased viscosity. The flow rate needs to be reduced during the rinse to maintain a safe operating pressure.  
* To avoid precipitation, if the system does not contain a non-volatile buffer, the system is first flushed with an aqueous buffer-free mobile phase before the pure organic solvent enters the system.  

#### Regeneration can't recover the HPLC column with 100% efficiency

High column pressure problems may not be caused by a blocked column but by a damaged gasket in the system and particles deposited on the inline filter head, which should be replaced before cleaning the column.

Do not replace the column sieve plate at random. It may cause irreversible damage to the column.

If the deterioration in quantitative analysis is due to a decrease in separation, this column should be discarded and replaced.

[Galak source](https://galaklc.com/how-to-regenerate-the-c18-c8-hplc-columns/)


### Sigma-Aldrich Guide

#### Silica Column

Flush with the following:

1) 50 mL hexane  
2) 50 mL methylene chloride  
3) 50 mL 2-propanol  
4) 50 mL methanol  
5) 25 mL methylene chloride  
6) 25 mL mobile phase  
7) Evaluate column performance according to conditions specified by the manufacturer.

Note: See also the [Silica Column Regeneration Solution]() for rejuvenating a deactivated silica column.


#### Silica-Based Reversed Phase Column (alkyl (C8, C18, etc.), phenyl, or diphenyl column, SUPELCOSIL LC-PAH column)

**A. Water Soluble Samples Flush with the following**:  
1) Flush with warm (60 °C) distilled water
2) 50 mL methanol
3) 50 mL acetonitrile
4) 25 mL methanol
5) 25 mL mobile phase
6) Evaluate column performance.

**B. Samples Not Soluble in Water Flush with the following**:
1) 50 mL 2-propanol  
2) 50 mL methylene chloride  
3) 50 mL hexane  
4) 25 mL isopropanol  
5) 25 mL mobile phase  
6) Evaluate column performance.  


#### Polar-Bonded Phase Column (amino, cyano, or diol column or Pirkle-type chiral columns).

For a column used in the reversed phase mode (e.g., organic solvent/aqueous buffer mobile phase), follow the same cleanup procedure as for silica-based reversed phase columns. For a column used with nonaqueous mobile phases, use the following scheme:

Flush with the following:

1) 50 mL chloroform  
2) 50 mL methanol  
3) 50 mL acetonitrile  
4) 25 mL methylene chloride  
5) 25 mL methanol  
6) 25 mL mobile phase  
7) Evaluate column performance.  


#### SUPELCOSIL LC-PCN Column

**A. To Remove Protein**  
Flush with 10 column volumes of acetonitrile:water, 50:50, containing 0.1% trifluoroacetic acid.

**B. To Remove TCA**
Flush with 10 column volumes of distilled water (adjust pH to 2.5 with H3PO4), then with 10 column volumes each of:  

1) water (to remove salts)  
2) methanol (to remove water)  
3) methanol/methylene chloride, 50:50 (a general clean-up solution) 
4) methanol  

If column performance still is not acceptable, prepare the mobile phase buffer at 10X the concentration used for the analysis and recycle through the column overnight.[^1]
Re-equilibrate the column with mobile phase at the normal buffer concentration and reevaluate.

[^1] Use caution: with some buffer types and/or concentrations a 10-fold increase in concentration can cause precipitation.


#### Silica-Based Columns for RPLC of Proteins and Peptides

1) Follow the protocol for silica-based reversed phase columns.  
2) Alternatively, make one or more 100 μL injections of trifluoroethanol (determine the number of injections by evaluating column performance after each injection).  
3) Evaluate column performance.  


#### Nonbonded Silica Columns Exposed to Polar Solvent

Samples and mobile phases containing very strongly polar solvents, such as water or alcohols, can deactivate uncoated silica HPLC columns. This can drastically affect column performance, particularly solute retention and selectivity. (Figure C2). Even prolonged column flushing with a nonpolar solvent only partially restores column performance, while wasting chemicals. A silica regeneration solution quickly and inexpensively restores silica column performance by removing trapped polar material. Pump the solution through the affected column for 10 minutes at a rate of 4 mL/minute, then flush with mobile phase for 10 minutes at a rate of 2 mL/minute. Evaluate column performance by using the test mixture for evaluating silica columns (Cat. No. 58281). Performance should be virtually the same as before the polar solvent was introduced (Figure C3).

<figcaption><b>Figure C</b>: Regeneration Solution Restores Silica Column Performance</figcaption>
<img src = "/docs/images/Screenshot 2022-02-01 213610.png"/>


### Dr. Egidijus Machtejevas, Analytix, Vol 7 | p30

Any HPLC or UHPLC column can typically be used for only a limited number of injections. Correct usage and maintenance of the column extends its lifetime and benefits the economy of the method. It is important to follow generally accepted chromatography practices, like adequate sample preparation (sample should be filtered through 0.45 µm membrane filter for HPLC and 0.22 µm filter for UHPLC); suitable quality/purity of the mobile phase (for example, isocratic grade solvents for isocratic mode, gradient grade solvents for gradient elution); filtered mobile phase, well developed method with sufficiently strong elution to minimize unspecific sorption; temperature, pH, and maximum backpressure ranges compatible with selected column. Also important to mention is that the total number of injections is inversely proportional to the volume of the sample injected, e.g., if 10 µL sample is applied per injection and this results in a column lifetime of 5000 injections, then an increased sample load of 100 µL per injection would typically shorten column lifetime to approximately 500 injections. Even if all the above listed points are carefully followed, users sometimes feel that column lifetime should be longer. In order to find out how to extend the lifetime of the column, it is first necessary to understand what causes the aging of the column.  

1. Column contamination/clogging by particles. Keep in mind that your column is a very efficient filter. Any particulate material coming from the mobile phase or sample will contaminate frits, and some particles might also migrate into the column packing. This will result in an increase in column backpressure. This creates more stress for the pump and can cause a column to settle, creating a void which result in peak splitting.

2. Unspecific sorption. An HPLC column can encounter many different substances during its use, such as salts from buffers or impurities from the mobile phase and sample. These materials can have lesser or greater retention than the analytes separated. These undesired interferences, if observed by the detector, appear as ghost peaks, blobs, baseline upsets or even negative peaks. Absorbed impurities might negatively contribute to retention mechanism (shorten retention) or begin to act as a new stationary phase (increased retention).

3. Column repacking. Every particle packed column contains a range of particle sizes. Particle size distribution might be wider or narrower. During chromatographic analysis, columns will experience pressure stresses when a non-pressurized injection loop is connected to a pressurized column. During these pressure stresses, the column packing is getting shocked, then particles might swap positions, causing the generally bigger particle to go up (towards column inlet), and the smaller down (towards column outlet). After a number of injections, smaller particles will accumulate at the bottom, and bigger at the top. The smaller particle zone then has a higher packing density backpressure, which users will observe due to the steady increase in backpressure. This again creates more pressure for the instrument and can cause a column to settle, creating a void and consequently peak splitting.

Many customers are asking for procedures which could regenerate a column to the initial performance level in order to extend column lifetime. Therefore, the importance of very carefully reading the instruction sheet which comes with every column cannot be overstressed. The sheet also contains information about suggested column care and regeneration procedures. This advice must be followed and can be different from column/phase type to column/ phase type. However, we can theoretically analyze how efficient column regeneration might be. Column contamination at the inlet by particles should generally be easily removed by washing the column for about 5 to 20 column volumes in a backflush mode, but only if the column manufacturer allows it. It is important to make sure that both column frits (inlet and outlet) have the same porosity. Please keep in mind that small impurity particles trapped deeper in the column packing are very unlikely to be removed. As a result of this washing, the column backpressure should be somewhat decreased. To remove unspecifically bound material from the column is often more difficult and the outcome is usually unpredictable, because typically we do not know what compounds these contaminants contain. The success ratio might be from 0 to 100%. To fully restore column packing uniformity for columns packed with smaller than 5 µm particles is very unlikely. Normally column backflush only helps for a short time.

So, what is the most reliable and certain solution offered for this topic? The use of guard columns! Guard columns will filter all particles, accumulate unspecific adsorbed materials, and will also extend the lifetime of the analytical main columns used at marginally alkaline pH. Typically, when the guard column is replaced, a majority of the problems will be eliminated, and even more importantly, it will occur without any lengthy time and solvent consuming washing procedure with questionable outcome. Important note: the Guard column must be the same particle size as the analytical column, the same modification and the same material type.

But how will you know when to replace the guard column? General advice: Replace the guard column when the nature of the sample is changing, when backpressure is increased about 10-15%, or by schedule/time basis (for example, every 200 to 500 injections – depending on the injection volume and sample purity).

If you routinely have any problems with the lifetime of your main column, think early enough about guard columns to save yourself analytical headaches.


## Column Storage

### Dr. Egidijus Machtejevas, Analytix, Vol 8 | p29

The concept may seem simple. Once the last chromatogram of the day or the project is finished, we disconnect the column and put it into the drawer. However, what exactly should be done with the column before storing it? Does the procedure vary depending on the planned storage time? There is actually quite a lot to: planned storage time, column modification (stationary phase), buffer concentration, pH, etc. In all the column storage scenarios, <font color ="blue">special care must be taken if buffers, which provide a microbe friendly environment, are used</font>. In such cases, fresh buffers are to be prepared daily and filtered using 0.45 or 0.22 μm membrane filters. Also adding a small amount of organic solvent (~ 10%) or adding sodium azide (~ 0.05%) in the storage solvent - if buffers are used for storing e.g. needed for some HILIC columns - can be sufficient to prevent microbial growth. The easiest and safest way to store the column, however, is by using the same solvent in which it was delivered to you. 

This applies in particular to the <font color ="blue">polymer-based stationary phases</font>. Depending on their material properties, these might not be compatible with some organic solvents. 

For <font color ="blue">silica-based normal phase columns</font>, it is typically recommended that heptane or isopropanol are used. I personnaly have also had good experience with dioxane, as it nicely removes residual water, but this cannot be generalized. Some stationary phases such as aminopropyl- or diol-modified stationary phases might be effectively stored in 2-propanol, which is in fact, compatible with both Reversed Phase and Normal Phase modes. Size exclusion columns should be stored in a solvent compatible with the swelling properties of the packing. 

Column storage may be short, middle, and long term.   

**<font style="text-transform:uppercase;">For short term storage</font>**, i.e., overnight, either the mobile phase used in the last analysis can remain in the column, or it is possible that the mobile phase passes at a very low flow rate (especially if the buffer concentration in the mobile phase is high, >50 mM). In these cases, <font color ="blue">column conditioning</font> can potentially be skipped before continuing the analysis the next day. This option is particularly recommended for <font color ="blue">normal phase</font> separations, where change in mobile phase composition can result in lengthy re-equilibration. However, if the buffer concentration in the mobile phase is very high (>0.5 M), then the lifetime of the pump parts (e.g. injector & switching valves) could depend on the length of time they are in contact with high concentration buffer. The same is true for the column if the pH is close to the limit of the column (for most silica-based columns - pH 2 to pH 7). Some salts, such as chloride salts used in ion chromatography in particular, are very corrosive to stainless steel and might attack the column wall as well as the inlet-outlet frits. In such cases, column (and all system) should be flushed with a less harsh mobile phase. In this case, I would recommend rinsing the column with a water-rich mobile phase (~90%) with about 10 column volumes (the approximate column volumes for some popular dimension are listed in Table 1).  


<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Table 1. Approximate Column Volumes for some Popular Column Dimensions and Their Multiples</b></caption>
  <colgroup>
    <col style="width: 10%" /><col style="width: 10%" /><col style="width: 27%" /><col style="width: 27%" /><col style="width: 27%" />
  </colgroup>
  <thead>
  <tr style="text-align:center" class="header">
    <th><p>Length (mm)</p></th><th><p>ID (mm)</p></th><th><p>Approximate Column Volume (mL)</p></th><th><p>10 Column Volumes (mL)</p></th><th><p>15 Column Volumes (mL)</p></th>
  </tr>
  </thead>
  <tbody VALIGN=Top style="text-align: center; vertical-align: middle;" align="char" char=".">
    <tr class="odd">
      <td><p>250</p></td><td><p>4.6</p></td><td><p>4.15</p></td><td><p>41.5</p></td><td><p>62.3</p></td>
    </tr>
    <tr class="even">
      <td><p>250</p></td><td><p>2.0</p></td><td><p>0.79</p></td><td><p>7.9</p></td><td><p>11.8</p></td>
    </tr>
    <tr class="odd">
      <td><p>150</p></td><td><p>4.6</p></td><td><p>2.49</p></td><td><p>24.9</p></td><td><p>37.4</p></td>
    </tr>
    <tr class="even">
      <td><p>150</p></td><td><p>2.0</p></td><td><p>0.47</p></td><td><p>4.7</p></td><td><p>7.1</p></td>
    </tr>
    <tr class="odd">
      <td><p>100</p></td><td><p>4.6</p></td><td><p>1.66</p></td><td><p>16.6</p></td><td><p>24.9</p></td>
    </tr>
    <tr class="even">
      <td><p>100</p></td><td><p>2.0</p></td><td><p>0.31</p></td><td><p>3.1</p></td><td><p>4.7</p></td>
    </tr>
    <tr class="odd">
      <td><p>50</p></td><td><p>4.6</p></td><td><p>0.83</p></td><td><p>8.3</p></td><td><p>12.5</p></td>
    </tr>
    <tr class="even">
      <td><p>50</p></td><td><p>2.0</p></td><td><p>0.16</p></td><td><p>1.6</p></td><td><p>2.4</p></td>
    </tr>
    <tr class="odd">
      <td><p>25</p></td><td><p>4.6</p></td><td><p>0.42</p></td><td><p>4.2</p></td><td><p>6.2</p></td>
    </tr>
    <tr class="even">
      <td><p>25</p></td><td><p>2.0</p></td><td><p>0.08</p></td><td><p>0.8</p></td><td><p>1.2</p></td>
    </tr>
  </tbody>
</table>
 

If you disconnect a column from the instrument, end plugs should be tightly fitted to prevent solvent evaporation, otherwise a drying of the stationary phase could happen. The worst-case scenario is an improperly washed column previously used with a high salt concentration and allowed to dry over time, resulting in the formation of salt crystals. The column most likely will be irreversibly damaged. However, it might be permissible for some columns to be stored dry, others should not. Please check the manufacturer’s column care guidelines. Standard HPLC columns should only be stored at room temperature and never in a freezer (exceptions are protein modified affinity or active enzyme reactor columns). This paragraph’s recommendations are also valid for mid- and long-term column storage. 

**<font style="text-transform:uppercase;">Medium interval storage</font>**, i.e., 2 days or over the weekend. <font color ="blue">Columns should be flushed</font>. Flush intensity or volume depends on the buffer concentration used during analysis. It is generally advisable to first flush buffering agents off the column with about 10 column volumes of mobile phase with 10% organic solvent in the water. In this case, washing will be effective, and we would also avoid buffer precipitation and possible column dewetting problems. When the buffer is washed out, pump 100% organic for 15 column volumes. The column could then be left connected to the instrument or disconnected and closed with end plugs. Please consider short term column storage advice too, such as referencing column documentation for recommended storage solvent. 

Storing a HILIC column in an acetonitrile–water mixture may take a long time to re-equilibrate if a low ionic strength buffer such as 5 mM ammonium acetate is used for the analytical method. Therefore, <font color ="blue">for HILIC columns, it is recommended that they are stored in solvents containing 80–90% acetonitrile and buffers containing 5–10 mM ammonium acetate or ammonium formate</font>. But for some HILIC phases this may differ, please check the column product information. Ion-exchange and mixed-mode phases containing carboxylic acid functional groups (for example, weak cation-exchange phases) cannot be stored in solutions containing alcohols, because of a possible slow esterification and the resulting change in selectivity/capacity. 

**<font style="text-transform:uppercase;">For long term storage (>2-3 days)</font>**, silica based columns, after proper washing with a minimum of 15 column volumes (Table 1) using ~ 10% organic solvent in water, should then be flushed with an organic-rich mobile phase for a minimum of 10 column volumes and should then be stored in an aprotic solvent. If water is also present, it should not be in higher concentrations (less than 50%). The best storing solvent recommended in the literature is acetonitrile or methanol (some exceptions exist, such as columns with amide modification, which should be stored in acetonitrile only). Some studies1 also indicate that at RP conditions, rates of erosion and corrosion of the stainless steel components of the HPLC using pure acetonitrile or methanol were higher compared to when they were mixed with water. Therefore, 90% acetonitrile or methanol are perfect long-term storage agents for most reverse-phase columns. However, my personal favorite storage solution is a mixture of isopropanol and water (80/20), because of isopropanol’s higher vapor pressure and the reduced chance for column dry-out, even if end fittings are not completely sealed. Isopropanol is also a stronger eluent, therefore, after storing in isopropanol, we can be sure that even more impurities will be removed than with acetonitrile or methanol gradients. Last but not least, isopropanol is also less toxic. It is also important to note that all mobile phases used for flushing, washing, or column storing must be of the same quality grade as the ones used for the analysis. Columns should be stored at room temperature (exceptions include affinity columns, as mentioned before) in their original box, with a copy of the certificate of analysis (CoA)/Column Report, and possibly with the column log book to show previous uses and to help the user evaluate the column prior to future use. 

How long can columns be stored? This depends on many factors. Some columns do not change even after 5 or 10 years of storage. If you decide to use a column after such a long period of time, assume that the column most likely has dried out, and needs to be rewetted by first flushing with 100% acetonitrile (RP-phases), and then equilibrated in mobile phase for about 1 hour before making any selectivity measurements. Additionally, consider running a column test mix and compare the data to the CoA or previous column tests. 

Correct column storage is essential for proper chromatography and a prolonged column life. In addition, always follow the manufacturer’s guidelines for column operation details!


Reference
1. R.A. Mowery, Jr., The Corrosion of 316 Stainless Steel in Process Liquid Chromatography with Acetonitrile or Methanol Carriers, J. Chromatogr. of Science, Volume 23, Issue 1, January 1985, Pages 22-29, https://doi.org/10.1093/chromsci/23.1.22


### Restek Guide


<iframe width="360" height="200" src="https://www.youtube.com/embed/IacnT4Vt40k" title="Storing LC Columns" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

When shelving a column, be sure to flush out any buffers or other additives. You can use a solvent mix similar to initial run conditions, just without additives, and that can be good for a couple days of storage. For longer term storage, you should choose a storage solvent appropriate to your column and method. And always make sure to document the date and storage solvent, so you have the information you need to get back up and running as soon as possible. 



## Column Operating Temperature

### Thermo Guide

Fluctuations in temperature can cause <font color = "blue">peak drift</font> and other undesirable effects in your chromatography.  

In applications where the column will be maintained at temperatures above or below ambient, it is also worth considering the use of <font color = "blue">a solvent heater</font>. The effect of solvent heating prior to analysis is shown below.


<figcaption><b>Figure </b>: Pre-heater</figcaption>
<img src = "/docs/images/Screenshot 2022-01-14 221008.png"/>


The recommended operating temperatures for columns is very much dependent on the analytical conditions and the packing inside the column. Typically, carbon and polymer based columns can be used at far higher temperatures than can a silica based column. This is because elevated temperatures increase the risk of chemical attack on the bonding and base silica by the solvent. For example, at 60 °C and with a buffer at pH 2, a silica based amide column packing can start to <font color = "blue">hydrolyze</font>. This would drastically affect the chromatography available from the column.

The choice of particle size is also a contributing factor when considering operating temperature. <font color = "blue">Particles below 5 µm in diameter are more prone to bed collapse and loss of efficiency at highly elevated temperatures</font>.

Temperature can be a powerful method development tool if it is used correctly. <font color = "blue">Lower temperatures can be used to help increase retention, selectivity and resolution. Higher temperatures can be used to help decrease retention, selectivity and resolution</font>.  





