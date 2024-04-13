# Vehicle Data Classification Project

## Overview

This project focuses on classifying vehicle data into segments or categories using supervised machine learning techniques such as Decision Trees and Random Forests. The dataset consists of various features such as selling price, kilometers driven, fuel type, seller type, transmission type, and owner status.

## Project Objectives

### Problem Statements

1. **Classification of Vehicle Data into Segments using Cross-Validation**
2. **Classification of Vehicle Data into Segments using Ensemble Methods**
3. **Determination of an Appropriate Classification Model**
4. **Identification of Important Features and their Thresholds for Classification**

## Data Description

### Source and Size

- **Data Source:** [CarDekho](https://www.cardekho.com/used-cars+in+delhi-ncr)
- **Data Size:** 7.71 MB
- **Data Shape:** 84340 rows × 9 columns

### Variables

#### Index Variable(s)
- Car Name

#### Categorical Variables
- **Nominal Categories:** Fuel, Seller Type, Transmission, Owner, Cluster
- **Ordinal Categories:** None

#### Non-Categorical Variables
- Selling Price
- Kilometers Driven

## Data Analysis

### Descriptive Statistics

- Summary statistics for categorical and non-categorical variables
- Correlation analysis

### Data Pre-Processing

- Missing data treatment
- Encoding categorical variables
- Outlier detection and treatment
- Data transformation and scaling
- Train-test split

## Model Building and Evaluation

### Base Model (Decision Tree)

- **Metrics:** Accuracy
- **Results:** Perfect accuracy, efficient training time, moderate memory usage
- **Feature Analysis:** Relevant feature - selling_price_mmnorm

### Comparison Model (Random Forest)

- **Metrics:** Cross-validation accuracy, confusion matrix
- **Results:** High accuracy, longer training time compared to Decision Tree
- **Feature Analysis:** Significant feature - selling_price_mmnorm

## Results and Insights

- **Model Parameters:** Comparison of accuracy and training time between Decision Tree and Random Forest
- **Variable Analysis:** Relevant features identified by the models
- **Managerial Insights:** Real-life applications and implications of the classification models

## GitHub Repository

- The code and documentation for this project can be found in the GitHub repository.

---

You can further elaborate on each section by providing code snippets, visualizations, and additional insights as needed. Let me know if you need any further assistance!
