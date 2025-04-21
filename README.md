# Clustering of Households Based on Their Possessions

## Overview
This project focuses on the **classification of households** based on the possessions and assets they own, such as **TVs, smartphones, washing machines, computers**, and other consumer goods. The goal is to build a model that can categorize households into different clusters based on their material possessions, using **Clustering** techniques. The dataset used for this project is from a survey of Algerian households, which includes information on income levels and household possessions.

## Objective
The primary goal of this project is to:
- **Classify Algerian households** based on their **possessions** (e.g., electronics, internet access, vehicles).
- Use clustering techniques to group households with similar possession patterns, which can help in understanding **socioeconomic trends**.
- Perform **data cleaning** and **feature engineering** to prepare the data for clustering.

## Approach

1. **Data Collection**:
   The dataset is based on a survey of over **28,000 Algerian households**. The survey collected data on:
   - Household **income levels**.
   - Possessions such as **TVs, computers, smartphones**, **vehicles**, and **internet connections**.

2. **Data Preprocessing**:
   - **Cleaning**: Missing values in the dataset are imputed using **Decision Trees** for categorical data to ensure that no important data is lost.
   - **Feature Engineering**: Various columns representing household possessions are transformed into a **scoring system** to simplify the analysis and reduce dimensionality.
     - **Entertainment Score**: Calculated based on the number and type of entertainment-related devices owned.
     - **Electronics Score**: Based on household appliances owned.
     - **Telecom Score**: Based on the type of internet connection (e.g., ADSL, 3G, 4G).
   
3. **Clustering**:
   - The dataset is clustered using **K-means clustering** to group households into categories based on their possessions and income.
   - **Elbow method** is used to determine the optimal number of clusters for the data.

4. **Exploratory Data Analysis (EDA)**:
   - **Univariate analysis**: Visualizing the frequency distribution of different possessions and household income.
   - **Multivariate analysis**: Understanding how different possessions correlate with household income and clustering results.

5. **Visualization**:
   - Several **visualizations** such as **bar charts** and **heatmaps** are used to display the clustering results and distribution of features.

## Dataset Description
The dataset consists of 28,000+ observations and 31 columns (features). Some of the key columns in the dataset are:
- **Revenu_global_du_ménage**: Household income.
- **Possession of goods**: Multiple columns indicating whether a household owns certain goods, such as TVs, washing machines, computers, vehicles, smartphones, etc.
- **WILAYA**: The region where the household is located.
- **SEXE**: The gender of the head of the household.
- **AGE1**: The age of the head of the household.

### Key Columns:
- **Q7A4C1 to Q7A4C20**: Columns indicating possession of various household items like **TVs, washing machines**, **laptops**, **smartphones**, and **vehicles**.
- **Revenu_global_du_ménage**: The overall income of the household.

## Files in the Repository
- **PROTECH_PRESENTATION.mp4**: A presentation video outlining the project.
- **Python Code.ipynb**: Jupyter notebook containing the Python code for the analysis, including data preprocessing, feature engineering, and clustering.
- **R code_html.html**: An HTML file containing the R code used for decision tree imputation and feature engineering.
- **statistical_report.pdf**: The full statistical report of the clustering project, including analysis, methodology, and results.

## How to Run the Project

### 1. Clone the Repository:
```bash
git clone https://github.com/your-username/Household-Clustering.git
cd Household-Clustering
```

### 2. Install Dependencies:
Install required Python libraries:
```bash
pip install -r requirements.txt
```

### 3. Run the Python Notebook:
Open the **Python Code.ipynb** in Jupyter Notebook and run the cells to perform data preprocessing, feature engineering, and clustering.

### 4. Check the Report:
Review the **statistical_report.pdf** for a detailed explanation of the clustering methodology and the final results.

## Conclusion
This project provides insights into the clustering of Algerian households based on their material possessions. By analyzing the possession patterns, the project helps in understanding household dynamics and socioeconomic classifications, which can be valuable for market research and policymaking.


