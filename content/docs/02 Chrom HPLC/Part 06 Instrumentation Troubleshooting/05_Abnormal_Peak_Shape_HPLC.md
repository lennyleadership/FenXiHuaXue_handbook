---
authors: edited by Lenny Lin
categories: Category
date: "2022-01-12"
description: It talks about abnormal peak shape
draft: false
lastmod: "2022-01-28"
series: 
tags: []
title: Chapter 05 LC Abnormal Peak Shape
toc: true
---

<figcaption><b>Figure </b>: </figcaption>

<img src = "/docs/images/"/>

<!--more-->

Abnormal peak shape encompasses a range of possible peak shape problems.

-   No peaks  
-   Smaller than expected peaks  
-   Fronting or tailing peaks  
-   Broad peaks -- early eluting analytes or all analytes  
-   Double peaks / shouldering peaks / Peak Splitting  
-   Flat topped peaks  
-   Change in Peak Height (one or more peaks)
-   Rounded peaks  
-   Extra peaks  
-   Negative peaks  
-   Ghost peak  

If all the peaks in a chromatogram are affected, then it suggests that the problem is related to either the system or the column. If only early eluting peaks are affected then it suggests that the problem lies within the fluid path -- perhaps with incorrect ID tubing, fittings etc.

If single peaks are affected, then it suggests that there might be a specific chemistry problem. The method in use should be examined for areas where the chemistry may not be correct.

Gradient methods, where early eluting peaks are abnormal and later peaks are acceptable may be suffering from pre-column <font style = "color:blue">band broadening</font>. If all the peaks are abnormal, then post-column <font style = "color:blue">band broadening</font> or other changes in the system are the most likely causes.

Isocratic methods, where the early eluting peaks are abnormal and the later peaks are acceptable may be suffering from <font style = "color:blue">extra-column band broadening</font>, injector problems, incorrect detector time constant or incorrect A/D sampling time. If all the peaks are abnormal, then extra-column band broadening or other changes to the system are the most likely causes.

Each table in this section will show an example of the type of chromatography being investigated; it's cause(s) and any corrective action that can be taken.

## No Peak / Missing Peaks

### Thermo Guide

Lack of chromatogram peaks is often due to either the wrong sample being injected, the detector not being switched on or a blockage between the injector and detector lines.

The next most common reason for a lack of peaks is that some part of the sample or mobile phase preparation has been performed incorrectly, so it is always worth revisiting to check that the correct buffer has been used, the sample/solvent pH is correct etc.


<figcaption><b>Problem: No Peak</b></figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 134223.png"/>


Single or multiple missing peaks are usually due to the wrong sample being injected or the sample degrading.  

Equally likely though is a loss of resolution due to column/ solvent inconsistencies.  


<figcaption><b>Problem: Missing Peaks</b></figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 220137.png"/>


[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)


### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: No Peaks/Very Small Peaks</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr VALIGN=TOP class="odd">
      <td><p><img src = "/docs/images/Screenshot 2022-01-27 214859.png"/></p></td><td><p>1. Detector lamp off.<br />
<br />
2. Loose/broken wire between detector and integrator or recorder.<br />
<br />
3. No mobile phase flow.<br />
<br />
4. No sample/deteriorated sample/ wrong sample.<br />
<br />
5. Settings too high on detector or recorder.</p></td>
<td><p>1. Turn lamp on.<br />
<br />
2. Check electrical connections and cables.<br />
<br />
3. “No Flow”.<br />
<br />
4. Be sure automatic sampler vials have sufficient liquid and no air bubbles in the sample. Evaluate system performance with fresh standard to confirm sample as source of problem.<br />
<br />
5. Check attenuation or gain settings. Check lamp status. Auto-zero if necessary.</p></td>
    </tr>
  </tbody>
</table>

[Source Sigma-Aldrich](https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/hplc-troubleshooting-guide?gclid=Cj0KCQiA_8OPBhDtARIsAKQu0gYR2a-bKGOUhDIj6CVZCut9t27HPzLqFqcyZBg51Yp8La_Ecue7cw0aAkZDEALw_wcB#table1)


## Smaller than expected peak

### Thermo Guide

Smaller than expected peaks are often due to either the wrong sample being injected, an incorrect sample volume being injected, or a blockage between the syringe needle and detector. Problems with the syringe plunger sticking in the barrel can occur if the sample contains particulates.

<b>Note</b>: Viscous samples will require a longer draw time. Insufficient draw time will result in a lower volume of sample being injected onto the column and smaller peaks will result.

<figcaption><b>Figure </b>: Smaller than expected peaks</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 135013.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)

### Galak Guide

<figcaption><b>Figure </b>: Small Peak</figcaption>

<img src = "/docs/images/Screenshot 2022-01-25 220646.png"/>

<table style="width:86%;"><colgroup><col style="width: 24%" /><col style="width: 61%" /></colgroup><thead><tr class="header"><th><p>Potential Problems</p></th><th><p>Solution</p></th></tr></thead><tbody><tr class="odd"><td><p>The sample is not pure</p></td><td><p>Using different mobile phase and HPLC columns to separate and compare samples, and select suitable separation conditions.</p></td></tr><tr class="even"><td><p>Column collapse of analysis column or protective column</p></td><td><p>This is a common situation. Change the analysis column or guard column, then compare the peak shape.<br />
Peak splitting tends to occur in all peaks with column head collapse. <br />
Regeneration and cleaning of the HPLC column will improve the separation effect.</p></td></tr><tr class="odd"><td><p>Column capacity decrease</p></td><td><p>After a long time of usage, there are some strong retention components adsorbed in the column, and small injection volumes tend to have peak splitting. The problem can be ameliorated by cleaning the column with a solvent with strong elution ability or by just replacing the column.</p></td></tr><tr class="even"><td><p>The sample solvent does not match the mobile phase or the injection volume is too large</p></td><td><p>When the polarity of the sample solvent is larger than that of the mobile phase, sometimes the peak deformation and splitting phenomenon are easy to occur even if the sample volume is small. It is recommended to dissolve the sample with the mobile phase.</p></td></tr><tr class="odd"><td><p>Improper mobile phase</p></td><td><p>This situation is rare. Some samples under specific chromatographic conditions may have a dynamic equilibrium structure, and the double peak, the double peak can not be separated completely. Change the chromatographic conditions, especially the pH value to make the peak shape normal.</p></td></tr><tr class="even"><td><p>Sample decomposition</p></td><td><p>Unstable samples will be changed into other substances during chromatographic separation and double peaks occur. So using the sample treatment methods or change chromatographic separation conditions.</p></td></tr></tbody></table>


[source](https://galaklc.com/troubleshooting-hplc-peak-shape-problem-ghost-peak/)


## All Peaks Broad

### Thermo Guide

Broad peaks (all) are most often due to errors in instrumentation or column. It is worthwhile investigating the column and guards first as they often are the critical part of the system.

<figcaption><b>Figure </b>: All Peaks Broad</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 173000.png"/>

<figcaption><b>Figure </b>: All Peaks Broad</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 172857.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)

### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Broad Peaks</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 114016.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1.  Mobile phase composition changed.<br />
        <br />  
      2. Mobile phase flow rate too low.<br />
        <br />
      3. Leak (especially between column and detector).<br />
        <br />
      4. Detector settings incorrect.<br />
        <br />
      5. Extra-column effects:<br />  
          a. Column overloaded<br />  
          b. Detector response time or cell volume too large.<br />  
          c. Tubing between column and detector too long or I.D. too large.<br />  
          d. Recorder response time too high.<br />
        <br />
      6. Buffer concentration too low.<br />
        <br />
      7. Guard column contaminated/worn out.<br />
        <br />
      8. Column contaminated/worn out.<br />
        <br />
      9. Void at column inlet.<br />
        <br />
      10. Peak represents two or more poorly resolved compounds.<br />
        <br />
      11. Column temperature too low.
      </p></td>
      <td VALIGN=TOP><p>
      1. Prepare new mobile phase.<br />
        <br />
      2. Adjust flow rate.<br />
        <br />
      3. Check system for loose fittings. Check pump for leaks, salt buildup, and unusual noises. Change pump seals if necessary.<br />
        <br />
      4. Adjust settings.<br />
        <br />
      5.  a. Inject smaller volume (e.g., 10 μL vs. 100 μL) or 1:10 and 1:100 dilutions of sample.  <br />
          b. Reduce response time or use smaller cell.  <br />
          c. Use as short a piece of 0.007-0.010" I.D. tubing as practical.  <br />
          d. Reduce response time.<br />
        <br />
      6. Increase concentration.<br />
        <br />
      7. Replace guard column.<br />
        <br />
      8. Replace column with new one of same type. If new column does not provide narrow peaks, flush old column (Table 2), then retest.<br />
        <br />
      9. Replace column or open inlet end and fill void.<br />
        <br />
      10. Change column type to improve separation.<br />
        <br />
      11. Increase temperature. Do not exceed 75 °C unless higher temperatures are acceptable to column manufacturer.
      </p></td>
    </tr>
  </tbody>
</table>

## Early Eluting Peaks Broad

Broad early eluting peaks are most commonly associated with sample overload or incorrect system plumbing.

<figcaption><b>Figure </b>: Early Eluting Peaks Broad</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 135436.png"/>

<figcaption><b>Figure </b>: Early Eluting Peaks Broad</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 135306.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)


## All Peaks Doubling

### Thermo Guide
The most common cause of peak doubling can be either blockage prior to the column or column or guard voiding.

<figcaption><b>Figure </b>: All Peaks Doubling</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 173209.png"/>

<figcaption><b>Figure </b>: All Peaks Doubling</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 173331.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)

### Galak

1. Column

If every peak has a double peak in the sample analysis process  (the shorter the appearance time, the less likely it is to have a double peak), especially the analysis of the pure sample, there is a problem in the column (column head damaged, stationary phase in the column head dirty or lost).

If the sample injection volume is small and the column works well, the peak is a large peak with a small peak, it is not trailing. This may be caused by the column block. Wash the column with mobile phase solvent or acid cleaning or other solvents in a reverse direction, the block in the column will be washed away. Forward direction washing sometimes also can solve this problem.

If the peak shape is trailing with little difference between two peaks, it may be caused by the dirty or loss of the stationary phase in the column header.

2. Solvent polarity and injection volume

For reversed-phase chromatography, the common mobile phases are methanol, acetonitrile, and water. Other additives are added to improve the separation performance. The sample is generally dissolved in a soluble solvent with the mobile phase, and the best solution is to use the mobile phase. When the solvent is strong polarity reagent (such as pure methanol, acetonitrile, pure ethanol) and the analysis system is mainly water, the double peaks phenomenon will occur with a large injection volume of pure sample (such as quantitative tube for 20ul): a peak combine with a smaller peak (different every time) with a tail, the retention time (relative to less sample quantity) will be earlier. If the injection volume is reduced by more than half, the peak shape will return to normal. This is because the solvent polarity of the sample is too different from that of the mobile phase, the mobile phase has no time to dilute it to reach equilibrium.

Another reason is that the injection volume is not necessarily large, but the absolute amount is large, and the two peaks on the chromatogram are close together, basically at the same height, without trailing (if the peak appearance time is very short, it may also be a column problem). If it is caused by a large injection and overload column, dilute the sample before injection.

3. Sample characteristics

Some samples, due to the characteristics of their chemical structure, have the phenomenon of tautomerism, and the tautomerism can not be separated, but in a dynamic equilibrium existence. In the chromatographic analysis, under a specific condition, a substance will appear double peaks. These double peaks are very close with the same height and no tail. The double peak phenomenon will disappear when the condition is changed (especially pH).

4. Device parameters

The parameters of the record are generally set internally and do not need to be modified without special needs. The HPLC recording time is generally 5ms. If the recording interval is shortened, one peak will become two or more peaks.


* Column contamination  
* Frit block  
* Column head collapsing (liquid phase pH≥7). Choose special columns will solve it.  
* Solvent effect. The solvent is more polar than the mobile phase. It is also decided by the sample injection volume.
* Bubbles in the detector

[source](https://galaklc.com/troubleshooting-hplc-peak-shape-problem-ghost-peak/)


### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Split Peaks </b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 101043.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Contamination on guard or analytical column inlet.<br />
        <br />
      2. Partially blocked frit.<br />
        <br />
      3. Small (uneven) void at column inlet.<br />
        <br />
      4. Sample solvent incompatible with mobile phase.
      </p></td>
      <td VALIGN=TOP><p>
      1. Remove guard column (if present) and attempt analysis. Replace guard column if necessary. If analytical column is obstructed, reverse and flush. If problem persists, column may be clogged with strongly retained contaminants. Use appropriate restoration procedure (Table 2). If problem still persists, inlet frit is probably (partially) plugged. Change frit or replace column.<br />
        <br />
      2. Replace frit (see above).<br />
        <br />
      3. Repack top of column with pellicular particles of same bonded phase functionality. Continue using the column in reverse flow direction.<br />
        <br />
      4. Adjust solvent. Whenever possible, inject samples in mobile phase.
      </p></td>
    </tr>
  </tbody>
</table>


## Fronting Peaks

### Thermo Guide
Fronting peaks are very often due to large injection volumes of a sample that is dissolved in solvents that are incompatible with the mobile phase being used. The next most common cause of peak fronting is a voided or contaminated guard or column.

<figcaption><b>Figure </b>: Fronting Peaks</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 212915.png"/>

<figcaption><b>Figure </b>: Fronting Peaks</figcaption>

<img src = "/docs/images/Screenshot 2022-01-12 213931.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)

### Galak Guide

<table style="width:100%;"><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup>
<thead>
<tr class="header"><th><p>Potential Problem</p></th><th><p>Solution</p></th></tr>
</thead>
<tbody>
<tr class="odd"><td><p>Improper solvent.</p></td><td><p>Choosing the appropriate solvent.</p></td></tr>
<tr class="even"><td><p>The sample is overloaded.</p></td><td><p>Reduce the injection volume.</p></td></tr>
<tr class="odd"><td><p>The column temperature is too low. </p></td><td><p>Raising the column temperature.</p></td></tr>
<tr class="even"><td><p>Column damaged.</p></td><td><p>Replace column.</p></td></tr>
</tbody>
</table>

The main reason for the tailing peak and the leading peak is the improper selection of the mobile phase, which can be better improved by adjusting the polarity of the mobile phase or adding acid appropriately. Generally, acid and base in the mobile phase have a great influence on the tailing peak and the leading peak. The leading peak may be caused by column overload, and the tailing peak may be caused by sample contamination. Choosing the appropriate mobile phase and adjusting the pH value will improve this situation. Tailing peak is related to the column, maybe overload, dilute the sample, or use a new column. Sometimes the tailing peak is caused by the unseparated impurities with similar organic properties. You may need to optimize the analysis method or replace the column. Tailing peaks may also cause by column effect decline or column collapse after long column use time. Sometimes, tailing peaks are related to the properties of the sample, which some chemicals need to be added in the mobile phase to optimize the peak shape (depend on the specific situation).  

[source](https://galaklc.com/troubleshooting-hplc-peak-shape-problem-ghost-peak/)

### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Fronting Peaks</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 104924.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Column overloaded.<br />
        <br />
      2. Sample solvent incompatible with mobile phase.<br />
        <br />
      3. Shoulder or gradual baseline rise before a main peak may be another sample component.
      </p></td>
      <td VALIGN=TOP><p>
      1. Inject smaller volume (e.g., 10 μL vs. 100 μL). Dilute the sample 1:10 or 1:100 fold in case of mass overload.<br />
        <br />
      2. Adjust solvent. Whenever possible, inject samples in mobile phase. Flush polar bonded phase column with 50 column volumes HPLC grade ethyl acetate at 2-3 times the standard flow rate, then with intermediate polarity solvent prior to analysis.<br />
        <br />
      3. Increase efficiency or change selectivity of system to improve resolution. Try another column type if necessary (e.g., switch from nonpolar C18 to polar cyano phase).
      </p></td>
    </tr>
  </tbody>
</table>


## Tailing Peaks

### Thermo Guide

Tailing peaks are typically caused by column degradation or inlet contamination. Carefully maintained columns and guards will considerably reduce the incidence of tailing peaks.

<figcaption><b>Figure </b>: Tailing Peaks</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 214244.png"/>


<figcaption><b>Figure </b>: Tailing Peaks</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 214203.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)

### Galak Guide

<table style="width:100%;">
  <colgroup>
    <col style="width: 50%" /><col style="width: 50%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Potential Problem </p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr VALIGN=TOP class="odd">
      <td><p>
      Interference peak.
      </p></td>
      <td><p>
      Separation under optimized conditions.
      </p></td>
    </tr>
    <tr VALIGN=TOP class="even">
      <td><p>
       Column collapse.
      </p></td>
      <td><p>
      Replace column.
      </p></td>
    </tr>
    <tr VALIGN=TOP class="odd">
      <td><p>
      Mobile phase pH is not appropriate.
      </p></td>
      <td><p>
      Adjust the pH value. Add additives to eliminate secondary effects (interaction between components in the mobile phase and the column).
      </p></td>
    </tr>
    <tr VALIGN=TOP class="even">
      <td><p>
      Improperly connected pipeline.
      </p></td>
      <td><p>
      Large dead volume. Reconnect the pipeline.
      </p></td>
    </tr>
    <tr VALIGN=TOP class="odd">
      <td><p>
      The injection volume is too large.
      </p></td>
      <td><p>
      Reduce it.
      </p></td>
    </tr>
  </tbody>
</table>

The main reason for the tailing peak and the leading peak is the improper selection of the mobile phase, which can be better improved by adjusting the polarity of the mobile phase or adding acid appropriately. Generally, acid and base in the mobile phase have a great influence on the tailing peak and the leading peak. The leading peak may be caused by column overload, and the tailing peak may be caused by sample contamination. Choosing the appropriate mobile phase and adjusting the pH value will improve this situation. Tailing peak is related to the column, maybe overload, dilute the sample, or use a new column. Sometimes the tailing peak is caused by the unseparated impurities with similar organic properties. You may need to optimize the analysis method or replace the column. Tailing peaks may also cause by column effect decline or column collapse after long column use time. Sometimes, tailing peaks are related to the properties of the sample, which some chemicals need to be added in the mobile phase to optimize the peak shape (depend on the specific situation).  

[source](https://galaklc.com/troubleshooting-hplc-peak-shape-problem-ghost-peak/)


### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Peaks Tail on Initial and Later Injections</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 102717.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Sample reacting with active sites.<br />
        <br />
      2. Wrong mobile phase pH.<br />
        <br />
      3. Wrong column type.<br />
        <br />
      4. Small (uneven) void at column inlet.<br />
        <br />
      5. Wrong injection solvent.
      </p></td>
      <td VALIGN=TOP><p>
      1. First check column performance with standard column test mixture. If results for test mix are good, add ion pair reagent or competing base or acid modifier.<br />
        <br />
      2. Adjust pH. For basic compounds, lower pH usually provides more symmetric peaks.<br />
        <br />
      3. Try another column type (e.g., deactivated column for basic compounds).<br />
        <br />
      4. See Split Peaks.<br />
        <br />
      5. Peaks can tail when sample is injected in stronger solvent than mobile phase. Dissolve sample in mobile phase.
      </p></td>
    </tr>
  </tbody>
</table>


<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Tailing Peaks </b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 104133.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Guard or analytical column contaminated/worn out.<br />
        <br />
      2. Mobile phase contaminated/deteriorated.<br />
        <br />
      3. Interfering components in sample.
      </p></td>
      <td VALIGN=TOP><p>
      1. Remove guard column (if present) and attempt analysis. Replace guard column if necessary. If analytical column is source of problem, use appropriate restoration procedure (Table 2). If problem persists, replace column.<br />
        <br />
      2. Check make-up of mobile phase.<br />
        <br />
      3. Check column performance with standards.
      </p></td>
    </tr>
  </tbody>
</table>


## Flat Topped Peaks

Flat-topped peaks are most often caused by either large injection volumes of dilute sample or by small injection volumes of strong sample solution.

<figcaption><b>Figure </b>: Flat Topped Peaks</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 214528.png"/>


<figcaption><b>Figure </b>: Flat Topped Peaks</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 214641.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)


## Change in Peak Height (one or more peaks)

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: </b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 115232.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. One or more sample components deteriorated or column activity changed.<br />
        <br />
      2. Leak, especially between injection port and column inlet. (Retention also would change.)<br />
        <br />
      3. Inconsistent sample volume.<br />
        <br />
      4. Detector or recorder setting changed.<br />
        <br />
      5. Weak detector lamp.<br />
        <br />
      6. Contamination in detector cell.
      </p></td>
      <td VALIGN=TOP><p>
      1. Use fresh sample or standard to confirm sample as source of problem. If some or all peaks are still smaller than expected, replace column. If new column improves analysis, try to restore the old column, following appropriate procedure (Table 2). If performance does not improve, discard old column.<br />
        <br />
      2. Check system for loose fittings. Check pump for leaks, salt buildup, unusual noises. Change pump seals if necessary.<br />
        <br />
      3. Be sure samples are consistent.<br />
        For fixed volume sample loop, use 2-3 times loop volume to ensure loop is completely filled. Be sure automatic sampler vials contain sufficient sample and no air bubbles. Check syringe-type injectors for air. In systems with wash or flushing step, be sure wash solution does not precipitate sample components.<br />
        <br />
      4. Check settings.<br />
        <br />
      5. Replace lamp.<br />
        <br />
      6. Clean cell.
      </p></td>
    </tr>
  </tbody>
</table>


## Rounded Peaks

### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Rounded Peaks </b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 105646.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Detector operating outside linear dynamic range.<br />
        <br />
      2. Recorder gain set too low.<br />
        <br />
      3. Column overloaded.<br />
        <br />
      4. Sample-column interaction.<br />
        <br />
      5. Detector and/or recorder time constants are set too high.
      </p></td>
      <td VALIGN=TOP><p>
      1. Reduce sample volume and/or concentration.<br />
        <br />
      2. Adjust gain.<br />
        <br />
      3. Inject smaller volume (e.g., 10 μL vs. 100 μL) or 1:10 or 1:100 dilution of sample.<br />
        <br />
      4. Change buffer strength, pH, or mobile phase composition. If necessary, raise column temperature or change column type. (Analysis of solute structure may help predict interaction.)<br />
        <br />
      5. Reduce settings to lowest values or values at which no further improvements are seen.
      </p></td>
    </tr>
  </tbody>
</table>


## Extra Peaks

### Thermo Guide

Extra peaks in chromatograms are more often than not due to contamination or degradation of the sample, mobile phase or column. To check if the extra peak(s) is/are in the sample alone, perform a blank injection of sample solvent. The peak(s) should be absent.  

<figcaption><b>Figure </b>: Extra Peaks</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 220435.png"/>


<figcaption><b>Figure </b>: Extra Peaks</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 220539.png"/>

## Negative Peaks

### Thermo Guide

Negative peaks are most often caused by differences in refractive index between the sample solvent, sample and mobile phase.

They are also caused after routine maintenance when the system has not been reconfigured correctly.


<figcaption><b>Figure </b>: Negative Peaks</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 214958.png"/>


<figcaption><b>Figure </b>: Negative Peaks</figcaption>
<img src = "/docs/images/Screenshot 2022-01-12 215034.png"/>

[source](https://assets.thermofisher.com/TFS-Assets/CMD/Product-Guides/TG-20421-HPLC-Troubleshooting-Guide-TG20421-EN.pdf)

### Galak Guide

<figcaption><b>Figure </b>: Negative Peak</figcaption>
<img width="320" height="200" src = "/docs/images/Screenshot 2022-01-25 222041.png"/>


<table style="width:100%;">
  <colgroup>
    <col style="width: 50%" /><col style="width: 50%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Potential Problem </p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr VALIGN=TOP class="odd">
      <td><p>
      The mobile phase absorption background value is too high.
      </p></td>
      <td><p>
      Change the detection wavelength appropriately.
      </p></td>
    </tr>
    <tr VALIGN=TOP class="even">
      <td><p>
       Air is entered during the injection. Using exhaust treatment.
      </p></td>
      <td><p>
      Re-inject when the baseline is stable.
      </p></td>
    </tr>
    <tr VALIGN=TOP class="odd">
      <td><p>
      The absorption of sample components is lower than that of the mobile phase.
      </p></td>
      <td><p>
      Change the mobile phase or the detection wavelength.
      </p></td>
    </tr>
    <tr VALIGN=TOP class="even">
      <td><p>
      The solution of the sample preparation is different from the mobile phase.
      </p></td>
      <td><p>
      Re-prepare the sample with the same solvent as the flow, or dilute the sample.
      </p></td>
    </tr>
  </tbody>
</table>
[source](https://galaklc.com/troubleshooting-hplc-peak-shape-problem-ghost-peak/)


### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Negative Peaks</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 121022.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Recorder leads reversed.<br />
        <br />
      2. Refractive index of solute less than that of mobile phase (RI detector).<br />
        <br />
      3. Sample solvent and mobile phase differ greatly in composition (vacancy peaks).<br />
        <br />
      4. Mobile phase more absorptive than sample components to UV wavelength.
      </p></td>
      <td VALIGN=TOP><p>
      1. Check polarity.<br />
        <br />
      2. Use mobile phase with lower refractive index, or reverse recorder leads.<br />
        <br />
      3. Adjust or change sample solvent. Dilute sample in mobile phase whenever possible.<br />
        <br />
      4. a. Change polarity when using indirect UV detection, or<br />
         b. Change UV wavelength or use mobile phase that does not adsorb chosen wavelength.
      </p></td>
    </tr>
  </tbody>
</table>


## Ghost Peak

### Galak Guide


<figcaption><b>Figure </b>: Ghost peak is no relationship with the previous sample. Ghost peaks also appear with blank samples. The retention time may differ from sample tests.</figcaption>
<img width = "320" height = "200" src = "/docs/images/Screenshot 2022-01-26 094032.png"/>


<figcaption><b>Figure </b>: This is caused by the previous sample residue. Small peaks that are similar sample peaks will appear.</figcaption>
<img width = "320" height = "200" src = "/docs/images/Screenshot 2022-01-26 094058.png"/>

[source](https://galaklc.com/troubleshooting-hplc-peak-shape-problem-ghost-peak/)


### Sigma-Aldrich Guide

<table style="width:100%;">
  <caption style="text-align:left", align = "top"><b>Problem: Ghost Peak</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p>Problem</p></th><th><p>Probable Cause</p></th><th><p>Remedy/Comments</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      <img src = "/docs/images/Screenshot 2022-01-28 121446.png"/>
      </p></td>
      <td VALIGN=TOP><p>
      1. Contamination in injector or column.<br />
        <br />
      2. Late eluting peak (usually broad) present in sample.
      </p></td>
      <td VALIGN=TOP><p>
      1. Flush injector between analyses (a good routine practice). If necessary, run strong solvent through column to remove late eluters. Include final wash step in gradient analyses, to remove strongly retained compounds.<br />
        <br />
      2. a. Check sample preparation.<br />
         b. Include (step) gradient to quickly elute component.
      </p></td>
    </tr>
  </tbody>
</table>


## Diagrams for Troubleshooting Abnormal Peak Shape


<div class="mermaid">
  graph LR
  A([Smaller peak <br />  No Peak <br />  Missing Peak]) --> 1.1[Sample]
  1.1 --> 1.1.1[no sample?]
  1.1 --> 1.1.2[sample deteriorated?]  
  1.1 --> 1.1.3[wrong sample?]
  1.1 --> 1.1.4[Wrong position?]
  1.1 --> 1.1.5[Insufficient sample?]
  1.1 --> 1.1.6[Needle blocked?]
  A([Smaller peak <br />  No Peak <br />  Missing Peak]) --> 1.2[Mobile phase]
  1.2 --> 1.2.1[Is solvent correct?]
  1.2 --> 1.2.2[correct proportions of solvents?]
  1.2 --> 1.2.3[correct gradient or isocratic path] --> 1.2.3.1[gradient sufficient?]
  1.2 --> 1.2.4[no flow? low flow?]
  1.2.4 --> 1.2.4.1[flow rate accurate?]      
  1.2.4 --> 1.2.4.2[pump works?]
  1.2.4 --> 1.2.4.3[blockage?] --> 1.2.4.2.1[pressure?]
  A([Smaller peak <br />  No Peak <br />  Missing Peak]) --> 1.3[Column]
  1.3 --> 1.3.1[Resolution lost?] --> 1.3.1.1[check the efficiency of the original column]
  1.3 --> 1.3.2[column dimension? particle size?]  
</div>


<div class = "mermaid">
  graph LR
  A([Peak Broaden]) --> 1.1[Sample]
  1.1 --> 1.1.1[Solvent strong?]
  1.1 --> 1.1.2[Sample overloaded?]
  A([Peak Broaden]) --> 1.6[Mobile phase]
  1.6 --> 1.6.1[composition changed?]
  1.6 --> 1.6.2[flow rate slow?]
  1.6 --> 1.6.3[Leak?]
  A([Peak Broaden]) --> 1.7[Buffer]
  1.7 -->1.7.1[Concentration is too slow]
  A([Peak Broaden]) --> 1.3[System equilibrium]
  1.3 --> 1.3.1[not equilibrium yet?]
  A([Peak Broaden]) --> 1.4[Column]
  1.4 --> 1.4.1[Contaminated? Degraded?]
  1.4 --> 1.4.2[Incorrect?]
  1.4 --> 1.4.4[Column temperature low?]
  A([Peak Broaden]) --> 1.5[Guard]
  1.5 --> 1.5.1[Contaminated? Degraded?]
</div>


<div class = "mermaid">
  graph LR
  A([Fronting Peaks]) --> 1.1[Sample]
  1.1 --> 1.1.1[Injection disrupting equilibrium?]
  1.1 --> 1.1.2[Sample overloaded?]
  1.1 --> 1.1.3[Sample solvent improper?]
  A([Fronting Peaks]) --> 1.2[Column]
  1.2 --> 1.2.1[Column voiding?]
  1.2 --> 1.2.2[Column damage?]
  1.2 --> 1.2.3[Column temperature unstable?]
  1.2 --> 1.2.4[Switch to a new type of column]
  A([Fronting Peaks]) --> 1.3[Guard Column]
  1.3 --> 1.3.1[contaminated? degraded?]
  A([Fronting Peaks]) --> 1.4[Mobile phase]
  1.4 --> 1.4.1[adjust polarity?]
  1.4 --> 1.4.2[add acid?]
</div>


<div class = "mermaid">
  graph LR
  A([Tailing Peaks]) --> 1.1[Sample]
  1.1 --> 1.1.1[solvent immiscibility]
  1.1 --> 1.1.2[Injector: malfunctioning valves?]
  1.1 --> 1.1.3[Sample overloaded?]
  1.1 --> 1.1.4[Sample solvent improper?]
  1.1 --> 1.1.5[Sample reacts with active sites]
  A([Tailing Peaks]) --> 1.2[Column]
  1.2 --> 1.2.1[Contaminated? degraded?] --> 1.2.1.1[check column performance]
  A([Tailing Peaks]) --> 1.3[Guard Column]
  1.3 --> 1.3.1[contaminated? degraded?]
  A([Tailing Peaks]) --> 1.4[Mobile phase]
  1.4 --> 1.4.1[Contaminated? deteriorated?] --> 1.4.1.1[check make-up of mobile phase]
  1.4 --> 1.4.2[pH?]
</div>
____
<figcaption><b>Figure </b>: </figcaption>
<img src = "/docs/images/"/>
