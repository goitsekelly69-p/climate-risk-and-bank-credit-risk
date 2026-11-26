# Business-Cycle Amplification of Climate-Related Credit Risk in Developing Economies: A Comparison Across Income Groups

## 1. Project Overview

This project investigates whether business-cycle weakness amplifies the effect of drought on banking-sector credit risk in developing economies.

Specifically, the study examines whether drought exposure is associated with higher non-performing loans (NPLs) during periods of weaker economic performance, and whether this relationship differs across income groups.

The empirical analysis uses annual panel data for 18 developing economies over the period 2005–2022. It applies a two-way fixed-effects panel regression framework to investigate the interaction between drought intensity and business-cycle weakness, considering both contemporaneous and delayed effects on non-performing loans.

The study also examines whether the potential amplification effect differs between low/lower-middle-income and upper-middle-income economies.

## 2. Research Objectives

The main objectives of the study are to:

- Examine the relationship between drought intensity and banking-sector credit risk, measured through non-performing loans.
- Investigate whether business-cycle weakness amplifies the relationship between drought intensity and non-performing loans.
- Examine whether the potential amplification effect is delayed by evaluating NPL outcomes from the contemporaneous period (t) to five years ahead (t+5).
- Investigate differences in the amplification relationship between low/lower-middle-income and upper-middle-income economies.
- Assess the robustness of statistical findings by accounting for multiple hypothesis testing.

## 3. Data and Sample

The study uses annual country-level data covering 18 developing economies from 2005 to 2022.

The initial sample consisted of 19 candidate economies. Argentina was excluded because it did not meet the minimum data-completeness requirement, resulting in a final sample of 18 countries.

**Low and Lower-Middle-Income Economies:**
- Uganda
- Rwanda
- Nigeria
- Kenya
- Ghana
- India
- Zambia
- Tanzania
- Bangladesh

**Upper-Middle-Income Economies:**
- Indonesia
- Malaysia
- Brazil
- Colombia
- Mexico
- Thailand
- Philippines
- Mauritius
- South Africa

### Data Sources

The analysis draws on two main data sources:

**World Bank – World Development Indicators (WDI)**

Used to obtain macroeconomic and banking-sector indicators, including non-performing loans, GDP growth, inflation, private-sector credit and bank capitalisation.

**World Bank – Climate Change Knowledge Portal (CCKP)**

Used to obtain annual precipitation and temperature data from the CRU TS 4.07 climate dataset.

The climate reference period is 1991–2020, while the empirical estimation period covers 2005–2022.

## 4. Variables and Measurement

The empirical analysis incorporates the following variables:

| Variable | Measurement |
|---|---|
| Non-performing loans (NPL) | Bank non-performing loans as a percentage of total gross loans |
| Drought intensity | Standardised national precipitation anomaly, with the sign reversed so higher values indicate drier-than-normal conditions |
| Business-cycle weakness | Deviation of annual GDP growth from each country's average growth rate, standardised within country |
| Inflation | Annual consumer price inflation (%) |
| Private credit | Domestic credit to the private sector as a percentage of GDP |
| Bank capitalisation | Bank capital to total assets (%) |

### Construction of Drought Intensity

Drought intensity is constructed using annual national precipitation data.

Precipitation is standardised relative to each country's 1991–2020 climate normal:

Precipitation Z-score = (Annual precipitation − Climate normal mean) / Climate normal standard deviation

The sign is then reversed:

Drought Intensity = − Precipitation Z-score

Consequently, higher values represent drier-than-normal conditions.

### Construction of Business-Cycle Weakness

Business-cycle weakness is measured as the difference between each country's average GDP growth rate and its observed annual GDP growth rate.

The resulting measure is standardised within each country. Higher values therefore represent economic growth that is weaker than the country's own average performance.

An interaction term between drought intensity and business-cycle weakness is subsequently constructed to investigate whether drought exposure has a stronger association with non-performing loans during periods of weaker economic activity.

## 5. Econometric Methodology

The study employs a two-way fixed-effects panel regression framework.

The baseline empirical specification examines the relationship between drought intensity, business-cycle weakness and their interaction:

NPL(i,t+h) = α + β1 Drought(i,t) + β2 Cycle(i,t) + β3 [Drought(i,t) × Cycle(i,t)] + γX(i,t) + μ(i) + λ(t) + ε(i,t)

Where:

- NPL(i,t+h) represents the non-performing loan ratio at horizon h.
- Drought(i,t) represents drought intensity.
- Cycle(i,t) represents standardised business-cycle weakness.
- The interaction term captures whether drought intensity has a stronger association with NPLs when economic conditions are relatively weak.
- X(i,t) represents the control variables.
- μ(i) represents country fixed effects.
- λ(t) represents year fixed effects.
- ε(i,t) represents the error term.

### Estimation Approach

The analysis incorporates:

- Country fixed effects to account for time-invariant country-specific characteristics.
- Year fixed effects to capture common shocks affecting countries in a given year.
- Country-clustered standard errors to account for within-country correlation over time.
- Inflation, private credit to GDP and bank capitalisation as control variables.

The model is estimated separately for six outcome horizons, from t to t+5, to investigate whether the relationship between drought exposure and non-performing loans emerges with a delay.

The future NPL observations are matched using calendar years to ensure that gaps in the unbalanced panel are not incorrectly treated as consecutive observations.

### Income-Group Analysis

The analysis is extended by estimating the model separately for:

1. Low and lower-middle-income economies.
2. Upper-middle-income economies.

A pooled triple-interaction model is then estimated to formally test whether the drought and business-cycle amplification coefficient differs between the two income groups.

### Multiple Hypothesis Testing

The Holm (1979) sequential multiple-testing procedure is applied to the six interaction p-values at each stage of the analysis.

Both unadjusted and Holm-adjusted p-values are reported to account for the increased probability of obtaining statistically significant results when testing multiple horizons.

## 6. Empirical Findings

### Full-Sample Results

The full-sample estimates indicate that the interaction between drought intensity and business-cycle weakness becomes positive at t+1 and reaches its largest positive value at t+2.

At the two-year horizon, the estimated interaction coefficient is 0.2443, with an unadjusted p-value of 0.0980.

Although the positive coefficient is consistent with the amplification hypothesis, it does not remain statistically significant after the Holm multiple-testing correction. The adjusted p-value is 0.5881.

The interaction coefficients become negative from t+3 onwards, providing no evidence of a persistent amplification effect over the longer horizons.

### Income-Group Results

The subgroup analysis produces a stronger positive interaction for low/lower-middle-income economies at the two-year horizon.

For this group, the estimated coefficient is 0.7692, with an unadjusted p-value of 0.0096.

In comparison, the estimated coefficient for upper-middle-income economies is -0.1150, with an unadjusted p-value of 0.0362.

The signs of the coefficients suggest differences in the relationship across the two income groups at this horizon.

However, the subgroup estimates alone do not establish that the coefficients are statistically different.

### Formal Income-Group Difference

The pooled triple-interaction model produces an estimated coefficient of 0.7104 at t+2, with an unadjusted p-value of 0.0253.

This suggests a stronger amplification relationship in low/lower-middle-income economies at the two-year horizon.

However, the result does not remain statistically significant after the Holm correction, with an adjusted p-value of 0.1515.

Consequently, the evidence does not establish a statistically robust difference between the two income groups.

## 7. Conclusion

The findings provide suggestive evidence of a delayed relationship between drought intensity, business-cycle weakness and banking-sector credit risk in developing economies.

The strongest positive interaction in the full sample occurs at the two-year horizon. The income-group analysis also indicates a stronger positive interaction among low/lower-middle-income economies at the same horizon.

However, these findings are statistically fragile and do not survive the relevant multiple-testing corrections.

Overall, the study does not provide sufficient statistical evidence to reject the null hypothesis that the effect of drought intensity on non-performing loans does not depend on business-cycle conditions.

The findings highlight the importance of considering both climate-related shocks and macroeconomic conditions when investigating banking-sector credit risk, while also demonstrating the need for further empirical research.

## 8. Limitations

The study identifies several limitations:

- The final panel contains a maximum of 18 country clusters, which limits the reliability of conventional cluster-robust inference.
- The six outcome horizons introduce a multiple-testing problem, which is addressed through the Holm correction but reduces statistical power.
- The climate data used in the analysis end in 2022, limiting the estimation period.
- Drought intensity is measured using national precipitation anomalies and does not incorporate temperature, evapotranspiration or soil moisture.
- Cross-country comparisons of non-performing loans may be affected by differences in banking systems and reporting practices.

## 9. Tools and Technologies

The project uses Python for data collection, data preparation, econometric estimation and statistical analysis.

**Programming Language:**
- Python

**Libraries:**
- Pandas – Data manipulation and preparation.
- NumPy – Numerical computations and variable construction.
- Requests – Retrieval of data through external APIs.
- Linearmodels – Panel data econometric estimation.
- Statsmodels – Statistical procedures and multiple-testing correction.

**Development Environment:**
- Jupyter Notebook

## 10. Repository Contents

This repository contains the following project materials:

- `analysis.ipynb` – The Jupyter Notebook containing the Python implementation, data collection, data preparation, variable construction, econometric estimation and empirical analysis.
- `research-report.pdf` – The accompanying research report documenting the research background, objectives, literature, data, methodology, empirical findings and conclusions.

## 11. Research Status and Usage Notice

**Research Status: Unpublished Academic Research**

This project represents original academic research undertaken as part of my academic work. It has not been formally published in an academic journal, book, conference proceeding or other scholarly publication.

The materials are made publicly accessible through this repository solely for portfolio and demonstration purposes, to showcase my research, programming and econometric analysis capabilities.

**Copyright and Usage Restrictions**

© 2026 [Goitse Kelly Pule]. All rights reserved.

The research report, Python notebook, analysis, interpretations and associated original materials remain the intellectual property of their respective rights holders.

Public access to this repository does not constitute permission to reproduce, redistribute, modify, adapt, commercially exploit or otherwise use these materials without prior written permission from the relevant rights holder.

**Citation Notice**

This work is not a formally published academic source and should not be represented or cited as a published journal article, book or peer-reviewed research publication.

Please do not cite, reference, reproduce or incorporate this work into academic publications, research papers, dissertations, theses or other scholarly submissions.

## 12. Reproducibility

The analysis retrieves macroeconomic and climate data through external APIs. Reproducing the analysis requires Python, the relevant packages and an active internet connection.

The accompanying Jupyter Notebook provides the implementation of the empirical analysis.

## 13. References

The research draws on literature relating to climate-related financial risks, banking-sector stability, business-cycle fluctuations, panel econometrics and multiple hypothesis testing.

Key methodological references include:

- Bernanke, Gertler and Gilchrist (1999) – Financial Accelerator Theory.
- Holm (1979) – A Simple Sequentially Rejective Multiple Test Procedure.
- Jordà (2005) – Estimation and Inference of Impulse Responses by Local Projections.
- Pesaran, Shin and Smith (1999) – Pooled Mean Group Estimation of Dynamic Heterogeneous Panels.
- Cameron, Gelbach and Miller (2008) – Bootstrap-Based Improvements for Inference with Clustered Errors.

The full reference list is available in the accompanying research report.
