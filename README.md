# Statistical Learning Course Repository

This repository contains coursework and projects for a Statistical Learning course, including homework assignments and a comprehensive final project on customer prediction using machine learning techniques.

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Homework Assignments](#homework-assignments)
- [Final Project](#final-project)
- [Setup and Requirements](#setup-and-requirements)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Overview

This repository demonstrates practical applications of statistical learning methods through:
- **5 Homework Assignments**: Covering fundamental statistical learning concepts and techniques using R
- **Final Project**: Advanced analysis using Python, focusing on customer prediction with boosting methods

## Repository Structure

```
statistical_learning/
├── README.md                 # This file
├── homework/                 # R-based homework assignments
│   ├── hw1.Rmd              # Introduction to Statistical Learning
│   ├── hw2.Rmd              # Linear Regression
│   ├── hw3.Rmd              # Classification Methods
│   ├── hw4.Rmd              # Resampling Methods
│   └── hw5.Rmd              # Tree-Based Methods
└── final_project/           # Python-based final project
    ├── EDA_1.ipynb          # Initial Exploratory Data Analysis
    ├── EDA_2.ipynb          # Advanced EDA
    ├── EDA_timeseries.ipynb # Time Series Analysis
    ├── SL_Final_code.ipynb  # Main implementation
    └── report.pdf           # Final project report
```

## Homework Assignments

The homework assignments (`hw1.Rmd` through `hw5.Rmd`) cover core statistical learning topics:

1. **HW1**: Introduction to Statistical Learning - Basic data manipulation and analysis
2. **HW2**: Linear Regression - Model fitting and evaluation
3. **HW3**: Classification Methods - Logistic regression and discriminant analysis
4. **HW4**: Resampling Methods - Cross-validation and bootstrap techniques
5. **HW5**: Tree-Based Methods - Decision trees and ensemble methods

Each assignment is implemented in R Markdown format and can be rendered to PDF or Word documents.

## Final Project

### Predicting Potential Customers using Boosting Methods with Bag-of-values Encoding

Precision marketing has become a critical focus in recent years as companies aim to allocate resources effectively to target customers. This project references the study "Generalize for Future: Slow and Fast Trajectory Learning for CTR Prediction" and explores methods for improving customer prediction.

#### Key Features:
- **Dataset**: Customer dataset from Huawei (historical data)
- **Methods**: XGBoost and CatBoost with bag-of-values encoding
- **Innovation**: Alternative to embedding-based encoding for categorical variables
- **Advantages**: 
  - Enhanced training efficiency through reduced computational complexity
  - Improved model interpretability
  - Explicit capture of statistical relationships between features and target

#### Project Components:
- **EDA_1.ipynb**: Initial data exploration and preprocessing
- **EDA_2.ipynb**: Advanced exploratory analysis
- **EDA_timeseries.ipynb**: Temporal pattern analysis
- **SL_Final_code.ipynb**: Main implementation with boosting algorithms
- **report.pdf**: Comprehensive project documentation

