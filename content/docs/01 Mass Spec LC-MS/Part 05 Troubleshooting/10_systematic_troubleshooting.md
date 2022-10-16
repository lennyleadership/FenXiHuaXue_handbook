---
weight: 10
title: Systematic Troubleshooting 
authors: Naidong Weng and Timothy D.J. Halls, edited by Lenny Lin
categories: null
tags: [Matrix Effects Determination]
description:  
draft: false
date: "2022-10-15"
lastmod: "2022-10-15"
series: null
toc: true
---

Tips: Frequently, resolving the problem requires a combination of individual experimental solutions and systematic and logical investigation.  

Part 2 discusses further troubleshooting techniques and presents an automation strategy that improves method robustness and performance.

<!--more-->

---

## Part 1

**Reference**:  
1. <a href = "http://alfresco-static-files.s3.amazonaws.com/alfresco_images/pharma/2014/08/26/ede58aca-c91e-462c-a41b-42355e3be017/article-2140.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 1: Sample Preparation and Chromatography</a>

---

## Part 2
### Carry-over
Carry-over is probably one of the most commonly encountered problems of LC/MS/MS method development. Sources of problems range from instrument hardware and the selection of appropriate rinse solvents to challenges with chromatography. Frequently, resolving the problem requires a combination of individual experimental solutions and systematic and logical investigation.   

<u>**The gradient elution** was actually determined to be the cause of the carry-over effect</u>. To address the issue, <u>an isocratic elution with a mobile phase that contained 45% acetonitrile was used to eliminate the carryover</u>. A new problem surfaced when the original internal standard was not retained on the column in the mobile phase, so a new one had to be used. The new standard had retention properties similar to those of the analyte. Figure 2 depicts the resolution of the carry-over problem. The method was validated and successfully used for sample analysis.  chromatographic condition and internal standard were changed as a result of the problem and its solution. Occasionally, carry-over problems have simpler solutions. In another example, simply raising the needle height solved the carry-over effect. <u>Carry-over is often avoided by merely minimizing the contact surface between a

Occasionally, carry-over problems have simpler solutions. In another example, simply raising the needle height solved the carry-over effect. Carry-over is often avoided by merely minimizing the contact surface between analyte and needle.  


### Recovery and matrix effects

For an LC/MS/MS method, it is important to identify whether the loss of sensitivity is due to poor recovery or to matrix suppression, because both causes give the same result. Carefully designed experiments will establish the source of the problem.  

Recovery is determined by comparing the peak areas of extracted samples with those of neat solutions spiked (postextraction) into a blank matrix. Because both samples have the matrix ingredients present, the matrix effects can be considered the same for extracted samples and postextraction spiked samples. Any differences in response can now be considered to be due to extraction recovery.   

The matrix effect[^1] is determined by comparing peak areas of neat solutions spiked (postextraction) into blank matrix with those of other neat solutions. Because the analytes are not extracted, the analyte should have the same response in postextraction spiked samples and in neat solutions. The matrix ingredients, therefore, cause whatever differences are noted in the responses. A useful method to assess matrix suppression is postcolumn infusion of an analyte into the MS detector. The extracted blank matrix is injected by an autosampler onto the analytical column. The setup is shown in Figure 3. The purpose of postcolumn infusion with analyte is to raise the background level so that the suppression matrix will show as negative peaks. This setup has been successfully used to identify and troubleshoot matrix suppression peaks.  

[^1]: According to the determination process, it seems there is no matrix effect on GC-MS/MS.  


**Reference**:  
2. <a href = "https://cdn.sanity.io/files/0vv8moc6/biopharn/1a7e564988c4ca05949add7061339d9dadbe47ec.pdf/article-7275.pdf" target="_blank" rel="noopener noreferrer">Systematic Troubleshooting for LC/MS/MS - Part 2: Large-Scale LC/MS/MS and Automation</a>