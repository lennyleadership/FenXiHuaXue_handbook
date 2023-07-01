---
weight: 2
title: Dunn's Test
authors: Lenny Lin
categories: 
tags: [Comparison, Post Hoc Test]
description:
draft: false
date: "2023-07-01"
lastmod: "2023-07-01"
series: null
toc: true
---



<!--more-->
---

<h1>What is Dunn's Test?</h1>
Dunn’s Multiple Comparison Test is a post hoc (i.e. it’s run after an ANOVA) non parametric test (a “distribution free” test that doesn’t assume your data comes from a particular distribution).

Once your initial ANOVA has found a significant difference in three or more means, Dunn’s Test can be used to pinpoint which specific means are significant from the others. 

It is one of the least powerful of the multiple comparisons tests and can be a very conservative test—especially for larger numbers of comparisons. 

<ol>
<li>The null hypothesis for the test is that there is no difference between groups (groups can be equal or unequal in size).</li>
<li>The alternate hypothesis for the test is that there is a difference between groups.</li>
</ol>

Dunn’s test divides the overall alpha level by the number of comparisons:
$$
\begin{equation}
\frac{Alpha_{EW}}{K}=Alpha_{PC}  
\end{equation}
$$


<h1>Dunn' test vs Tukey's Test and Dunnett</h1> 

The Dunn is an alternative to the Tukey test when you only want to test for differences in <b>a small subset</b> of all possible pairs.

For <b>larger numbers</b> of pairwise comparisons, use <b>Tukey’s</b> instead. Use Dunn’s when you choose to test a specific number of comparisons before you run the ANOVA and when you are <b>not comparing to controls</b>. If you are comparing to <b>a control group</b>, use the <b>Dunnett test</b> instead.


Reference: <a href = "https://www.statisticshowto.com/dunns-test/" target="_blank" rel="noopener noreferrer">Statistics How To | Dunn's test: Definition</a>