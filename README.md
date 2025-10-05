
# Multinomial Single Index Model with Extended Smooth Terms using MGCV


## Table of Contents
- [Introduction](#Introduction)
  - [Research Objectives](#research-objectives)
- [Literature Review](#Literature-Review)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Selection](#model-selection)
- [SUMMARY OF RESULTS](#summary-of-results)


## Introduction
This study focuses on the application of the Single-Index Model (SIM) for analyzing road traffic accident data. The goal is to understand the nonlinear relationships between accident rates and multiple predictors such as weather conditions, road types,and traffic controls. By extending the traditional SIM to accommodate multinomial response variables, this research aims to enhance predictive accuracy and provide actionable insights for improving road safety.The choice of this assignment is motivated by the critical need to reduce road traffic accidents and improve transportation safety. The primary analysis questions revolve around identifying key predictors of road accidents, understanding their impact, and evaluating high-risk areas. The challenge lies in managing complex, nonlinear interactions between multiple predictors and accident rates. Solving these problems is expected to contribute significantly to policy making and resource allocation, ultimately reducing accidents and saving lives. The Single-Index Model (SIM) is a semiparametric regression technique that simplifies the analysis of complex datasets by reducing multiple predictors into a single index.  This model $$
\begin{aligned}
Y &= g(X^{\prime}\alpha)+ \epsilon
\end{aligned}
$$ assumes a non-linear relationship between the response variable (accident rates) and the predictors. In this study, SIM is extended to handle multinomial response variables by incorporating additive component functions alongside the single-index function. Key concepts include the link function  \cite{han2020adaptive} $g(X^{\prime}\alpha)$ where $\alpha$ represents the weights of the predictors and $g(.)$ captures the nonlinear relationship.

### Research Objectives
