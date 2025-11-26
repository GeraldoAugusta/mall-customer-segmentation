# Customer Segmentation – Machine Learning Clustering

## Overview
This project demonstrates customer segmentation using unsupervised learning (clustering).  
The goal is to group customers based on their demographics and spending behavior to provide insights for marketing strategies and business decisions.  

The workflow includes:
- Exploratory Data Analysis (EDA)  
- Preprocessing & Feature Scaling  
- KMeans Clustering  
- 2D and 3D Visualizations  
- Cluster Insight Analysis  

## Dataset
- Source: [Mall Customer Segmentation Dataset – Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Features:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)


## Exploratory Data Analysis (EDA)
- Understand dataset structure and feature distributions  
- Check for missing values  
- Visualize distributions of Age, Income, Spending Score  
- Pairplots to explore feature relationships  
- Correlation heatmap  

## Preprocessing
- Encode categorical features (e.g., Gender → numeric)  
- Select relevant features for clustering  
- Standardize numerical features using StandardScaler  

## Clustering
- Apply KMeans clustering  
- Determine optimal number of clusters using:
  - Elbow Method  
  - Silhouette Score  
- Assign cluster labels to dataset  

## Evaluation & Visualization
- 2D scatter plot of Annual Income vs Spending Score colored by cluster  
- 3D interactive scatter plot of Age, Annual Income, Spending Score  
- Optional: pairplots or other interactive plots  

## Insights
- Identify different customer segments, e.g.:
  - High-income, high-spending  
  - Low-income, low-spending  
  - Young, high-spending, etc.  
- Useful for targeted marketing campaigns and business strategy  

## How to Run
1. Install required libraries:
```bash
pip install -r requirements.txt
