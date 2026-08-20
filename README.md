# Trade Settlement Risk Model

An Excel-based probabilistic model for analyzing trade settlement failure risk, expected financial loss, and control optimization.

## Project Overview

I built this project to answer two questions:

1. What is the probability that a trade fails to settle?
2. Which stage of the process matters most if something goes wrong?

I mapped the trade lifecycle into six stages:

**Trade Capture → Validation → Confirmation → Clearing → Settlement → Reconciliation**

Each stage was assigned a probability of failure to estimate the overall settlement failure probability.

## Methodology

Rather than relying entirely on assumed probabilities, I anchored key assumptions to published industry data, including:

- ESMA data on EU equity settlement fail rates
- ERCC data on the causes of settlement fails

The model then uses:

- Binomial probability analysis
- Expected number of failed trades
- Cost-of-failure calculations
- Sensitivity analysis
- Control-point optimization

## Key Finding

The analysis identified settlement/delivery issues as the largest risk lever, consistent with the industry data used to inform the model.

## Tools & Concepts

- Microsoft Excel
- Probability & Statistics
- Binomial Distribution
- Sensitivity Analysis
- Operational Risk
- Trade Settlement
- Financial Modelling

## Project File

[Download the Excel Model](./Trade_Settlement_Risk_Model_Project.xlsx)

## Model Screenshots

### Assumptions
![Assumptions](screenshots/assumptions.png)

### Probability Analysis
![Probability Analysis](screenshots/probability_analysis.png)

### Sensitivity Analysis
![Sensitivity Analysis](screenshots/sensitivity_analysis.png)

### Dashboard
![Dashboard](screenshots/dashboard.png)
