# Applied Statistics and Reliability Analysis in R

## Project Overview

This repository presents a two-phase set of applied engineering statistics projects completed as part of the Industrial Engineering curriculum at Sharif University of Technology.

The projects combine statistical theory, data analysis, simulation, and regression modeling using R. They cover hypothesis testing, parameter estimation, confidence intervals, statistical quality control, reliability analysis, and regression diagnostics.

The work emphasizes the practical application of statistical methods, validation of assumptions, interpretation of results, and reproducible computational analysis.

## Project Objectives

- Apply statistical inference methods to real and illustrative datasets.
- Evaluate statistical assumptions and select appropriate hypothesis tests.
- Implement Monte Carlo simulations to investigate estimator properties.
- Analyze acceptance-sampling plans and operating characteristic curves.
- Estimate component reliability using lifetime models.
- Develop and evaluate regression models using statistical diagnostics.

## Project Topics

### 1. Exploratory Data Analysis and Hypothesis Testing

- Exploratory data visualization using `ggplot2`
- Normality and variance-assumption checks
- Parametric and non-parametric hypothesis testing
- Welch's t-test, Wilcoxon rank-sum test, and correlation analysis
- Statistical power and sample-size analysis
- Construction of a standardized composite academic index

### 2. Statistical Quality Control and Simulation

- Single-sampling plans and acceptance probabilities
- Operating characteristic (OC) curve analysis
- Normal-distribution probability calculations
- Monte Carlo simulation
- Box–Cox transformation and distributional assessment

### 3. Parameter Estimation and Statistical Inference

- Method of Moments (MoM) and Maximum Likelihood Estimation (MLE)
- Bias, unbiasedness, and consistency
- Cramér–Rao lower bound and estimator efficiency
- Exact and bootstrap confidence intervals
- Simulation-based evaluation of estimator behavior

### 4. Reliability Analysis

- Statistical modeling of component lifetimes
- Exponential lifetime distribution
- Reliability estimation at a specified operating time
- Bootstrap confidence intervals for reliability estimates

### 5. Simple Linear Regression

- Ordinary Least Squares (OLS) estimation
- Relationship between process temperature and material hardness
- ANOVA and variance decomposition
- Confidence intervals and prediction
- Residual analysis and model-assumption diagnostics

## Selected Quantitative Results

The English research summary reports the following results from the analyses:

| Analysis | Selected Result |
|---|---|
| Acceptance sampling | For a sampling plan with \(n=60\) and \(c=3\), the acceptance probability at a 5% defect rate was approximately 64.73%. |
| Estimation theory | The estimated exponential lifetime parameter was 356.95 hours. |
| Reliability analysis | Estimated reliability at 500 hours was approximately 24.64%. |
| Linear regression | The temperature–hardness model achieved \(R^2=0.9338\) on a dataset of 40 observations. |
| Regression diagnostics | The residual normality test yielded \(p=0.391\), providing no evidence against normality at conventional significance levels. |

These figures are reported results from the course projects and should be interpreted in the context of their respective datasets and modeling assumptions.

## Tools and Libraries

- **Language:** R
- **Data manipulation:** `dplyr`, `tidyverse`
- **Data visualization:** `ggplot2`
- **Statistical analysis:** Base R statistical functions
- **Additional packages:** `MASS`, `pwr`
- **Computational methods:** Monte Carlo simulation and bootstrap resampling

## Research Summary

An English-language summary of the two-phase project is available as a separate PDF. It provides an overview of the methods, selected numerical results, and statistical conclusions.

**[Read the English Research Summary (PDF)](English_Research_Summary.pdf)**

The summary is intended as a concise introduction to the project. The complete reports contain the detailed analyses and interpretations in Persian.

## Repository Structure

```text
applied-statistics-and-reliability-analysis/
├── README.md
├── English_Research_Summary.pdf
├── R_Code/
│   ├── Phase_1/
│   └── Phase_2/
└── Full_Reports/
    └── Persian_Reports/
```

The directory structure above is a suggested organization. Include only files and folders that have actually been uploaded to the repository.

## Academic Context

**Field:** Industrial Engineering  
**Institution:** Sharif University of Technology  
**Course:** Engineering Statistics  
**Project Format:** Two-phase applied statistical analysis

This work demonstrates the application of statistical reasoning and computational methods to data analysis, quality control, reliability assessment, and engineering modeling.
