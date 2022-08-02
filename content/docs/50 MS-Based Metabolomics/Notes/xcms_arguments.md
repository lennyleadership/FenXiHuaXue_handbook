---
authors: Lenny Lin
categories: 
date: null
description: 
draft: false
lastmod: "2022-05-17"
series: 
tags: [R package,xcms]
title: Arguments available in xcmsSet() 
toc: true
---
I list a number of arguments available in xcmsSet().
<!--more-->


<table style="width:100%;">
<caption style="text-align:left", align = "top"><b>Arguments for Feature Detection</b></caption>
<colgroup><col style="width: 30%" /><col style="width: 70%" />
</colgroup>
<thead>
  <tr VALIGN=TOP style="text-align:left" class="header">
    <th><p>Arguments</p></th>
    <th><p>Definition</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
  <tr class="odd">
    <td><p>method
    </p></td>
    <td><p><b>centWave</b>: 	Highly sensitive feature detection using a peak density and wavelet based method. Applicable for high resolution LC/MS data in centroid mode.  
    <br />  
    <b>matchedFilter</b>: 	Find peaks in the chromatographic time domain of the profile matrix using "matched filter" method.  
    <br />   
    default value: centWave
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>ppm  
    <br />  
    [ppm]
    </p></td>
    <td><p>maximal tolerated m/z deviation in consecutive scans, in ppm (parts per million)  
    <br />   
    default value: 10
    </p></td>
  </tr>
  <tr class="even">
    <td><p>minimum peak width  
    <br />  
    [peakwidth = c(##, )]
    </p></td>
    <td><p> minimum chromatographic peak width in seconds.  
    <br />  
    note: must be less than max peak width.  
    <br />   
    default value: 5
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>maximum peak width  
    <br />  
    [peakwidth = c(,##)]
    </p></td>
    <td><p>maximum chromatographic peak width in seconds  
    <br /> 
    note: must be greater than min peak width.  
    <br />   
    default value: 20
    </p></td>
  </tr>
  <tr class="even">
    <td><p> Signal/Noise threshold  
    <br />   
    [snthresh]
    </p></td>
    <td><p> Signal/Noise threshold  
    <br />   
    default value: 6
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>mzdiff  
    <br />   
    [mzdiff]
    </p></td>
    <td><p>minimum difference in m/z for peaks with overlapping retention times, can be negative to allow overlap  
    <br />   
    default value: 0.01
    </p></td>
  </tr>
  <tr class="even">
    <td><p>Integration method  
    <br />   
    [integrate]
    </p></td>
    <td><p> Integration method.   
    <br />  
    If =1 peak limits are found through descent on the mexican hat filtered data,   
    <br />   
    if =2 the descent is done on the real data.   
    <br />    
    Method 2 is very accurate but prone to noise, while method 1 is more robust to noise but less exact.  
    <br />   
    default value: 1
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>prefilter peaks  
    <br />   
    [prefilter = c(##, )]
    </p></td>
    <td><p> Prefilter step for the first phase. Mass traces are only retained if they contain at least [prefilter peaks] peaks with intensity >= [prefilter intensity]  
    <br />   
    default value: 3
    </p></td>
  </tr>
  <tr class="even">
    <td><p> prefilter intensity  
    <br />  
    [prefilter = c(,##)]
    </p></td>
    <td><p> Prefilter step for the first phase. Mass traces are only retained if they contain at least [prefilter peaks] peaks with intensity >= [prefilter intensity]  
    <br />   
    default value: 100
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>Noise Filter  
    <br />   
    [noise]
    </p></td>
    <td><p>Optional argument which is useful for data that was centroided without any intensity threshold, centroids with intensity < noise are omitted from ROI detection  
    <br />   
    default value: 100
    </p></td>
  </tr>
</tbody>
</table>


<table style="width:100%;">
<caption style="text-align:left", align = "top"><b>Arguments for Retention Time Correction</b></caption>
<colgroup><col style="width: 30%" /><col style="width: 70%" />
</colgroup>
<thead>
  <tr VALIGN=TOP style="text-align:left" class="header">
    <th><p>Arguments</p></th>
    <th><p>Definition</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
  <tr class="odd">
    <td><p>Method
    </p></td>
    <td><p><b>obiwarp</b>: Retention time correction method based on correlations of the raw data.  
    <br />   
    <b>peakgroups</b>: use "well behaved" peak groups and nonlinear regression to calculate retention time deviations for every time point of each sample.  
    </p></td>
  </tr>
  <tr class="even">
    <td><p>profStep
    </p></td>
    <td><p> step size (in m/z) to use for profile generation from the raw data files.  
    <br />   
    default value: 1
    </p></td>
  </tr>
</tbody>
</table>


<table style="width:100%;">
<caption style="text-align:left", align = "top"><b>Arguments for Aligment</b></caption>
<colgroup><col style="width: 30%" /><col style="width: 70%" />
</colgroup>
<thead>
  <tr VALIGN=TOP style="text-align:left" class="header">
    <th><p>Arguments</p></th>
    <th><p>Definition</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
  <tr class="odd">
    <td><p>bw
    </p></td>
    <td><p>Allowable retention time deviations, in seconds. In more detail: bandwidth (standard deviation or half width at half maximum) of gaussian smoothing kernel to apply to the peak density chromatogram.  
    <br />   
    default value: 5
    </p></td>
  </tr>
  <tr class="even">
    <td><p>minfrac
    </p></td>
    <td><p>minimum fraction of samples necessary in at least one of the sample groups for it to be a valid group.  
    <br />   
    default value: 0.5
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>mzwid
    </p></td>
    <td><p>	width of overlapping m/z slices to use for creating peak density chromatograms and grouping peaks across samples.  
    <br />   
    default value: 0.15
    </p></td>
  </tr>
  <tr class="even">
    <td><p>minsamp
    </p></td>
    <td><p> 	minimum number of samples necessary in at least one of the sample groups for it to be a valid group  
    <br />   
    default value: 1
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>max
    </p></td>
    <td><p>maximum number of groups to identify in a single m/z slice  
    <br />   
    default value: 100
    </p></td>
  </tr>
</tbody>
</table>


<table style="width:100%;">
<caption style="text-align:left", align = "top"><b>Arguments for Statistics</b></caption>
<colgroup><col style="width: 30%" /><col style="width: 70%" />
</colgroup>
<thead>
  <tr VALIGN=TOP style="text-align:left" class="header">
    <th><p>Arguments</p></th>
    <th><p>Definitions</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
  <tr class="odd">
    <td><p>Statistical test
    </p></td>
    <td><p>Statistical test method: Welch t-test (unequal variances) or Wilcoxon Rank Sum test.  
    <br />  
    default: Kruskal-Wallis non-parametric.  
    <br />  
    another option: ANOVA (parametric)
    </p></td>
  </tr>
  <tr class="even">
    <td><p>Perform paired test
    </p></td>
    <td><p>The selected statistical test is performed as a paired test. The sample pairs need to be specified.
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>Perform post-hoc analysis
    </p></td>
    <td><p>	Perform post-hoc analysis [multigroup only]  
    <br />   
    default: True
    </p></td>
  </tr>
  <tr class="even">
    <td><p>p-value threshold (highly significant features)
    </p></td>
    <td><p> statistical figures (e.g. Mirror plot) are generated using only the dysregulated features according to this threshold.  
    <br />  
    default: 0.001
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>fold change threshold (highly significant features)
    </p></td>
    <td><p>	Features with a fold change greater than this threshold are considered highly significant. Some statistical figures (e.g. Mirror plot) are generated using only the dysregulated features according to this threshold.  
    <br />  
    default:  1.5
    </p></td>
  </tr>
  <tr class="even">
    <td><p>p-value threshold (significant features)
    </p></td>
    <td><p>	Features with a p-value less than this threshold are not considered significant and are omitted from some calculations to save time and space. EIC's, annotations and database ID's are not generated for features with p-values above this threshold.  
    default: 0.05
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>value
    </p></td>
    <td><p>	intensity values to be used for the diffreport.   
    <br />  
    If value="into", integrated peak intensities are used.   
    <br />  
    If value="maxo", maximum peak intensities are used.  
    <br />  
    default: into
    </p></td>
  </tr>
</tbody>
</table>


<table style="width:100%;">
<caption style="text-align:left", align = "top"><b>Arguments for Annotation</b></caption>
<colgroup><col style="width: 30%" /><col style="width: 70%" />
</colgroup>
<thead>
  <tr VALIGN=TOP style="text-align:left" class="header">
    <th><p>Title Left</p></th>
    <th><p>Title Right</p></th>
  </tr>
</thead>
<tbody VALIGN=TOP>
  <tr class="odd">
    <td><p>ppm
    </p></td>
    <td><p>	ppm error  
    <br />  
    default: 5
    </p></td>
  </tr>
  <tr class="even">
    <td><p>m/z absolute error
    </p></td>
    <td><p>m/z absolute error  
    <br />  
    default: 0.015    
    </p></td>
  </tr>
  <tr class="odd">
    <td><p>Search for
    </p></td>
    <td><p>Search for  
    <br />  
    1.) just isotopic features or   
    <br />  
    2.) isotopic features and adducts formations, dimers, trimers, neutral losses, etc.   
    WARNING: searching for all adducts can increase the total processing time by approximately 50 %  
    <br />  
    default: isotopes+adducts  
    <br />  
    option: isotopes
    </p></td>
</tbody>
</table>
