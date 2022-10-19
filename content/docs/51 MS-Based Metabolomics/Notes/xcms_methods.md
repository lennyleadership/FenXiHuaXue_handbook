---
authors: edited by Lenny Lin
categories: 
date: null
description: 
draft: false
lastmod: "2022-05-17"
series: 
tags: []
title: xcms Methods and Parameters
toc: true
---

<figcaption><b>Figure </b>: </figcaption>
<img src = "/docs/images/"/>
<!--more-->

The first 'xcmsSet'-method 'centWave' deals with peak picking. This is the method of choice for processing centroided data acquired with liquid chromatography (LC) coupled to high resolution mass spectrometry (HRMS).   

First, 'centWave' identifies regions of interest (ROIs). ROIs are created by combining consecutive centroids within a tolerated m/z deviation, defined by the parameter 'ppm'.   

Chromatographic peaks are identified within the ROIs using wavelets. The peak width parameters ('min peakwidth' and 'max peakwidth') describe the range of the expected peak widths and determine the scales of the wavelets.   

The minimum difference of m/z for peaks with overlapping retention times is given by 'mzdiff'.   

The second 'xcmsSet'-method 'matchedFilter' also deals with peak picking, but it has particularly been developed for low resolution data.   

The 'obiwarp' method is responsible for the retention time correction. The 'center' parameter indicates the sample which serves as reference sample for retention time correction. If not otherwise specified by the user, XCMS uses the sample with the highest number of peaks as 'center' sample whereas IPO chooses the one with the highest average intensity. First, profiles are generated from the raw data. The parameter 'prof- Step' defines the widths of these profiles in the m/z dimension. Then, the profiles are compared to each other and a similarity matrix is calculated. Similarity scores are added to recursively generate an optimal path. Offdiagonal transitions are penalized. The parameters 'gapInit' and 'gapExtend' define penalties for gap openings and gap enlargements, respectively.   

The method ‘density’ is a method for the grouping step. Grouping is the process of combining peaks from different samples with similar masses and retention times to peak groups. The parameter ‘bw’ is used to define a certain retention time range to find peak groups. ‘mzwid’ describes the allowed variation in the m/z dimension. <mark>The default value for ‘mzwid’ is 0.25 which is too high for high resolution data and this value was therefore set to 0.025</mark>. A valid feature must have a minimum fraction of samples within at least one sample group. This fraction is defined by the parameter ‘minfrac’. 
