---
authors: edited by Lenny Lin
categories:
date: "2022-07-07"
description: null
draft: false
lastmod: "2022-07-08"
series:
tags: []
title: Acceptable Limits for Accuracy using LCMSMS?
toc: true
---

**solution**:  
) Separate analyte from the matrix.  

**Lessons Learnt**:  
) Highering `dissolvation temperature` and gas flow will help to get a better dissolvation  
) Decreasing `flow rate` (especially on TQD) around 0.4 ml/min will help to get better RSD's (also linked to dissolvation)  
) Lowing `capillary voltage` may give higher sensitivity but may increase Rsd (consider a test at 3kv and then compare with 1.5 and 1 kv, never go to 0.5kv).


<!--more-->

**Situation**:    
I'm wondering what folks here consider to be acceptable limits for accuracy using LCMSMS.

I work in a clinical lab. Historically the limit has been 10%. Most procedures nowadays are performed on automated instruments using few manual steps if any at all. My lab director wants 10% for the LCMSMS as well. I have found this is not so easy. From an article I read from Validation Viewpoint the FDA recommends 15% for four of six points and 20% at the lower limit of quantitation. That seems rather wide for me but I don't see why there can't be some compromise between 10 and 15%.

As an example I am working up a Levetiracetam method on a UPLC/TQD. I get an obs error of 6.3% with concentrations 0 to 50 ug/mL. But pushing the upper limit to 75 ug/mL gets me an error up to 11%. He will not accept this. Problem is therapuetic range for this drug is up to 80 ug/mL which means we'll be diluting quite a few samples.

**Solution**:  
Response #1:  
While MRM experiments usually provide sufficient specificity, I have often found that simply separating your analyte of interest from the matrix will vastly improve your RSDs and often increase the sensitivity of the method.  

Response #2:  
It will not be always easy to reach these 10% all the way in LC-MS/MS. FDA regulation is accepted almost everywhere... A more robust source will help to achieve these limits for a specified assay: to help to stay away from the LOQ for this assay. What MS instrument do you have?  

However, here is a possible list from one of our application chemists of things to check for the system as a rough guide.

1) Detuning the Probe adjuster (spraying a little bit more far away from the Cone)

2) Highering dissolvation temperature and gas flow will help to get a better dissolvation

3) Eventually decreasing flow rate (especially on TQD) around 0.4 ml/min will help to get better RSD's (also linked to dissolvation)

4) Too low capillary voltage may give higher sensitivity but may increase RSD (consider a test at 3kv and then compare with 1.5 and 1 kv, never go to 0.5kv).

5) Internal standard with deuterated compounds should be used.

6) Matrix effect is also something to consider, a very specific and selective sample prep will help to reduce RSDs.

7) In addition to this, Full loop injection will help from the UPLC end.

**Reference**:  
[Waters: Accuracy for LC-MS/MS](https://forums.waters.com/discussion/1564/acceptable-accuracy-for-lc-ms-ms)