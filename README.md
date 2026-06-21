# Enterprise Predictive Analytics — LEGO Market Valuation

An Excel-based predictive analytics project modeling the secondary market value of 2,322 LEGO sets (1981–2014) using OLS regression, theme-level ROI analysis, and interactive forecasting tools.

---

## Overview

This project extends descriptive analysis of the LEGO secondary market into the predictive domain — moving from "what happened" to "what drives value and what can we expect." Using Ordinary Least Squares (OLS) regression, the model identifies which set characteristics (piece count, retail price, theme, year) are statistically significant predictors of secondary market performance, and quantifies their impact.

The workbook is structured as an enterprise-ready analytics deliverable: modular sheets, formula-driven outputs, a working price prediction tool, and full residual diagnostics.

---

## What's Inside

**Raw Data** — 2,322 LEGO sets with attributes including theme, year of release, piece count, retail price (USD), and secondary market value.

**OLS Regression Model** — built using Excel's Data Analysis Toolpak. Outputs include coefficients, R², adjusted R², standard errors, t-statistics, and p-values for each predictor variable.

**Price Prediction Tool** — an input-driven calculator where users enter a set's characteristics (pieces, theme, year) and receive an estimated secondary market value based on the fitted regression model.

**Theme-Level ROI Analysis** — calculates return on investment per LEGO theme by comparing average retail price to average resale value, ranking themes by investment efficiency.

**Residual Analysis** — plots of residuals vs. fitted values and a normality check to assess model assumptions and identify patterns the model doesn't capture.

**Interactive Dashboard** — PivotTable-powered charts and slicers for dynamic exploration of actual vs. predicted values, theme performance, and pricing distributions.

---

## Key Questions Answered

- Which variables are statistically significant predictors of LEGO secondary market value?
- How well does piece count or retail price alone explain resale performance?
- Which themes offer the best ROI from retail to resale?
- Where does the model underperform — which set types are hardest to predict?
- Given a new set's attributes, what secondary market value can be expected?

---

## Methodology

The regression was run using Excel's built-in Data Analysis Toolpak (OLS). Predictor variables include retail price, piece count, year of release, and theme (encoded categorically). Model fit was evaluated using R² and adjusted R², and residual plots were used to check for heteroscedasticity and non-linearity.

---

## Tools Used

Microsoft Excel — Data Analysis Toolpak (OLS regression), PivotTables, PivotCharts, slicers, formula-linked prediction inputs, and conditional formatting.

---

## Dataset

The dataset covers 2,322 officially released LEGO sets from 1981 to 2014, spanning licensed and original product lines, with both retail and secondary market pricing.

---

## Relationship to Prior Work

This project is the predictive follow-up to [Descriptive Analytics Dashboard — LEGO Investment & Pricing Trends](https://github.com/rahmanazir5087-source/Descriptive-Analytics-Dashboard-of-LEGO-Investment-and-Pricing-Trends), which explored the same dataset using statistical summaries and visualizations. The two projects together form a complete analytics pipeline from exploration to modeling.

---

## Academic Context

Completed as part of the Business Analytics program at FAST-NUCES Islamabad, with a focus on predictive modeling and data-driven decision-making using Excel.
