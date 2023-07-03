---
weight: 3
title: Dunn's Test (2)
authors: Lenny Lin
categories: 
tags: null
description:
draft: true
date: "2023-07-01"
lastmod: "2023-07-01"
series: null
toc: true
---





<!--more-->
---

<h1> What is Dunn's test?</h1>
We firstly use a Kruskal-Wallis test to determine whether or not there is a statistically significant difference between the medians of three or more independent groups. <a class = "marginnote">The Kruskal-Wallis test is considered to be the non-parametric equivalent of the One-Way ANOVA.</a> 

If the results of the Kruskal-Wallis test are statistically significant, then it’s appropriate to conduct Dunn’s Test to determine exactly which groups are different.

Dunn’s Test performs pairwise comparisons between each independent group.

For example, suppose a researcher wants to know whether three different drugs have different effects on back pain. He recruits 30 subjects for the study and randomly assigns them to use Drug A, Drug B, or Drug C for one month and then measures their back pain at the end of the month.

The researcher can perform a Kruskal-Wallis test to determine if the median back pain is equal among the three drugs. If the p-value of the Kruskal-Wallis test is below a certain threshold, it can be said that the three drugs produce different effects. 

Following this, the researcher could then perform Dunn’s Test to determine which drugs produce statistically significant effects.


<h1>The Formula</h1>
$$
\begin{equation}
z_i=\frac{y_i}{&delta;_i}
\end{equation}
$$

where i is one of the 1 to m comparisons, y<sub>i</sub> =W<sub>A</sub> – W<sub>B</sub> (where W<sub>A</sub> is the average of the sum of the ranks for the i<sup>th</sup> group) and &delta;<sub>i</sub> is calculated as:
$$
\begin{equation}
&delta;_i = \sqrt{\frac{N(N+1)}{12}-\frac{\sum(T^3_s)-\frac{T_s}{(12(N-1)}}{(\frac{1}{n_A}+\frac{1}{n_B})}}
\end{equation}
$$

where N is the total number of observations across all groups, r is the number of tied ranks, and T<sub>s</sub> is the number of observations tied at the sth specific tied value.


<h1>Control the family-wise error rate</h1>

Whenever we make multiple comparisons at once, it’s important that we control the family-wise error rate. One way to do so is to adjust the p-values that results from the multiple comparisons.

There are several ways to adjust the p-values, but the two most common adjustment methods are:

<ol>
<li>The Bonferroni Adjustment
$$
\begin{equation}
\text{Adjusted p-value} = p \times m
\end{equation}
$$
where:
<br><b>p</b>: The original p-value
<br><b>m</b>: The total number of comparisons being made
<br>
</li>
<li>The Sidak Adjustment
$$
\begin{equation}
\text{Adjusted p-value} = 1 – (1-p)^m
\end{equation}
$$
where:
<br><b>p</b>: The original p-value
<br><b>m</b>: The total number of comparisons being made
<br><br>By using one of these p-value adjustments, we can dramatically reduce the probability of committing a type I error among the set of multiple comparisons.</li>
</ol>


Reference: <a href = "https://www.statology.org/dunns-test/" target="_blank" rel="noopener noreferrer">Statology | Dunn's Test for Multiple Comparisons</a>