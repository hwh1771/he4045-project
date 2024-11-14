# HE4045 Quantitative Economics with Data Science Project 
--------

Our study aims to further our understanding of the factors driving income inequality in China. As previous research has mostly worked on income factors, we will be particularly focusing on non-income factors that may contribute to this income divide. By determining these non-income features, we intend to identify and recommend policies that could possibly reduce income disparities. Conclusively, we will simulate these policies using economic models and evaluate their potential effectiveness in narrowing income inequality.


## ARIMAX Modelling
--------
To identify key factors that affect Gini coefficient, we decided to use ARIMAX models to figure out the regressors that are significant. Given the time-series nature of the data and the autoregressive characteristics of both the Gini coefficient and GDP, the ARIMAX framework is particularly suitable for this analysis.

Our regressors consist of variables that can measure impacts of policies like education, urbanisation, healthcare, technology accessibility and employment levels. 

We find that the common significant regressors that affect Gini Coefficient as well as GDP are ‘Percentage of Urban Population’ as well as ‘ Percentage of Uni Educated’.


## Macroeconomic Modelling
--------
We implement two models with different premises and observe inequality dynamics in each.

<b>1. Structural transformation in development model (Urbanisation)</b>
This model seeks to explain the effect of migration between a rural and urban economy on a country's overall inequality.  

<b>2. Human Capital Investments wIth Imperfect Credit Markets Model (Education)</b>
This model focuses on how individual's decisions on investing in their own education leads to the existence of the poverty trap. We incorporate shocks to wages to allow families to 'escape' the poverty sink. Through simulations of this model, we demonstrate that the trend in inequality within rural and urban China separately can be explained by both the aforementioned migrartion (out of rural areas and into urban areas) and policy changes in education cost. 


