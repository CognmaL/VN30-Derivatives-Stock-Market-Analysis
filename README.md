# VN30-Derivatives-Stock-Market-Analysis
This is a midterm team project in Introduction to Data Sciences from HCMUS.

## Overview
In this project, we will start by obtaining the data file in pickle format from the client. Depending on the data processing requirements, we will use essential libraries and modules such as pickle, numpy, pandas, and matplotlib. Our goal is to perform a comprehensive analysis of the stock market for a one-month period involving 30 companies listed in VN30.

## Data Preprocessing
### 1. Obtaining and Loading Data
We begin by obtaining the data file in pickle format from the client. The necessary libraries for data processing include pickle, numpy, pandas, and matplotlib.

### 2. Data Cleaning and Transformation
Real-world data is often incomplete, inconsistent, and inaccurate. The data preprocessing step involves cleaning, formatting, and organizing raw data to make it suitable for analysis. Before diving into the data processing steps, it's crucial to have a basic understanding of stock markets, laying the foundation for analysis and meeting client requirements.

#### (1) Cleaning:
Clean the data to address issues such as missing values and outliers.
#### (2) Transforming:
Utilize foundational stock market knowledge and features in the dataset to create a new, more meaningful dataset for analysis.
### 3. Data Scaling
Data scaling is a crucial step in machine learning, involving the transformation of feature values to a specific range (e.g., 0 to 1 or -1 to 1). This ensures that no single feature dominates distance calculations in algorithms, improving algorithm performance. Scaling methods include standardization and normalization.

#### PCA (Principal Component Analysis)
Principal Component Analysis is applied to reduce dataset dimensionality while retaining essential features, simplifying the analysis process and enhancing computational efficiency. The cumulative sum of explained variance helps determine the percentage of variance retained by the selected components.

#### K-Means Clustering
K-Means clustering is employed to group stocks with similar characteristics, revealing patterns and relationships within the dataset. This aids in understanding market dynamics.

### Data Analysis
Perform in-depth analysis on clustered data to derive meaningful insights, exploring correlations, trends, and anomalies. The analysis provides a basis for informed decision-making in trading or investment strategies.

## Conclusion
Through this Stock Analysis project, our Data Science team aims to deliver valuable insights to our client, supporting them in making informed decisions in the dynamic stock trading environment. The combination of data preprocessing, PCA, K-Means clustering, and thorough data analysis contributes to a comprehensive understanding of the VN30 stock market for the specified one-month period.
