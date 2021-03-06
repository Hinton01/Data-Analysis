# 用R进行探索性数据分析

## 项目背景及目的

Prosper是美国的一家P2P在线借贷平台网站。网站撮合了一些有闲钱的人和一些急于用钱的人。用户若有贷款需求，可在网站上列出期望数额和可承受的最大利率。潜在贷方则为数额和利率展开竞价。卖家可以获得比银行更高的利息收入，而对于买家来说，除了过程快捷便利和可以获得较低的还款利率外，更主要的是你不需要经过漫长的审查过程，不会遇到在银行申请贷款遭拒时的尴尬。本案例试图从EDA分析角度出发，分析Propser数据集中贷款人条件及贷款利率等问题。


## 项目步骤

#### 第一步 - 选择数据集

首先，从[数据集选项](https://github.com/udacity/new-dand-advanced-china/blob/master/%E6%8E%A2%E7%B4%A2%E6%80%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90/%E9%A1%B9%E7%9B%AE/%E6%8E%A2%E7%B4%A2%E6%80%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E6%95%B0%E6%8D%AE%E9%9B%86.md)文档中选择了来⾃Prosper的贷款数据。此数据集包含 113,937项贷款，每项贷款有81个变量，包括贷款⾦额、借款利率（或利率）、当前贷款状态、借款⼈收⼊、借款⼈就业状态、借款⼈信⽤历史及最新⽀付信息。


#### 第二步 - 探索性数据分析，并记录分析

在提交的 RMD 文件中记录探索和分析工作，应依次包含：

1. 以意识流方式对数据进行的分析和探索。

   a. 应通过标题和文本组织想法，以及反映在探索数据时的分析工作。

   b. 该分析中的图形无需通过标签、单位和标题来修饰；这些图形是探索性的。但是，它们应具有合适的类型，并能有效传递从中搜集的信息。

   c. 可以在相同的 R 区块中迭代图形，但无需在分析中说明每一次的图形迭代。

2. “最终图形和摘要”结尾部分

   a. 你将从分析报告中选择三个图形来进行修饰，并在这一部分中进行分享。三个图形应该呈现不同的趋势，并且应该由合适的标签、单位和标题来修饰。

3. 称为“反思”的最终部分

   a. 在该部分中，应尽力说明对以上探索数据集的想法和反思，以及对未来进一步探索的想法。

#### 第三步 - 拼合 RMD 文件，并提交

拼合的RMD文件不应该是一个很长的R代码块。它应包含文本和穿插于其中的图形，目的是使阅读该文件的读者能够深入了解我在探索数据时思考的问题。

### 软件及库
- RStudio
- R的相关库：ggplot2, dplyr, reshape2, GGally, gridExtra, MASS, memisc, knitr

### 文件描述

- LoanData_EDA.Rmd: 完整的探索性分析代码文件
- prosperLoanData.csv: 原始贷款数据集
- DataVariableDefs.xlsx: 数据集中变量的解释
- README.md

