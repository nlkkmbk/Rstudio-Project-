# Rstudio-Project-

# Traffic Accident Distance — EDA & Regression Modeling (US 2023)

This repository contains an Exploratory Data Analysis (EDA) and regression modeling project on U.S. traffic accidents (2023).  
The main focus is the response variable **Distance** (roadway length affected by an accident, in miles) and how it relates to weather, geography, and infrastructure factors.

---

## Repository Contents

### Report (Final PDF)
- `SDS_301_REPORT (6) (2).pdf` — final report document.

### R Script (Code)
- `eda+model(res,qq)+evaluation+conf int (3).R`  
  Contains:
  - data cleaning + missing value handling
  - EDA plots
  - regression models (M1–M9)
  - residual diagnostics (QQ/residual plots)
  - model evaluation and confidence intervals

### Figures (PNG)
The following images are included and referenced in the report/analysis:

- `summary.png` — dataset summary / overview
- `isnull.png` — missing values visualization
- `numericalhist (1).png` — histograms for numerical variables
- `CorrelationNumeric (1).png` — correlation matrix of numeric variables
- `distance (1).png` — distribution of the target (Distance)
- `severity (1).png` — severity-related visualization
- `boxplots (1).png` — boxplots / distribution + outliers overview
- `outliers (1).png` — outlier-focused plot
- `log (1).png` — log-transformation related plot

#### Model Diagnostic Plots
Residual/diagnostic plots for each regression model:
- `M1 (1).png`
- `M2 (1).png`
- `M3 (1).png`
- `M4 (1).png`
- `M5 (1).png`
- `M6 (1).png`
- `M7 (1).png`
- `M8 (1).png`
- `M9 (1).png`

---

## How to Run the R Script

### 1) Requirements
Install R (and optionally RStudio).

Recommended packages commonly used in EDA/regression workflows:
```r
install.packages(c(
  "tidyverse",
  "ggplot2",
  "dplyr",
  "readr",
  "lubridate",
  "skimr",
  "DataExplorer",
  "corrplot",
  "car",
  "broom",
  "lmtest",
  "sandwich"
))
