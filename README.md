# Advanced Statistics and Machine Learning with Education Data

## Overview

This repository contains notebooks that explore statistical techniques and machine learning methods applied to two different datasets related to education and salary. It's divided into two main sections:

1. **Salary Distribution Analysis:** Investigates the relationship between salary, educational qualifications, and occupation.
2. **Principal Component Analysis (PCA) on Education Data:** Applies PCA to an education dataset to reduce dimensionality and extract key features.

## Datasets

### 1. Salary Distribution Analysis

* **Dataset:** `SalaryData.csv`
* **Variables:**
    * `Salary`: Annual salary of an individual.
    * `Education`: Educational qualification (High School, Bachelor, Doctorate).
    * `Occupation`: Job category (Administrative, Sales, Professional, Executive).

### 2. Principal Component Analysis (PCA) on Education Data

* **Dataset:** `Education_Post_12th_Standard.csv`
* **Variables:** (Refer to the data dictionary for a detailed description of all variables)
    * `Names`: Names of universities/colleges.
    * `Apps`: Number of applications received.
    * `Accept`: Number of applications accepted.
    * `Enroll`: Number of new students enrolled.
    * ... (other relevant variables related to university characteristics)

## Analysis

### 1. Salary Distribution Analysis

* **Exploratory Data Analysis:** Visualizations (count plots, box plots, violin plots) and descriptive statistics to understand the distributions of salary, education, and occupation.
* **One-way ANOVA:** Tests for significant differences in salary based on education and occupation individually.
* **Interaction Plot:** Visualizes the interaction effect between education and occupation on salary.
* **Two-way ANOVA:** Analyzes the main and interaction effects of education and occupation on salary.

### 2. Principal Component Analysis (PCA) on Education Data

* **Data Preprocessing:** Handling missing values, scaling variables (using z-score), and checking correlations.
* **PCA Implementation:** Applying PCA to reduce dimensionality and extract principal components.
* **Scree Plot:** Visualizing the explained variance ratio of each principal component.
* **Loadings Interpretation:** Examining the loadings of original variables on principal components to understand feature importance.
* **Dimensionality Reduction:** Selecting a subset of principal components based on explained variance.


## Findings

### 1. Salary Distribution Analysis

* Higher levels of education are generally associated with higher salaries.
* Occupation has a significant impact on salary, with executive and managerial roles commanding the highest salaries.
* There is an interaction effect between education and occupation, suggesting that the relationship between education and salary might vary depending on the occupation.

### 2. Principal Component Analysis (PCA) on Education Data

* PCA identified key factors/dimensions that explain the variability in the education dataset.
* The scree plot and cumulative explained variance helped determine the optimal number of principal components to retain.
* The loadings of original variables on the principal components provide insights into the underlying structure of the data.

## Business Implications

The insights from these analyses can be used for:

* **Compensation planning:**  Setting competitive salaries based on education and occupation.
* **Talent acquisition:**  Targeting individuals with desired qualifications and skills.
* **Career development:**  Guiding employees towards higher education and career growth.
* **University Ranking/Benchmarking:** Using PCA to understand university characteristics and potentially create rankings.
* **Data-driven Decision Making in Education:** Using insights from PCA to inform policy and resource allocation decisions.


## How to Use

1. Clone this repository: `git clone <repository_url>`
2. Open the notebook in Google Colab or locally.
3. Run the cells in the notebook to reproduce the analyses and visualizations.

## Dependencies

* Python 3.x
* pandas
* numpy
* seaborn
* matplotlib
* statsmodels
* factor_analyzer
* scikit-learn (for PCA)

## Author
Aravindan Natarajan

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
