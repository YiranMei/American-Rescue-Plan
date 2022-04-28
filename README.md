# The Effectiveness of Biden’s American Rescue Plan: Linear Regression Analysis

This report aims to investigate whether there is a statistically significant correlation between the growth of the U.S. economy in various aspects and the implementation of ARP using a number of economic indicators from the Federal Reserve Economic Data using R.

The paper is composed of the following sections: an introduction, a data section where the data is analyzed and examined, a model section where the regression model is developed, and a discussion section where the limitations and implications are assessed. The findings of this report will provide stakeholders with an insight into how to evaluate ARP policies and make better plans by taking into account findings.

It is evident from the simple linear analysis that the implementation of APR is associated with the decline in the unemployment rate. The unemployment rate declined by 2.8% following the introduction of the ARP, a result that is statistically significant at a significance level of 10%, but insignificant at a significance level of 5%. Nevertheless, there is no statistical evidence that the implementation of ARP reduces the unemployment rate, suggesting that it may be ineffective.

The final report can be viewed [here](https://github.com/YiranMei/American-Rescue-Plan).

## R Packages

In order to process the data and analysis, the following packages should be installed:

1.kableExtra()
2.ggplot2()
4.openxlsx()
5.jtools()
6.modelsummary()



## File Structure

All data are downloaded from the website of FRED, which refers to the Federal Reserve Economic Data, which is contained in the “input” folder.

Additionally, all related literature is kept in the "input" folder.

The "output" folder contains the original R Markdown file containing the analysis carried out in R, a PDF version of the final paper, and the reference list.