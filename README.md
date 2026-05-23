# Agricultural Resilience Modeling

This project applies business intelligence methods and predictive analytics to assess whether agricultural regions require adaptation measures in response to environmental and economic stressors. Using a synthetic dataset of 5,000 records generated via generative AI, the analysis spans exploratory data analysis, dimensionality reduction, clustering, and binary classification modeling across four machine learning approaches.

> **Note:** This project is intended for academic and portfolio purposes only. It should not be interpreted as a production-ready decision system or as professional agricultural, environmental, financial, or policy advice.

---

## Objective

The goal of this project is to predict whether a given agricultural region requires adaptation — represented as a binary target variable (`Adaptation_Required`: 1 = required, 0 = not required) — based on a combination of environmental, agronomic, and economic indicators. These include precipitation, temperature, soil type, water stress, crop yield, market access, technology access, and extreme weather events. The analysis is intended to demonstrate how predictive analytics and business intelligence methods can support proactive resource allocation, risk mitigation, and resilience planning for agricultural stakeholders at both local and national levels.

---

## Methods

| Category | Techniques |
|---|---|
| Exploratory Analysis | Exploratory data analysis |
| Interdependence Analysis | Principal component analysis, hierarchical clustering, k-means clustering |
| Dependence Analysis | Logistic regression, decision tree, neural networks, support vector machines, ensemble modeling |
| Model Evaluation | ROC curves, AUC, lift curves |

The neural network achieved the strongest overall performance, with a validation AUC 
of 0.939 and the highest lift values at the 10% and 30% thresholds. Logistic 
regression (validation AUC 0.933) is recommended where interpretability is a priority.

---

## Tools

- **JMP** — primary analysis environment (data, EDA, modeling, journals)
- **Microsoft Excel** — model comparison summaries and ROC/lift curve data

---

## Repository Contents

### Report
| File | Description |
|---|---|
| `Agricultural Adaptation Analysis [Report].pdf` | Final report covering methodology, analysis, model comparison, findings, and conclusions. |

### JMP Files
> Requires JMP software and a valid license to open.

| File | Description |
|---|---|
| `Agricultural Adaptation Analysis [Data].jmp` | Dataset used for all analyses. |
| `Agricultural Adaptation Analysis [EDA].jrn` | EDA outputs and visualizations. |
| `Agricultural Adaptation Analysis [Interdependence Analysis].jrn` | PCA, hierarchical clustering, and k-means clustering outputs. |
| `Agricultural Adaptation Analysis [Dependence Analysis].jrn` | Logistic regression, decision tree, and dependence analysis outputs. |
| `Agricultural Adaptation Analysis [Model Comparison].jrn` | Final model comparison outputs. |

### Excel Files
> Accessible without JMP.

| File | Description |
|---|---|
| `Agricultural Adaptation Analysis [Model Comparison].xlsx` | Summary of model comparison results. |
| `Agricultural Adaptation Analysis [ROC_Lift_LR].xlsx` | ROC and lift curve data — logistic regression. |
| `Agricultural Adaptation Analysis [ROC_Lift_NN].xlsx` | ROC and lift curve data — neural network. |
| `Agricultural Adaptation Analysis [ROC_Lift_SVM].xlsx` | ROC and lift curve data — support vector machine. |
| `Agricultural Adaptation Analysis [ROC_Lift_Ensemble].xlsx` | ROC and lift curve data — ensemble model. |

---

## Getting Started

Users **with JMP** can open all files for full interactivity.  
Users **without JMP** can review the PDF report and Excel workbooks for
methodology, results, and model evaluation outputs.

---

## Authors

Yash Mahadik, Vignesh Anand, Akshata Dalvi, and Sidhant Mandal

---

## License

Copyright © 2026 Yash Mahadik, Vignesh Anand, Akshata Dalvi, & Sidhant Mandal. All rights reserved.

This repository is intended for academic and portfolio reference only. The report, analysis files, datasets, visualizations, and supporting materials may not be copied, modified, redistributed, or used for commercial purposes without prior written permission from the authors.
