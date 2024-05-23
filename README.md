# Census Income Data Analysis and Prediction

## Project Overview

This project involves analyzing the Census Income dataset from the UCI Machine Learning Repository, which contains income information for over 48,000 individuals from the 1994 US census. The primary objective is to preprocess the data, perform exploratory data analysis (EDA), and develop predictive models to classify whether an individual earns over $50,000 a year or less.

For more details about this dataset, you can refer to the following [link](https://archive.ics.uci.edu/ml/datasets/census+income).

## Problem Statement

The goal of this project is to:
1. Preprocess the data and understand its features through EDA and visualizations.
2. Perform a classification task to predict whether an individual makes over $50,000 a year using various machine learning algorithms.

## Tasks To Be Performed

1. **Exploratory Data Analysis (EDA):**
   - Clean and preprocess the dataset.
   - Analyze the distribution of features.
   - Identify key patterns and insights through visualizations.

2. **Predictive Modeling:**
   - Train and evaluate different machine learning models.
   - Compare model performance and select the best model for prediction.

## Project Structure

- `Census Income Project.ipynb`: Jupyter Notebook containing the complete analysis, including data preprocessing, EDA, and machine learning models.
- `data/census-income (7).csv`: Folder containing the dataset used for analysis.
- `README.md`: Project overview and documentation (this file).
  
## Data

The dataset includes various features related to individual demographics and employment, such as:
- Age
- Workclass
- Education
- Marital status
- Occupation
- Relationship
- Race
- Sex
- Hours per week
- Native country
- Income (target variable)

## Methodology

1. **Data Preprocessing:**
   - Handling missing values.
   - Encoding categorical variables.
   - Normalizing numerical features.

2. **Exploratory Data Analysis (EDA):**
   - Univariate and bivariate analysis.
   - Visualization of distributions and relationships.
   - Identification of significant features.

3. **Machine Learning:**
   - Model selection and training (e.g., logistic regression, decision trees, random forests, SVM).
   - Model evaluation using metrics such as accuracy, precision, recall, and F1-score.
   - Hyperparameter tuning and cross-validation.

## Results

- Summary of key findings from EDA.
- Performance metrics of various machine learning models.
- Final model selection and insights derived from the predictions.

## Usage

To run the analysis, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/HrHarsh59/census-income-analysis.git
   cd census-income-analysis
