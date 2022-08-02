---
authors: Lenny Lin
categories: null
date: "2022-03-17"
description:  
draft: false
lastmod: "2022-07-13"
series: null
tags: [Sensitivity]
title: How to improve the sensitivity
toc: true
---



<!--more-->

Sensitivity of MS

Sensitivity definition: signal-to-noise 

## From mass spectrometer hardware perspective, what could affect the sensitivity?

good asymmetric spray.

less matrix effect.  

How do the MS components work? and how do the MS components impact the sensitivity?

1) Electron (not electronic) multiplier.  The very weak ion current exits the quadrupole, ions hit the electron multiplier surface, and produce electrons. They are amplified by 10 to the six.  Don't jack up the voltage on the multiplier, but to clean the source, or re-tune it.  Monitor the EMV.

2) quadrupole mass analyzer. We won't get ion currents if they are under the Scan Line.  We need to do tuning to raise the Scan Line in order to improve resolution and separation. Do not let the ions hit the quadrupole.

3a) Electrospray. 
Electrospray makes droplets, ions are in the droplets. We put high voltage on it. It undergoes the ion evaporation model.

the liquids coming through at 200 microliters per minute. If the electrosprayer was blocked, you would have unstable ion current noise that ion current will be noisy.  We need to have asymmetrical spray. 

The spray first takes place, the ion evaporation takes place to produce gas-phase ions.  

A combination of heat, nebulizing gas, and time can get the large droplet to sub micro droplet.

Only one in 10,000 ions get inside the mass spectrometer.  

Check the the voltage potential between the sprayer and the interface plate (orifice??), if the voltage is decreased.  The voltage potential makes ions go where we want them to go.  The ions could go other places with the reduced voltage potential so that the sensitivity suffers.

What does it take to increase evaporation? optimum temperature and flow rate.

If the spray is structured as a pneumatic systems, 

It is a concentration sensitive detector,
, matrix effects. optimize flow rate, lower the voltage, pH in mobile phase to improve ionization.
clean the source.  


3b) APCI

4) SIM or MRM can improve sensitivity comparing to full scan.  SIM is preferred over full-scan.  

) capillary. temperature, voltage


From the perspective of sample introducting to MS:
1) less carry-over
2) less sample volume [50ng is plenty for MS]
3) solution:pH, low boiling point, low dielectric constant, low surface tension.


How to increase the sensitivity at low mass-to-charge end?
There are chemical noise there, use APCI instead of ESI; or negative ionization mode.

compartment temperature does not help resolution, but repeatability.  temperature vs. solvent viscosity.

baseline resolution.

How do obtain sensitivity?
1) select an ionization method between ESI and APCI (according to the residue of compounds).  
2) select positive ion mode or negative ion mode.



How to increase resolution of MS?
Quadrupole (Q1). , needs tuning (autotune or manual tune) to keep the instrument in the best condition.



## From LC hardware perspective
Samples are diluted in proportion to the cross-sectional area of the column and therefore, smaller ID columns yield less dilution.  
Reduction of particle size causes an increase in the sensitivity because of more narrow and higher peaks.  
In order to have a high-efficiency separation, it is important to minimize the instrument’s dead volume. This can be achieved by optimizing the entire HPLC system using smaller I.D. and/or shorter connection capillaries, smaller injection unit, and smaller detector cell.

## From mobile phase perspective
formic acid concentration decreased, will lower the sensitivity, because formic acid promotes 

systematic approach to expectation:
1) Proactive approach: monitor the mass (exact mass for HRMS) daily, and plot it.
2) monitor back pressure., and plot it.
3) build troubleshooting database (knowledge transfer).

## From sample preparation perspective
A loss in sensitivity can indicate problems with either the sample preparation or the analytical system.  First, confirm that the sample preparation procedure was followed correctly, including storage temperature and time, and verify that system parameters are set correctly and functioning properly. Always check for obvious problems (e.g., calculation/dilution error, autosampler needle not reaching sample, incorrect injection volume, wrong detector settings, no mobile phase flow, detector or lamp turned off, integrity of the reference standard, etc.) before looking for more complex issues. Having a coworker double check your work can be invaluable because it is often easier for an independent person to spot problems than it is for someone who is already familiar with the work.




## Summary of sensitivity reduction
1. Simple potential causes:  
  1.1) sample preparation,   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;abnormal storage temperature,   
  &nbsp;&nbsp;storage time,  
  &nbsp;&nbsp;abnormal extraction,  
  &nbsp;&nbsp;abnormal clean-up,  
  &nbsp;&nbsp;Was matrix be cleaned-up in sample preparation?
  1.2) LC system,  
  &nbsp;&nbsp;Dilution error,  
  &nbsp;&nbsp;autosampler needle not reaching sample,  
  &nbsp;&nbsp;incorrect injection volume,  
  &nbsp;&nbsp;abnormal LC back pressure,  
  &nbsp;&nbsp;Leak,  
  &nbsp;&nbsp;mobile phase unstable (modifier, prepared date, )  
  1.3) Mass spectrometer system,  
  &nbsp;&nbsp;non-asymmetric spray (due to clog)  
  &nbsp;&nbsp;Electron multiplier voltage error,   
  &nbsp;&nbsp;the declustering potential error,  
  &nbsp;&nbsp;the collision energy error  
  &nbsp;&nbsp;the collision exit cell potential error  
  &nbsp;&nbsp;GS1 pressure - nebulizer gas error  
  &nbsp;&nbsp;GS2 pressure - turbo gas error  
  &nbsp;&nbsp;Curtain gas pressure error  
  &nbsp;&nbsp;Ion spray voltage error  
  &nbsp;&nbsp;test  
  1.4) System monitoring,  
  &nbsp;&nbsp; monitoring charts of internal standards, blank, calibrators,   
  1.5) Data processing,  
  &nbsp;&nbsp;Calculation error (dilution factor),  
  &nbsp;&nbsp;Peak integration error (baseline issue, noise),  
  &nbsp;&nbsp;Retention time shift,  
  &nbsp;&nbsp;
  &nbsp;&nbsp;
  &nbsp;&nbsp;
  
2. Complex potential causes:  
  &nbsp;&nbsp;Analyze new known standard  
  &nbsp;&nbsp;Analyze blank  
  &nbsp;&nbsp;Infuse standard in 50-50 mobile phase solution to the mass spectrometer  
  &nbsp;&nbsp;Dry run  
  &nbsp;&nbsp;
  &nbsp;&nbsp;
  &nbsp;&nbsp;
