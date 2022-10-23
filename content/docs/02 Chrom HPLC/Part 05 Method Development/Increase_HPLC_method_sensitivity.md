---
weight: 1
title: Increase HPLC/UHPLC Method Sensitivity
authors: null
categories: null
tags: [Sensitivity, TEA, TFA]
description: 
draft: false
date: "2020-10-16"
lastmod: "2020-10-16"
series: null
toc: true
---


<!--more-->


The sensitivity of a chromatographic method might be described by its limit of detection (LOD). LOD is usually defined as the minimum detectable amount or concentration of a component that can be reliably detected using a given analytical method. In other words, LOD is the lowest amount or concentration of an analyte in a test sample that can be reliably distinguished from zero. In reality, “zero” is obtained from the measurement of a sample not containing the component (blank sample). The usual estimation of LOD in chromatography involves the measurement of signalto-noise ratio (S/N). The chromatographic signal value is determined by the height of the analyte peak and the noise value. The noise value can be derived from either the standard deviation of the noise or from the so called peak-to-peak value. Latter one is determined by injecting a blank sample and using the difference between the highest and lowest points in the baseline noise around the time where the peak of interest would elute. The globally accepted criteria for the detection of an analyte is a S/N ratio of equal to or above 3. Multiple (minimum 3) measurements are performed at the lowest concentration, with all the measurements still showing significant detection of the compound (S/N ≥ 3) for the concentration to be taken as LOD. Limit of detection is the most important value that researchers look for when considering their method’s validity. 

So how to increase the sensitivity of your analytical method? Logically, it is quite simple: we must either increase the signal or/and decrease baseline noise.  

**Reduction of baseline noise**  

In many cases, the type of solvent and additives used and their purity in the eluent are strongly responsible for the noise of the baseline. Additives such as TEA or TFA might increase noise due to their relatively high UV absorbance. It is particularly important if the detection is done at low wavelengths of below 220 nm. First, check whether or not the detection can also be performed reliably at longer wavelengths. Doublecheck the eluent selection, for example, methanol exhibits a higher absorption at low wavelengths, which can make the detection of smaller peaks difficult. Uncontrolled temperature drifts during the day for detector and the solvents should also be avoided. Next, even minor impurities from the column after synthesis or because of column bleeding can greatly increase baseline noise. Therefore, it is best to first install a new guard column and, if necessary, also a new separation column and compare the obtained chromatograms. Another factor to be considered is the HPLC system itself. It can be checked for any contamination or air in the system, performance of pumps (pressure fluctuations), lifetime of UV lamp, and cleanliness of the detector cell - all of which can contribute to the baseline noise. Finally, the size of solvent mixing unit. A smaller size offers less contribution to the dead volume, but a higher baseline noise, usually because of less perfect mixing. A larger solvent mixing unit would facilitate a better mixing but would also contribute to larger dead volume. In general, regular maintenance, cleaning cycles, and good understanding of the system’s individual components are prerequisites for a problem-free HPLC analysis. 

**Increasing the signal intensity**

**<font class = "font_upper">Decrease the column internal diameter (ID)</font>**. The ID of the HPLC column affects the concentration of the sample in the column. <mark>Samples are diluted in proportion to the cross-sectional area of the column and therefore, smaller ID columns yield less dilution</mark>. Just a decrease by half of the diameter will result in a ~4 times higher concentration in the detector. Keep in mind that the column capacity is also reduced at the same time and hence the injection volume as well as the flow rate must be adjusted. However, above mentioned increase in sensitivity will be obtained even after adjusting/lowering the injection volume. 

**<font class = "font_upper">Increasing column efficiency</font>**. <mark>Reduction of particle size causes an increase in the sensitivity because of more narrow and higher peaks</mark>. Excellent choice is to use superficially porous particle (SPP)/Fused-Core® columns like Ascentis® Express. These will simulate a smaller diameter (more efficient) particle without a larger increase in backpressure. For example, replacing a fully porous 3 µm particle packed column with a superficially porous particles of 2.7 µm, would almost double the column efficiency. Since the efficiency is higher, the peak will be narrower and higher, and by that the sensitivity will increase. 

**<font class = "font_upper">System efficiency</font>**. In order to have a high-efficiency separation, it is important to <font color ="blue">minimize the instrument’s dead volume</font>. This can be achieved by optimizing the entire HPLC system using smaller I.D. and/or shorter connection capillaries, smaller injection unit, and smaller detector cell. 

**<font class = "font_upper">Optimal flow rate</font>**. The resulting peak height/efficiency is also influenced by the choice of the correct flow rate. A too high flow rate (very narrow peaks), at a too low detection frequency may result in losses during detection as the detector simply would not have enough "time" to reasonably detect the analyte (too few data points). Also, the van Deemter plot should be considered: try to operate at the optimum conditions, selecting an optimal flow rate where efficiency is at its maximum (minimum of theoretical plate height). 

**<font class = "font_upper">Column bleeding</font>**. The choice of the separation column can also affect the noise levels. Choose chromatographic conditions matching optimum temperature, pH, solvent compatibility, working ranges of the column to minimize potential bleeding effects. 

**<font class = "font_upper">Peak tailing</font>**. Select best column and chromatographic conditions to obtain symmetrical peaks. Optimization of method conditions must be performed to select the most suited buffer, pH, and if necessary, additives. For example, optimal pH value should be +/- 2 pH units of the analytes pKa value, in order to work with the nonionized form. Use of a steep gradient can often yield a sharper peak than isocratic mode alone. 


## Conclusions

In order to increase your chromatographic method sensitivity, chose one or few options to reduce baseline noise and/or make suggested improvements to increase signal intensity.  


## Reference
<a href = "https://www.sigmaaldrich.com/deepweb/assets/sigmaaldrich/marketing/global/documents/802/240/analytix-reporter-v9-nl7012en-ms.pdf#page=30" target="_blank" rel="noopener noreferrer">Dr. Egidijus Machtejevas, Analytix Reporter | Sigma Aldrich vol 9, 2021</a>
