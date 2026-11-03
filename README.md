# AgriShift 🌾

### Agricultural Diversification & Crop Pattern Intelligence in India

**SDG 2 – Zero Hunger**

AgriShift is a machine learning project that analyses agricultural diversification and crop-specialization patterns across Indian districts using historical crop production data.

The project aims to discover how districts differ in their crop portfolios, identify districts with similar agricultural patterns, and analyse how these patterns change over time.

## Problem Statement

Indian districts have different agricultural structures depending on the crops they cultivate and the area allocated to each crop. Understanding these differences can reveal patterns of agricultural specialization and diversification.

AgriShift uses historical district-level crop data and machine learning to identify these patterns, group districts with similar agricultural characteristics, and detect significant changes in crop portfolios over time.

## Aim

To develop a machine learning-based analytical system that identifies and studies agricultural diversification and crop-specialization patterns across Indian districts.

## Objectives

1. Analyse historical crop production patterns across Indian districts.
2. Measure crop diversification and concentration at the district level.
3. Identify districts with similar agricultural crop portfolios using clustering.
4. Detect significant changes in crop composition over time.
5. Visualize the discovered agricultural patterns and present meaningful insights.

## Dataset

**Dataset:** District-wise, Season-wise Crop Production Statistics from 1997.

**Source:** Government of India – Open Government Data Platform.

**Dataset resource:** https://data.gov.in/resource/district-wise-season-wise-crop-production-statistics-1997

The downloaded dataset contains historical records from 1997 to 2015.

### Dataset Columns

| Column | Description |
|---|---|
| State_Name | State or Union Territory |
| District_Name | District name |
| Crop_Year | Year of crop production |
| Season | Agricultural season |
| Crop | Crop name |
| Area | Area under cultivation |
| Production | Recorded crop production |

## Planned Methodology

1. Data understanding and inspection
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Feature engineering for crop diversification and specialization
5. Agricultural portfolio analysis
6. Unsupervised machine learning and clustering
7. Analysis of unusual changes in crop patterns
8. Model evaluation and interpretation
9. Data visualization and final reporting

## Planned Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Important Limitations

- The analysis is based on the available historical crop dataset.
- The dataset does not contain weather, soil, irrigation, or market information.
- The project will identify statistical patterns, not establish their causes.
- It will not provide direct crop recommendations to farmers.
- The completeness and quality of historical records will be checked during preprocessing.

## Project Status

**Status:** Initial setup

The dataset has been selected. Data preprocessing, feature engineering, machine learning and visualization will be developed progressively.

---

*AgriShift – Discovering agricultural diversity through data and machine learning.*
