---
weight: 5
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: null
draft: false
lastmod: "2022-07-08"
series: 
tags: []
title: 05 Hypothesis Testing (t-Test & F-Test)
toc: true
---




<!--more-->

Now, going back to our initial problem: the results from an experiment are considered as <mark>a sample of the population</mark>. From the data we know that the sample mean of the unmodified formulation is slightly higher than the sample mean from modified one. However, <mark>the observed difference in the average results is due to the polymer addition or is due to the noise the system</mark>? In other words, <mark>is the difference significant</mark>? To answer this question, we are going to use <mark>a statistical technique called hypothesis testing</mark>. We are going to test two hypothesis: The null hypothesis, H<sub>0</sub>, that states that the means are equal, in our case, that the polymer addition does not affect the strength. And the alternative hypothesis, H<sub>1</sub>, that states that the means are different, in our case, the polymer addition does affect the strength.   

Suppose that we can assume that the variances of the tension bond strength are the same for both formulations, then the appropriate <mark>statistical test to compare them is the two-sample t-test</mark>. 

<center><img src="https://latex.codecogs.com/svg.latex?\space t_0 = \frac{\overline{y}_1 - \overline{y}_2}{S_p\sqrt{\frac{1}{n_1}+\frac{1}{n_2}}}" title="t_0 = \frac{\overline{y}_1 - \overline{y}_2}{S_p\sqrt{\frac{1}{n_1}+\frac{1}{n_2}}}"/></center>
 
<center><img src="https://latex.codecogs.com/svg.latex?\space S_p^2^ = \frac{(n_1 - 1)S_1^2^ + (n_2 - 1)S_2^2^}{n_1 + n_2 - 2}" title="S_p^2^ = \frac{(n_1 - 1)S_1^2^ + (n_2 - 1)S_2^2^}{n_1 + n_2 - 2}"/></center>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-08 204317.png" style ="float: left" HSPACE="10" VSPACE="10"/>
The quantity t<sub>0</sub> is calculated using the sample means and variances, and then compared to the t-distribution curve.   

The null hypothesis will be considered true, meaning the means are equal if the absolute value of t<sub>0</sub> is smaller than a critical t. For a significance level alpha, For a significance level alpha, it is expected that $100(1-\alpha)$\% of t<sub>0</sub> values to fall between minus t-critical -t<sub>$\alpha$/2, n_1+n_2-2</sub> and plus t-critical +t<sub>$\alpha$/2, n_1+n_2-2</sub>. The values of t-critical can be read in a table using <mark>the significance level and the number of observations</mark>. However, as we are going to use statistical software for our analysis, we are not going to use tables.   

<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-08 211812.png" style ="float: left" HSPACE="10" VSPACE="10"/>
This new term, the significance level alpha, is the probability of type I error, that is <mark>the probability of rejecting the null hypothesis when it is true</mark>. In our example, the probability of stating that the polymer does affect the result when it does not. We usually set alpha at 0.05 or 5%.   

And now one last detail before analyzing the two formulations of our example. <mark>The two-sample t-Test is applied for samples with equal variances</mark>. So we are going to check if the variances are equal or not. And the appropriate way is by using the F-test. Consider that we have a random sample of apples from Farm 1, with $n_1$ observations and variance $S_1$ to the square ($S_1^2$), and a random samples from Farm 2, with $n_2$ observations and variance $S_2$ to the square ($S_2^2$). If the two populations of apples from the two farms have the same variance, then $\sigma_1^2$ = <font color = "blue">$\sigma_2^2$</font>, $\sigma$ (sigma) is the variance of the populations, and the ratio between the two sample variances follows an $F_{n_1-1, n_2-1}$(F-distribution for $n_1$ minus 1 and $n_2$ minus 1 degrees of freedom). In practice, we are going to consider that the null hypothesis is true, meaning the variances of the populations are equal, if the ratio between the sample variances is lower than `a critical F`. In the same way of the t-Test, the values of `the critical F` can be read in the F-distribution tables for each significance level by crossing the degrees of freedom of the two samples.   

Now we have everything we need to compare the two formulations. We are going to use Microsoft Excel for this analysis. Please download the Microsoft Excel file cement and let's change to Microsoft Excel to start the analysis.  

