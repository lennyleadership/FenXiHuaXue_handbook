---
weight: 12
authors: edited by Lenny Lin
categories: 
date: "2022-01-03"
description: null
draft: false
lastmod: "2022-07-09"
series: 
tags: []
title: 12 Interpretation of the ANOVA Results
toc: true
---

The ANOVA tells us whether one factor is a significant factor that makes experiment different.  

We need to compare pairs of means to see which level is outstanding level among many levels (greater than three)


<!--more-->

After performing `the analysis of variance` using Excel, we have the resulting ANOVA table. The first column presents our three sources of variation, the cotton percentage, that is our treatments, the error and the total. The following column presents the sum of squares. We have 475.76 for the cotton percentage, 161.20 for the error and 636.96 for the total sum of squares. The third column presents the degrees of freedom: 4 for cotton percentage, 5 percentages minus one. 24 for the total, 25 observations minus one. And the error is the difference between them: 20. The next column shows the mean squares, the ratio between the sum of squares and the degrees of freedom. And finally we F<sub>0</sub>. That is the ratio between the mean squares of the treatments and the mean squares of the error. Now we have to compare F<sub>0</sub> with our F<sub>critical</sub> of 2.866. To remember... We should reject the null hypothesis H<sub>0</sub>. If F<sub>0</sub> is higher than the F<sub>critical</sub>. As the F<sub>0</sub> or 14.76 is higher than our F<sub>critical</sub> of 2.87 As the F<sub>0</sub> of 14.76 is higher than our F<sub>critical</sub> of 2.87 we should reject the null hypothesis and accept that at least one of the cotton percentages does affect the tensile strength. However, we can see an additional column here, the p-value. The p-value is the smallest level of significance of that the results are significant. In this case, the p-value of 9.01x10<sup>-6</sup> means that we are 99.99909% Sure that the cotton percentage affects the tensile strength. In simple words, as the p-value decreases, the more significant is the effect. That's being analysed. 