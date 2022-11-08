---
weight: 1
title: Maximize Sensitivity in LC-MS/MS
authors: Lenny Lin
categories: 
tags: [Sensitivity]
description: null
draft: true
date: "2022-10-31"
lastmod: "2022-10-31"
series: 
toc: false
---

<!--more-->
---

Here I summarize solutions on how to address the sensitivity concern in LC-MS.  The solutions are segregated into two sections, "during the routine analysis", and "during the method development".


## During the routine analysis

<table style="width:100%; font-size: 60%">
<caption style="text-align:left", align = "top"><b></b></caption>
<colgroup><col style="width: 55%" /><col style="width: 45%" />
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

  
  <tr class="even">
    <td><p><b><font style = "font-size: 90%" class = "font_upper">MS</font></b>:
    <br>The interface region of the mass spectrometer becomes contaminated
    </p></td>
    <td><p><a href = "https://www.aacc.org/cln/articles/2015/august/troubleshooting-liquid-chromatography-tandem-mass-spectrometry-in-the-clinical-laboratory" target="_blank" rel="noopener noreferrer">AACC: Troubleshooting Liquid Chromatography-Tandem Mass Spectrometry in the Clinical Laboratory</a>
    </p></td>
  </tr>

  
</tbody>
</table>

<tr><td><div class="pagebreak">&nbsp;</div></td></tr>

## During the method development

<table style="width:100%; font-size: 60%">
<caption style="text-align:left", align = "top"><b></b></caption>
<colgroup><col style="width: 55%" /><col style="width: 45%" />
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

</tbody>
</table>
