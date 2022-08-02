---
authors: edited by Lenny Lin
categories:
date: "2022-07-07"
description: null
draft: false
lastmod: "2022-07-07"
series:
tags: []
title: Internal standard Variation
toc: true
---



<!--more-->

**Situation**:  
I got consistent response of internal standard in Method Validation.But during study sample analysis, I got variation more than 40% of mean response of calibration curve standards. And I was observed that in some samples ISTD response exactly double than that of preceeding and succeeding samples, even after taking care during sample processing.  

Response of ISTD in CC's and QC's almost same, but in subject samples response was differed.  


1.what might be the reason for internal standard variation?  
2.why sudden response change will come?  
3.Is there any regulatory guideline suggesting the acceptance criteria for internal standard variation?  

**Solution**:  
Is the response systematically significantly higher in your unknown samples compared to the standards and QCs ? If you are using a LC/MS/MS method, it could be a matrix effect issue. Could also be a different behaviour during sample preparation, leading to a different recovery. A few questions and ideas:  

- what method are you using for sample preparation?
- are you using the same anticoagulant in your standards/QCs and in your unknown samples ?
- how did you investigate matrix effect during method development and validation ? Did you try any post-column infusion as part of development ?
- how variable is your IS response in your unknown samples ? I understand the response is higher, but is the CV of the IS response similar in unknown samples and in standards/QCs ?
- if you have more variability in your unknown samples, does it follow any specific pattern, for instance depending on the sampling time (looking like a PK curve) ? If this is the case you may have some interference from a metabolite. Enhancement is not frequent with electrospray ionisation (suppression is much more frequent), but it does happen with APCI.
- Oh, and what kind of IS are you using ? Stable isotope labelled, or structural analogue (what structure compared to your metabolites), or totally different structure ?  

**Reference**:  
[BEBAC forum: Internal Standard Variation](https://forum.bebac.at/mix_entry.php?id=1768&page=0&category=0&order=time&descasc=DESC#p1770)