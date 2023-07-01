---
weight: 1
title: Method Comparison Regression
authors: Lenny Lin
categories: 
tags: null
description:
draft: false
date: "2022-10-03"
lastmod: "2022-10-03"
series: null
toc: true
---

<!--more-->
---

This function compares two methods of measurement using linear regression techniques that can accommodate errors in both dimensions (test method Y vs. reference method X).  

Two main types of regression are offered: Deming and Passing-Bablok.  

Deming regression is an extension of simple linear regression to handle random measurement errors in X as well as Y variables ([Cornbleet & Gochman, 1979](http://www.clinchem.org/content/25/3/432.long)). So Deming regression considers both X and Y to be subject to measurement error whereas simple regression allows only the Y variable to be measured with error. The X and Y variables in Deming regression may contain repeated measurements or may be single measurements from each subject. You should not use this method with small samples (less than 40).  

Deming regression can accommodate differences in measurement errors between the test and reference methods. The default procedure assumes no difference, in other words an "error ratio" of 1. If there is a difference then change this value to the variance ratio between the methods (see [F test](https://www.statsdirect.com/help/parametric_methods/f_variance_ratio.htm)).  

If the differences between the test and reference observations tend to be different with higher or lower values of the factor being measured then the data are heteroscedastic. In this case a Deming regression breaks an important linear regression assumption about the distribution of residuals. To overcome this problem a weighted Deming regression is offered, using weights equal to the reciprocal of the square of the reference value - which is more robust to heteroscedasticity.  

Where Deming regression expects errors to be from a normal distribution, Passing-Bablok regression is a non-parametric method that does not make any assumptions about the distributions of the samples or their measurement errors ([Passing and Bablok, 1983](http://www.ncbi.nlm.nih.gov/pubmed/6655447)). The method does, however, assume the two variables are highly correlated and have a linear relationship.  

Different methods for calculating confidence intervals are offered. For Deming and weighted Deming regression [Linnet (1993)](http://www.clinchem.org/content/39/3/424.long) recommends the jackknife (leave one out resampling) method. For Passing-Bablok regression a nested bootstrap (bias corrected and accelerated) interval is preferred, but this can take a very long time with large datasets, where an approximate Passing-Bablok procedure may be more practical.  

If the confidence interval for the slope does not contain the value 1 then you reject the null hypothesis that the slope is equal to 1 - in other words there is statistically significant evidence of at least a proportional difference between the two methods.  

If the confidence interval for the intercept does not contain the value 0 then you reject the null hypothesis that the intercept is equal to 0 - in other words there is statistically significant evidence that the methods differ by at least a constant amount.  

A scatter plot is given with each regression by default, showing the fitted regression line with a confidence interval, the identity line (methods equal) and the regression equation. This plot enables you to see the observations and how well the methods of measuring them agree, with the disagreement reflecting the bias and likely range of bias.  

You can select a residual plot, which is useful for spotting outliers and non linear patterns, and for checking how the agreement varies over the range of measurement.  

You can also select a Bland-Altman agreement plot displaying differences vs. means within standard limits of agreement.  

**Technical Validation**  

StatsDirect produces a R script to execute these methods via the MCR package developed by E. Manuilova, A. Schuetzenmeister and F. Model at the pharmaceutical company Roche.  

Source: [cran.r-project.org/web/packages/mcr/](http://cran.r-project.org/web/packages/mcr/)  

Standard: The MCR package implements the [Clinical Laboratory and Standards Institute](http://www.clsi.org/) guidance EP09-A2 (Method Comparison and Bias Estimation Using Patient Samples; Approved Guideline – Second Edition.).  

Further analysis in R: You can choose to save the intermediate R script to your StatsDirect report. You can then run supplementary analyses. For example to estimate the bias and confidence interval at a given series of measurement levels (1 to 5) you could run the command calcBias(model1,x.levels=c(1,2,3,4,5)) for absolute bias or calcBias(model1,x.levels=c(1,2,3,4,5),type="proportional") for proportional bias. calcCUSUM(model1) will give a cumulative sum test with which you can assess linearity.  

**Example**  

From [MCR R package](http://cran.r-project.org/web/packages/mcr).  

Data: Test workbook (Agreement worksheet: Plasma Creatinine, Serum Creatinine).  

To run this example in StatsDirect: select the menu item (Analysis_Agreement_Method Comparison Regression); when asked to "Select Data for Test Method" highlight the Plasma Creatinine column of the Agreement worksheet in the Test workbook (test.xlsx) and right click on the mouse to select the data; when asked for the "Reference Method" choose Serum Creatinine in the same way; when presented with options select Regression Method: Deming and Charts: Test vs. Reference.  

**Method Comparison Regression**  

Test method: Plasma Creatinine  

Reference method: Serum Creatinine  

Sample size: 108  

Error ratio: 1  

 

<table style="width:100%; font-size: 60%">
  <caption style="text-align:left", align = "top"><b>Deming regression (analytic CI): </b></caption>
  <colgroup>
    <col style="width: 20%" /><col style="width: 20%" /><col style="width: 20%" /><col style="width: 20%" /><col style="width: 20%" />
  </colgroup>
  <thead>
  <tr style="text-align:left" class="header">
    <th><p></p></th><th><p>Estimate</p></th><th><p>Standard Error</p></th><th><p>95% CI</p></th><th><p>Meaning</p></th>
  </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td VALIGN=Middle><p>
      Slope:
      </p></td>
      <td VALIGN=TOP><p>
      1.054539
      </p></td>
      <td VALIGN=TOP><p>
      0.024883
      </p></td>
      <td VALIGN=TOP><p>
      1.005207 to 1.103872
      </p></td>
      <td VALIGN=TOP><p>
      Proportional differences
      </p></td>
    </tr>
    <tr class="even">
      <td><p>
      Intercept:
      </p></td>
      <td><p>-0.058913
      </p></td>
      <td><p>0.034375
      </p></td>
      <td VALIGN=TOP><p>
      -0.127066 to 0.009239
      </p></td>
      <td VALIGN=TOP><p>
      Systematic differences
      </p></td>
    </tr>
  </tbody>
</table>



<img width ="360" height= "200" src = "/docs/images/deming_regression.png" />  

[**Reference**: statsdirect. Method Comparison Regression](https://www.statsdirect.com/help/agreement/mcr.htm)
