# Organ-Wise Health Risk Scoring System

## Overview

This project aims to develop a **health scoring system** that predicts the health status of individuals based on organ-specific assessments (Heart, Liver, Lung). The system uses **machine learning** (XGBoost, Random Forest, SVM, and deep learning models) in combination with **clinical guidelines** (AHA, WHO, NIH) to generate **predictive health scores** for various organs and an **overall health score**. The scores are complemented by **personalized medical advice** based on individual health categories (Excellent, Good, Poor, Risky).

This project uses **KNHANES (Korean National Health and Nutrition Examination Survey)** dataset but can be adapted to other populations, including Indian patients, by fine-tuning the clinical thresholds and features.

---

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Model Evaluation](#model-evaluation)
- [PDF Report Generation](#pdf-report-generation)
- [Visualizations](#visualizations)
- [Contributions](#contributions)
- [License](#license)

---

## Project Description

This health scoring system aims to predict the **overall health score** and **organ-specific scores** (Heart, Liver, and Lungs) based on key clinical features such as **blood pressure, cholesterol levels, BMI**, and others. The model uses **ensemble techniques** (XGBoost + Deep Learning) for better accuracy and **SHAP (SHapley Additive exPlanations)** for interpretability.

### Key Components:
- **Data Analysis**: Exploratory Data Analysis (EDA), Correlation Matrices, Pairplots, and 3D Scatter Plots
- **Feature Engineering**: Calculating **BMI**, creating **penalty-based health scoring** logic for each organ
- **Machine Learning Models**: **XGBoost**, **Random Forest**, **SVM**, **Gradient Boosting**, and **MLP**
- **PDF Report Generation**: Personalized health reports with recommendations
- **Model Explainability**: SHAP for feature importance and interpretation

---

## Features

- **Organ-specific scoring**: Heart, Liver, Lungs, and Overall Health
- **Personalized Medical Advice** generated using **NLP** based on health score clusters
- **Comprehensive data visualization**: Pairplots, Histograms, and 3D scatter plots for feature analysis
- **Machine Learning Models**: XGBoost, Random Forest, SVM, Gradient Boosting
- **Hybrid Model**: Combination of **XGBoost and Deep Learning (MLP)** for improved accuracy
- **SHAP for interpretability**: Provides transparent decision-making
- **PDF Report Generation**: Each individual’s health score and recommendations in a downloadable PDF format

---

## Installation Instructions

To get started with this project, follow the steps below:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/health-risk-scoring.git
   cd health-risk-scoring
