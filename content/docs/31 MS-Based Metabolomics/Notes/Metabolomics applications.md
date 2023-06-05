---
title: "Metabolomics Application"
author: "Lenny Lin"
date: "21/04/2022"
---




[2016: 代谢组学技术在临床医学中的应用](https://med.sina.com/article_detail_103_1_15636.html)

[干货：常用的差异代谢产物分析方法及常见问题](https://zhuanlan.zhihu.com/p/371031340)

[代谢组学数据处理——代谢通路分析](https://www.metaboprofile.com/school/1961/) 
通过上述方法筛选到差异代谢物后，还需要挖掘和这些代谢物相关的代谢通路。此时，可以采用MetaboAnalyst网站(http://www.metaboanalyst.ca/)进行代谢通路分析（Metabolic pathway analysis），代谢通路分析分为富集分析（Enrichment analysis）和通路分析（pathway analysis）。通路分析中添加了通路拓扑分析 （topology analysis），会输出通路在整体网络中的重要性（impact）。下图展示了典型的代谢通路分析图。

[代谢组学数据处理——差异代谢物筛选]
筛选差异代谢产物通常基于OPLS-DA模型，因为它更易于进行模型解释，所有跟分组相关的信息都集中于第一维。筛选的标准通常是基于以下两个指标：

Corr.Coeffs./p(corr) （Correlation Coefficient），是样本得分值t和变量X间的相关系数-Corr(t, X)，代表了变量的可靠度。该值没有固定阈值，通常设定对应的P值 < 0.05。
VIP （Variable importance in the projection），为变量对模型的重要性，描述了每一个变量对模型的总体贡献，通常设定阈值为VIP >1。

[推荐一个好用的差异代谢组分析工具！](https://m.sohu.com/n/488058350/)  

[代谢组学数据分析结果如何呈现？](https://zhuanlan.zhihu.com/p/376517497)

