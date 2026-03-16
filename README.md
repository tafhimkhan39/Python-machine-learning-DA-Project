# Marketing Campaign Analysis & Customer Segmentation

## Introduction

This project analyzes a marketing campaign dataset to better understand customer behavior and identify distinct customer segments. Using Python and machine learning techniques, the analysis explores customer demographics, purchasing behavior, and responses to past marketing campaigns.

The main objective of the project is to uncover patterns in customer spending and group customers into meaningful clusters that can help businesses design more effective marketing strategies.

---

## Project Overview

Companies often collect large amounts of customer data but struggle to extract actionable insights from it. In this project, exploratory data analysis, feature engineering, and clustering techniques were used to analyze customer characteristics and purchasing behavior.

The project follows a typical data science workflow:

1. Data Loading and Inspection
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis
5. Dimensionality Reduction (PCA)
6. Customer Segmentation using Clustering
7. Visualization and Interpretation of Results

---

## Dataset

The dataset contains information about customers and their interaction with marketing campaigns. It includes demographic information, purchasing behavior, and responses to previous campaigns.

Key types of features in the dataset include:

* **Customer demographics**

  * Age
  * Education
  * Marital status
  * Household composition

* **Financial information**

  * Income
  * Spending on different product categories

* **Purchasing behavior**

  * Number of deals purchased
  * Number of web purchases
  * Catalog purchases
  * Store purchases

* **Marketing campaign responses**

  * Acceptance of past campaigns
  * Customer complaints
  * Promotion responses

---

## Tools & Technologies Used

* **Python**
* **Pandas** – data manipulation and analysis
* **NumPy** – numerical operations
* **Matplotlib & Seaborn** – data visualization
* **Scikit-learn** – machine learning algorithms
* **Principal Component Analysis (PCA)** – dimensionality reduction
* **Agglomerative Clustering** – customer segmentation

---

## Data Cleaning & Preprocessing

Several preprocessing steps were performed to prepare the data for analysis:

* Removed rows containing missing values
* Converted date columns into proper datetime format
* Removed extreme outliers in **Age** and **Income**
* Encoded categorical variables using **Label Encoding**
* Standardized features for machine learning models

These steps ensured the dataset was clean and suitable for modeling.

---

## Feature Engineering

Additional features were created to improve the analysis and capture meaningful patterns in the data.

Examples include:

* **Customer_For** – number of days since the customer joined
* **Age** – calculated from birth year
* **Spent** – total spending across all product categories
* **Total_Promos** – total number of accepted marketing campaigns

Feature engineering helped reveal deeper insights into customer behavior.

---

## Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand relationships between variables and detect patterns in the data.

Key analyses included:

* Distribution of customer demographics
* Spending patterns across product categories
* Relationship between income and total spending
* Analysis of promotion acceptance
* Customer purchasing behavior across channels

Visualizations were created using **Seaborn** and **Matplotlib** to better understand the dataset.

---

## Dimensionality Reduction

To simplify the dataset and prepare it for clustering, **Principal Component Analysis (PCA)** was applied.

PCA reduced the high-dimensional dataset to **three principal components**, allowing the data to be visualized in a 3D space while retaining most of the original variance.

This step helped improve clustering performance and visualization.

---

## Customer Segmentation (Clustering)

Customer segmentation was performed using **Agglomerative Clustering**, a hierarchical clustering algorithm.

The **Elbow Method** was used to determine the optimal number of clusters. The analysis identified **four distinct customer segments** based on purchasing behavior and demographic characteristics.

Each cluster represents a different type of customer group.

Examples of potential segments include:

* High-income high-spending customers
* Moderate spenders
* Deal-driven customers
* Low-engagement customers

---

## Key Insights

The clustering analysis revealed several useful patterns:

* Customer **income strongly influences spending behavior**
* Certain customer groups respond more positively to marketing campaigns
* Some clusters purchase more frequently through promotional deals
* High-spending customers can be targeted for premium marketing campaigns

These insights can help businesses create **targeted marketing strategies** for different customer groups.

---

## Project Structure

```
marketing-campaign-analysis
│
├── dataset
│   └── marketing_campaign.csv    # Dataset used for analysis
├── README.md                     # Project documentation
├── marketing_campaign.ipynb      # Main analysis notebook

```

---

## What I Learned

Through this project I gained experience in:

* Data cleaning and preprocessing
* Feature engineering
* Exploratory data analysis
* Dimensionality reduction with PCA
* Customer segmentation using clustering
* Data visualization and interpretation

This project demonstrates how machine learning techniques can be applied to marketing data to generate meaningful business insights.

---

## Future Improvements

Potential improvements for this project include:

* Testing additional clustering algorithms (K-Means, DBSCAN)
* Building predictive models for campaign response
* Creating interactive dashboards using Power BI or Tableau
* Deploying the analysis as a data app

---

## Credit

This project was completed as part of a data analytics portfolio to demonstrate skills in **Python, data analysis, and machine learning**.

Credits to the original creator for making the project and walking through it https://www.youtube.com/watch?v=k_7Ise59GQY


