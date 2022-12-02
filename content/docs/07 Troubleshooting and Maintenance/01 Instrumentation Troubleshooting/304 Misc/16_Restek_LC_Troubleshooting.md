---
authors: edited by Lenny Lin
categories: 
date: "2022-01-12"
description: 
draft: false
lastmod: "2022-01-12"
series: 
tags: [Sensitivity]
title: Restek - Effective LC Troubleshooting Symptom-based Strategies and Solutions
toc: true
---
Summary of sensitivity reduction
1. Simple potential causes:  
  1.1) sample preparation,   
  &emsp;abnormal storage temperature,   
  &emsp;storage time,  
  &emsp;abnormal extraction,  
  &emsp;abnormal clean-up,  
  1.2) LC system,  
  &emsp;Dilution error,  
  &emsp;autosampler needle not reaching sample,  
  &emsp;incorrect injection volume,  
  &emsp;abnormal LC back pressure,  
  &emsp;Leak,  
  &emsp;mobile phase unstable (modifier, prepared date, )  
  1.3) Mass spectrometer system,  
  &emsp;non-asymmetric spray (due to clog)  
  &emsp;Electron multiplier voltage error,   
  &emsp;the declustering potential error,  
  &emsp;the collision energy error  
  &emsp;the collision exit cell potential error  
  &emsp;GS1 pressure - nebulizer gas error  
  &emsp;GS2 pressure - turbo gas error  
  &emsp;Curtain gas pressure error  
  &emsp;Ion spray voltage error  
  &emsp;test  
  1.4) System monitoring,  
  &emsp; monitoring charts of internal standards, blank, calibrators,   
  1.5) Data processing,  
  &emsp;Calculation error (dilution factor),  
  &emsp;Peak integration error (baseline issue, noise),  
  &emsp;Retention time shift,  
  &emsp;
  &emsp;
  &emsp;
  
2. Complex potential causes:  
  &emsp;Analyze new known standard  
  &emsp;Analyze blank  
  &emsp;Infuse standard in 50-50 mobile phase solution to the mass spectrometer  
  &emsp;Dry run  
  &emsp;
  &emsp;
  &emsp;
  


<!--more-->
---

- Tips for reestablishing a smooth baseline.
- Guidance on diagnosing and solving common peak problems.
- Best practices for managing system back pressure.

Every instrument and every method will at some point experience a deterioration in performance that requires troubleshooting. When this occurs, the first—and most essential—part of LC troubleshooting is knowing what “normal” looks like. By carefully documenting instrument qualification tests, maintenance events, and system suitability results, you create an invaluable source of comparison that establishes normal ranges and can reveal where problems may lie. For example, rerunning a flow rate accuracy test and comparing it to previous values can help establish whether a flow rate issue is the root cause behind retention time shifts. In this article, we explore common problems with baseline variation, chromatographic peaks, and system pressure and offer practical tactics for resolving them. Use these general guidelines in combination with equipment manuals and your laboratory’s standard operating procedures to get your instrument back into service quickly and effectively.


## Reestablishing a Smooth Baseline


<figure>
  <img width ="360" src = "/docs/images/figure-article-gnar3485-01.webp"/>
  <figcaption><b>Figure 1</b>: Abnormal baselines that are commonly encountered in LC troubleshooting</figcaption>
</figure>

Encountering an inconsistent baseline is not unusual in LC laboratories. Variation can be caused by a number of factors, and determining if there is a pattern can help you establish the cause (Figure 1). <mark class = "lemon">If you are seeing an erratic baseline, it is likely caused by a leak or an air bubble, so checking all fittings, confirming the degasser is working, and purging your system with fresh mobile phase should stabilize the baseline</mark>. If you are using a UV detector, a noisy baseline can also indicate that it is time to change the detector lamp or flow cell. However, if there is regularity to the changes in the baseline, it may be a pump or piston issue, and routine maintenance of those parts should resolve the problem. Finally, if the baseline is looking bad overall, a thorough system cleaning is recommended. Note that ambient temperature changes can also cause baseline fluctuations, so using a column oven or insulating the column and tubing may also restore performance.


## Troubleshooting Peak Issues

Troubleshooting peak problems is necessary during both routine analysis and method development, but the changes that are allowable under those two scenarios are different. Issues with poor peak shape, sensitivity, and retention that develop over time in an established method that is otherwise performing well indicate a change has occurred (e.g., system leak, mobile phase deterioration, guard contamination, etc.) and resolving it through maintenance should restore performance. However, some of the tips discussed below, such as adding buffer to mobile phases or changing the column temperature, should not be made during routine analysis because they may require additional validation before implementation.

In contrast, peak issues seen during method development indicate further changes to method parameters may be needed, and more opportunities for improvement are available than when they are encountered with an established method. During method development, in addition to using the LC troubleshooting guidelines below, the sample preparation method, column stationary phase, and analytical conditions can be optimized for the matrices and compounds to be analyzed. When making changes to improve chromatographic peaks, it is important to first understand what factors can or cannot be changed based on your laboratory’s standard operating procedures.


## Improving Poor Peak Shape

Sharp, symmetrical peaks improve accuracy and sensitivity, but many factors can cause peaks to tail, front, split, or broaden. These types of peak distortions often lead to other problems, such as shifting retention times or coelution. If you observe distorted peak shapes either during routine analysis or method development, the LC troubleshooting tips in Table I will help you diagnose the problem based on the symptoms you observe in the chromatogram.

Table I: LC troubleshooting tips for improving peak shape.

[Untitled](https://www.notion.so/796fc18dddb84768a66e5cf13065864f)

## Dealing With a Decrease in Sensitivity

<mark class = "lemon">A loss in sensitivity can indicate problems with either the sample preparation or the analytical system</mark>.   

First, confirm that the sample preparation procedure was followed correctly, including storage temperature and time, and verify that system parameters are set correctly and functioning properly. Always check for `obvious problems` (e.g., calculation/dilution error, autosampler needle not reaching sample, incorrect injection volume, wrong detector settings, no mobile phase flow, detector or lamp turned off, integrity of the reference standard, etc.) before looking for more complex issues. Having a coworker double check your work can be invaluable because it is often easier for an independent person to spot problems than it is for someone who is already familiar with the work.

Once simple problems have been ruled out, <mark class = "lemon">analyzing a known standard is a helpful diagnostic tool for LC troubleshooting</mark>. If results are within the expected range, the system is performing well, and the problem is in the sample preparation or handling; however, <mark class = "lemon">if low response is also seen for the standard, the problem is likely with the instrument</mark>. It is also possible that analytes are simply outside of the instrument’s sensitivity range. In this case, sample concentration may bring them within range, but care must be taken to prevent the loss of more volatile analytes.

If poor response is seen only in the first few injections, it is possible that the sample is adsorbing to active sites in the sample loop or column. Using a passivation solution or making a few preliminary sample injections to condition the system and reduce adsorption prior to actual sample analysis may help restore analyte response. If response has decreased across all peaks, this is likely caused by calculation errors, incorrect dilutions, or a decrease in injection volume that may result from leaks, system malfunctions, programming errors, or use of the wrong size sample loop. If a catastrophic loss of retention is observed, it is possible that phase dewetting has occurred and the column must be regenerated or replaced, but this is a relatively rare event compared to other causes.

<mark class = "lemon">For LC-MS analysis, there could be additional causes responsible for a decrease in sensitivity</mark>. Issues with the MS analyzer can be a common source, so verifying that the MS performance is at its best is essential. Directly infusing the tuning solution into the MS (bypassing the LC system) is an easy step that provides useful information for troubleshooting. Since there are several possible causes of loss in MS sensitivity (e.g. cleanliness of the optics, buffer precipitate in the MS entrance, need to change an electron multiplier, ionization source performance, compounds tuning, etc.) we recommend checking with your manufacturer for specific troubleshooting information. Ion suppression due to matrix interferences can also cause poor response in LC-MS systems, but this typically must be addressed with major method changes that may require revalidation, such as better sample preparation procedures, use of internal or matrix-matched standards, and changes to the mobile phase composition.

## Stabilizing Shifting Retention Times

<img width ="360" src = "/docs/images/figure-article-gnar3485-03.jpg" style ="float: left" HSPACE="10" VSPACE="10"/>
For accurate identification and quantification, it is critical that analytes always elute at the same retention time. However, it is not uncommon to observe retention time shifts during routine analysis, and there are a number of possible causes. As a first step in LC troubleshooting, verify that all method settings are correct and that the mobile phase was properly prepared (particularly if you see a big change instead of a slight drift). Preparing fresh mobile phase is an easy way to eliminate problems caused by composition changes due to evaporation, reactions, contamination, or incomplete mixing. Also, if you are transferring an existing method to a new instrument, be sure to account for any difference in `dwell volume` between the instruments because that can significantly affect retention time. Other possible causes include the following:

1. Incorrect or variable flow rate—manually confirm that the flow rate is correct and verify that there are no leaks in the system.
2. Temperature fluctuations—always use a thermostatically controlled column compartment.
3. Solvent mismatch—make sure that the sample solvent is compatible with the starting mobile phase (try to match both the aqueous:organic ratio and the buffer strength).
4. Sample overloading—don’t inject more sample than the column can hold.
5. Column contamination/clogging—flush the column to remove any particulates, particularly if back pressure is also elevated. If this does not work, it may be time to replace the column. Using a guard column is recommended to minimize contamination and maximize column lifetime.
6. Matrix interferences—analyze a solvent standard and compare it to your sample to see if the shifting peaks are actually matrix components.
7. Insufficient column equilibration—allow more time between runs, sufficient time for passing 10 column volumes is recommended. Note: Column equilibration may take longer for HILIC analyses.
8. Air bubbles—purge air from pump and ensure the mobile phase is degassed. Inspect pump seals and change if leaks are evident.

Occasionally, ghost peaks will appear at unexpected times during analysis. This can be tested by making a solvent injection after a sample injection. If a peak appears, it is likely a late-eluting peak carried over from the previous sample injection. In this situation, increasing the flow rate, extending the run time, or adding a gradient step may help eliminate the carryover problem. The risk of carryover can also be reduced by minimizing extra system volume by plumbing the LC with shorter, smaller diameter tubing and zero-dead-volume connections because this will reduce the places that sample can build up. In addition, needle wash solvents and needle wash parameters are important to consider in order to reduce carryover. Ghost peaks can also be caused by contamination in the mobile phase, guard column, or analytical column. This can be resolved by preparing fresh, degassed mobile phase; replacing the guard column; and replacing your analytical column (but first try flushing it according to the manufacturer’s recommended cleaning procedures).

## Restoring Normal System Pressure

*Diagnosing the Cause of Increased Back Pressure*

Increased back pressure is one of the most common of all LC troubleshooting issues, but it is important to remember that not all pressure changes indicate a problem. For example, pressure will change during gradient analysis as mobile phase viscosity increases (maximum viscosities are at ~50:50 for methanol:water and ~20:80 for acetonitrile:water). So, it is important to know what is normal for your setup in order to diagnose a problem. It is also important to work within the pressure limits of your LC (e.g., do not use <2.7 µm columns in instruments with a 400 bar limit). When abnormally high back pressure is observed, it indicates a blockage exists somewhere in the system, and the first step in resolving it is to identify the location by isolating one potential source at a time following the steps in Figure 2.
<figure>
<img width ="720" src = "/docs/images/figure-article-gnar3485-04.jpg"/>
<figcaption><b>Figure 2</b>: LC troubleshooting steps for locating system blockages that cause increased back pressure</figcaption>
</figure>

## Removing Column Clogs and Contaminants

Increased back pressure and decreased chromatographic performance can indicate column contamination or blockage. Flushing the column and preventing future blockage using the following guidelines can solve the problem and extend the life of your analytical column.


## Treatment

Flushing HPLC and UHPLC columns in the direction shown on the column with a series of solvents can be an effective way to remove both chemical contaminants and particulates that have formed clogs. Use a minimum of 20 column volumes of each solvent and flush in the order shown in Table II below. Following regeneration, always store your column in the solvent recommended by the column manufacturer.

Table II: Solvent Sequence for Column Flushing

<img width ="720" height= "400" src = "/docs/images/Screenshot 2022-07-16 213530.png" />


## Prevention

- Always use fresh, filtered mobile phases to remove particulates and prevent bacterial growth. Keep your mobile phase bottles capped to avoid contamination. If using MS analyzers, make sure you use LC-MS grade solvents and additives.
- Filter samples to remove matrix particulates; syringe filters and filter vials simplify this task.
- Confirm the sample solvent and mobile phases are compatible. Solvent mismatch can cause sample components or buffer salts to precipitate and form clogs.
- Use a guard column or precolumn filter to protect your analytical column. Always select a guard system and phase that matches the analytical column.
- Regularly inspect and replace pump seals, auto-injector rotors, inline filters, and needle seats before normal wear and tear causes them to break down and shed particles into the flow stream.

Although less common, it is also possible to encounter pressures that are too low. In this scenario, leaks are a usually the culprit, so check your fittings and pump carefully for signs of moisture or precipitates. If tightening or replacing the fittings does not solve the problem, it may be time to replace the pump seals. Trapped air bubbles or a stuck check valve can also cause pressure drops, but both issues can generally be fixed by flushing the system with degassed mobile phase or an appropriate solvent, such as isopropyl alcohol. If this does not resolve this problem, it may be time to replace the check valves. Some leaks could be due to scratches in the rotor seal in six-port valves. The leak may not be visible, but it will cause a drop in the pressure and flow. When looking for leaks or measuring flow rate accuracy, be sure to utilize an old column or a flow restrictor. In addition to pressure drops, leaks can cause other chromatographic problems, such as increased retention, decreased signal, or even automatic instrument shut down. To prevent this, make it a daily practice to inspect fittings for residue, and wipe tubing with a lab tissue to detect moisture. Gently retightening fittings and regularly replacing tubing, fittings, and seals as part of your routine maintenance plan is a good way to prevent catastrophic leaks and unexpected downtime. Restek’s <a href = "https://www.restek.com/row/technical-literature-library/articles/routine-LC-maintenance/" target="_blank" rel="noopener noreferrer">Routine LC Maintenance guide</a> is a helpful starting place when developing or refining a maintenance plan. 


## Reference

<a href = "https://www.restek.com/globalassets/pdfs/literature/gnar3485-unv.pdf" target="_blank" rel="noopener noreferrer">Restek: Effective LC Troubleshooting: Symptom-Based Strategies and Solutions</a>


##  Summary

LC troubleshooting is an essential part of generating accurate and reliable data. While there are many potential causes of poor performance, careful observation of the chromatographic symptoms, testing of one possible cause at a time, and comparison to an established “normal” state will help you quickly and effectively identify the root cause. Finally, working any lessons learned into a routine maintenance plan will help prevent future problems and keep your instrument running more efficiently.  



