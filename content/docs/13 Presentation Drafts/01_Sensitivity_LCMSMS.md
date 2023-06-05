---
weight: 1
title: Maximize Sensitivity in LC-MS/MS
authors: Lenny Lin
categories: 
tags: [Sensitivity]
description: null
draft: false
date: "2022-10-19"
lastmod: "2022-10-31"
series: 
toc: true
---

<!--more-->
---

## Sensitivity of MS

Sensitivity definition: signal-to-noise 


## From HPLC system hardware perspective, what could affect the sensitivity?

contamination

HPLC system settings (dead volume)


## From the perspective of sample introducting to mass spectrometer
1) less carry-over
2) less sample volume [50ng is plenty for MS]
3) solution: pH, low boiling point, low dielectric constant, low surface tension.


## From mass spectrometer hardware perspective, what could affect the sensitivity?

Asymmetric spray

matrix effect  

We won't get ion currents if they are under the Scan Line.  We need to do tuning to raise the Scan Line in order to improve resolution and separation. Do not let the ions hit the quadrupole.  

compartment temperature does not help resolution, but repeatability.  temperature vs. solvent viscosity.

baseline resolution.

### Ion source options  
1) select an ionization method between ESI and APCI (according to the residue of compounds).  
2) select positive ion mode or negative ion mode.  

There are chemical noise there, use APCI instead of ESI; or negative ionization mode.

#### Electrospray  
&emsp;Electrospray makes droplets, ions are in the droplets. We put high voltage on it. It undergoes the ion evaporation model.

&emsp;The liquids coming through at 200 microliters per minute. If the electrosprayer was blocked, you would have unstable ion current noise that ion current will be noisy.  We need to have asymmetrical spray. 

&emsp;The spray first takes place, the ion evaporation takes place to produce gas-phase ions.  

&emsp;A combination of heat, nebulizing gas, and time can get the large droplet to sub micro droplet.

&emsp;Only one in 10,000 ions get inside the mass spectrometer.  

&emsp;Check the the voltage potential between the sprayer and the interface plate (orifice??), if the voltage is decreased.  The voltage potential makes ions go where we want them to go.  The ions could go other places with the reduced voltage potential so that the sensitivity suffers.

&emsp;What does it take to increase evaporation? optimum temperature and flow rate.

&emsp;If the spray is structured as a pneumatic systems, 

&emsp;It is a concentration sensitive detector,
, matrix effects. optimize flow rate, lower the voltage, pH in mobile phase to improve ionization.
clean the source.  


#### APCI


#### Electron (not electronic) multiplier
The very weak ion current exits the quadrupole, ions hit the electron multiplier surface, and produce electrons. They are amplified by 10 to the six.  Don't jack up the voltage on the multiplier, but to clean the source, or re-tune it.  Monitor the EMV.


#### Scan modes
SIM or MRM can improve sensitivity comparing to full scan.  SIM is preferred over full-scan.  


#### Misc
) capillary. temperature, voltage



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


## During the routine analysis  

What if the sensitivity dropped? 

The troubleshooting strategy. What cause the dropped sensitivity?  

What tools could we use?

<table style="width:100%; font-size: 60%">
<caption style="text-align:left", align = "top"><b>Increase sensitivity for LC-MS/MS During the Routine Analysis</b></caption>
<colgroup><col style="width: 40%" /><col style="width: 60%" />
</colgroup>
<thead>
  <tr VALIGN=TOP style="text-align:left"  class="header">
    <th><p>Suggestions</p></th>
    <th><p>References</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
 <tr class="odd">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">general</font></b>
    <br>Identify whether the loss of sensitivity is due to poor recovery or to matrix suppression
    </p></td>
    <td><p><a href = "https://cdn.sanity.io/files/0vv8moc6/biopharn/1a7e564988c4ca05949add7061339d9dadbe47ec.pdf/article-7275.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 2: Large-Scale LC/MS/MS and Automation</a>
    </p></td>
  </tr>

  
  <tr class="even">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">sample preparation</font></b>:
    <br>Elute analytes to waste instead of autosampler vials or collection plate
    </p></td>
    <td><p><a href = "https://https://www.aacc.org/cln/articles/2015/august/troubleshooting-liquid-chromatography-tandem-mass-spectrometry-in-the-clinical-laboratory">AACC: Troubleshooting Liquid Chromatography-Tandem Mass Spectrometry in the Clinical Laboratory</a>
    </p></td>
  </tr>


  <tr class="odd">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">Lab equipment</font></b>:
    <br>Flush the equipment and vessels with MS grade solvents if necessary.
    </p></td>
    <td><p><a href = "https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/tips-and-tricks-sensitivity-gains-in-lcms" target="_blank" rel="noopener noreferrer">Millipore Sigma: Analytix Reporter - Issue 2: How to Maximize Sensitivity in LC-MS</a>
    </p></td>
  </tr>

  
  <tr class="even">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">hplc system</font></b>:
    <br>1) Minimize dead volume.
    <br>Large dead volumes can cause peak broadening, tailing, or splitting and lead to poor resolution and decreased performance, and hence can decrease sensitivity and prevent detection of low abundant analytes. 
    <br>2) Replace the pump inlet filter every 1 to 2 months or after changing from acetonitrile to methanol (or vice versa) as a solvent.
    <br>3) Use stainless steel or PEEK eluent filter frits rather than glass.
    </p></td>
    <td><p>1-3) <a href = "https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/tips-and-tricks-sensitivity-gains-in-lcms" target="_blank" rel="noopener noreferrer">Millipore Sigma: Analytix Reporter - Issue 2: How to Maximize Sensitivity in LC-MS</a>
    </p></td>
  </tr>

  
  <tr class="odd">
    <td><p>
    </p></td>
    <td><p>sentence right.
    </p></td>
  </tr>

  
  <tr class="even">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">MS</font></b>:
    <br>The interface region of the mass spectrometer becomes contaminated
    </p></td>
    <td><p><a href = "https://www.aacc.org/cln/articles/2015/august/troubleshooting-liquid-chromatography-tandem-mass-spectrometry-in-the-clinical-laboratory" target="_blank" rel="noopener noreferrer">AACC: Troubleshooting Liquid Chromatography-Tandem Mass Spectrometry in the Clinical Laboratory</a>
    </p></td>
  </tr>

  
  <tr class="odd">
    <td><p>sentence left
    </p></td>
    <td><p>sentence right.
    </p></td>
  </tr>
  
  <tr class="even">
    <td><p>sentence left
    </p></td>
    <td><p> sentence right.
    </p></td>
  </tr>
  
</tbody>
</table>


## During the method development   

<table style="width:100%; font-size: 60%">
<caption style="text-align:left", align = "top"><b>Increase sensitivity for LC-MS/MS During the Method Development</b></caption>
<colgroup><col style="width: 50%" /><col style="width: 50%" />
</colgroup>
<thead>
  <tr VALIGN=TOP style="text-align:left"  class="header">
    <th><p>Suggestions</p></th>
    <th><p>References</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>

  <tr class="odd">
    <td><p><b><font style = "font-size: 90%"  class = "font_upper">Sample Pretreatment</font></b>: 
    <br><b><font style = "font-size: 90%" class = "font_upper">Goal</font></b>: Remove matrix compounds
    <br>1) Simple filtration and dilution
    <br>2) Endogenous matrix compounds in the sample (proteins, lipids, pigments, ...)
    <br>3) Exogenous matrix compounds leached from plastic centrifuge tubes, well plates, and pipette tips, ...
    <br>4) poor recovery or matrix suppression can result in the loss of sensitivity
    <br>5) Better SPE
    <br>6) Choosing a reconstitution solvent compatible with the mobile phase
    </p></td>
    <td><p>1-3) <a href = "https://www.chromatographyonline.com/view/lc-ms-sensitivity-practical-strategies-boost-your-signal-and-lower-your-noise" target="_blank" rel="noopener noreferrer">LC-GC: LC–MS Sensitivity: Practical Strategies to Boost Your Signal and Lower Your Noise</a>
    <br>4) <a href = "https://cdn.sanity.io/files/0vv8moc6/biopharn/1a7e564988c4ca05949add7061339d9dadbe47ec.pdf/article-7275.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 2: Large-Scale LC/MS/MS and Automation</a>
    <br>5) <a href = "https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/solid-phase-extraction/the-extraction-of" target="_blank" rel="noopener noreferrer">Sigma Aldrich: The Extraction of Amphetamine and Related Drugs using Molecularly Imprinted Polymer SPE. </a>
    <br>6) <a href = "http://alfresco-static-files.s3.amazonaws.com/alfresco_images/pharma/2014/08/26/ede58aca-c91e-462c-a41b-42355e3be017/article-2140.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 1: Sample Preparation and Chromatography</a>
    </p></td>
  </tr>


  <tr class="even">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">Solvents and Additives</font></b>:
    <br>1) The quality of solvents (include water, acetonitrile, methanol, isopropanol, and n-propanol) and additives (such as acids (e.g., formic acid), bases (e.g., ammonia) or buffers (e.g., ammonium acetate))
    <br>Additives are used to enable the protonation or deprotonation of the analytes.  
    <br>Buffers are utilized to set and control the pH of mobile phase A to stabilize analyte, protonate or deprotonate analytes.
    <br>Buffers ionize an analyte molecule M, but the formation of adducts [M+buffer] with, e.g., ammonium, formate or acetate is possible.  
    <br>2) The use of ion pair reagents (e.g., heptafluorobutyric acid and tetrabutyl ammonium)
    <br>3) Avoid strong acids, such as hydrochloric acid, sulfuric acid, or nitric acid
    </p></td>
    <td><p>
    <br>1) *<a href = "https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/tips-and-tricks-sensitivity-gains-in-lcms" target="_blank" rel="noopener noreferrer">Millipore Sigma: Analytix Reporter - Issue 2: How to Maximize Sensitivity in LC-MS</a>
    <br>*<a href = "https://www.sigmaaldrich.com/CA/en/collections/analytix-reporter#archives" target="_blank" rel="noopener noreferrer">HPLC Tips & Tricks, Analytix Reporter, issue 11 | 2022, page 34.</a>
    <br>*<a href = "https://www.chromatographyonline.com/view/lc-ms-sensitivity-practical-strategies-boost-your-signal-and-lower-your-noise" target="_blank" rel="noopener noreferrer">LC-GC: LC–MS Sensitivity: Practical Strategies to Boost Your Signal and Lower Your Noise</a>
    <br>2) p79, Analysis of Pesticides in Food and Environmental Samples, CRC Press, 2008, edited by José L. Tadeo
    <br>3) <a href = "https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/tips-and-tricks-sensitivity-gains-in-lcms" target="_blank" rel="noopener noreferrer">Millipore Sigma: Analytix Reporter - Issue 2: How to Maximize Sensitivity in LC-MS</a>
    </p></td>
  </tr>


  <tr class="odd">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">solvents and additives storage</font></b>: 
    <br>1) Adjustment of the bottle size to specific needs.
    <br>2) Use surface treated amber or borosilicate glass bottles. Avoid standard clear or soda-lime glass bottles.
    <br>3) Seal bottles with professional caps.  Connect ot the HPLC system with professional adapters and tubings.
    <br>4) Avoid plastic devices such as bottles, funnels, beakers, or gloves, except pipette tips or syringes.
    </p></td>
    <td><p><a href = "https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/tips-and-tricks-sensitivity-gains-in-lcms" target="_blank" rel="noopener noreferrer">Millipore Sigma: Analytix Reporter - Issue 2: How to Maximize Sensitivity in LC-MS</a>
    </p></td>
  </tr>


  <tr class="even">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">mobile phase compositions</font></b>:
    <br>The water content in an eluent used in LC-MS should be set to 5 to 80% in order to work trouble-free and with a stable spray.
    </p></td>
    <td><p><a href = "https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/tips-and-tricks-sensitivity-gains-in-lcms" target="_blank" rel="noopener noreferrer">Millipore Sigma: Analytix Reporter - Issue 2: How to Maximize Sensitivity in LC-MS</a>
    </p></td>
  </tr>
  
  
  <tr class="odd">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">LC Column</font></b>:
    <br>1) Column with smaller dimention
    <br>2) A suitable LC column (a silica column was used in the reference)
    <br>Many of the silica-based bonded phases are inherently prone towards bond/phase cleavage by hydrolysis, mainly at acidic pH (e.g., below pH 2), a phenomenon referred to as column bleeding.
    <br>The use of a washing protocol can help to decrease the negative effect of column bleed. Alternatively, a column should undergo up to ten gradient runs from strongly aqueous to strongly organic before use with MS.
    </p></td>
    <td><p>1) *<a href = "https://www.chromatographyonline.com/view/lc-ms-sensitivity-practical-strategies-boost-your-signal-and-lower-your-noise" target="_blank" rel="noopener noreferrer">LC-GC: LC–MS Sensitivity: Practical Strategies to Boost Your Signal and Lower Your Noise</a>
    <br>*<a href = "http://alfresco-static-files.s3.amazonaws.com/alfresco_images/pharma/2014/08/26/ede58aca-c91e-462c-a41b-42355e3be017/article-2140.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 1: Sample Preparation and Chromatography</a>
    <br>*<a href = "https://www.sigmaaldrich.com/CA/en/technical-documents/technical-article/analytical-chemistry/small-molecule-hplc/tips-and-tricks-sensitivity-gains-in-lcms" target="_blank" rel="noopener noreferrer">Millipore Sigma: Analytix Reporter - Issue 2: How to Maximize Sensitivity in LC-MS</a>
    <br>2) <a href = "http://alfresco-static-files.s3.amazonaws.com/alfresco_images/pharma/2014/08/26/ede58aca-c91e-462c-a41b-42355e3be017/article-2140.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 1: Sample Preparation and Chromatography</a>
    </p></td>
  </tr>


  <tr class="even">
    <td><p>MS Optimization:
    <br>1) Choose the appropriate polarity
    <br>2) Capillary voltage (The applied potential difference between the capillary tip and sampling plate)
    <br>3) Nebulizing gas flow and temperature
    <br>4) Temperature
    <br>5) Drying gas flow and temperature
    <br>6) The distance between the capillary tip and the sampling orifice 
    <br>7) An additional heated sheath gas coupling with ESI can reach a higher sensitivity, such design can be found at the Jet Stream ESI, but it can suffer at the same time from significantly stronger signal suppressions
    <br>8) A longer dwell time would result in better sensitivity with the reduced number of data points acquired across a single peak
    <br>
    </p></td>
    <td><p>1-6) <a href = "https://www.chromatographyonline.com/view/lc-ms-sensitivity-practical-strategies-boost-your-signal-and-lower-your-noise" target="_blank" rel="noopener noreferrer">LC-GC: LC–MS Sensitivity: Practical Strategies to Boost Your Signal and Lower Your Noise</a>
    <br>7) Stahnke, H., Kittlaus, S., Kempe, G., Hemmerling, C., & Alder, L. (2012). The influence of electrospray ion source design on matrix effects. Journal of Mass Spectrometry, 47(7), 875–884. doi:10.1002/jms.3047
    <br>8) <a href = "https://www.chromatographyonline.com/view/lc-ms-sensitivity-practical-strategies-boost-your-signal-and-lower-your-noise" target="_blank" rel="noopener noreferrer">LC-GC: LC–MS Sensitivity: Practical Strategies to Boost Your Signal and Lower Your Noise</a>
    <br>8) p68, p70, Analysis of Pesticides in Food and Environmental Samples, CRC Press, 2008, edited by José L. Tadeo
    </p></td>
  </tr>

  <tr class="odd">
    <td><p>sentence left
    </p></td>
    <td><p> sentence right.
    </p></td>
  </tr>
  <tr class="even">
    <td><p>sentence left
    </p></td>
    <td><p>sentence right.
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>sentence left
    </p></td>
    <td><p> sentence right.
    </p></td>
  </tr>

  <tr class="even">
    <td><p>sentence left
    </p></td>
    <td><p>sentence right.
    </p></td>
  </tr>

  <tr class="odd">
    <td><p>sentence left
    </p></td>
    <td><p> sentence right.
    </p></td>
  </tr>

  <tr class="even">
    <td><p>sentence left
    </p></td>
    <td><p>sentence right.
    </p></td>
  </tr>

  <tr class="odd">
    <td><p>sentence left
    </p></td>
    <td><p> sentence right.
    </p></td>
  </tr>
</tbody>
</table>


## How to increase resolution of MS?
Quadrupole (Q1). , needs tuning (autotune or manual tune) to keep the instrument in the best condition.
