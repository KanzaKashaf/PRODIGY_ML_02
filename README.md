# Customer Segmentation Using K-Means Clustering

This project implements a K-Means clustering algorithm to segment retail store customers based on their purchase history. The goal is to group customers into distinct clusters to understand their purchasing behavior and enhance targeted marketing strategies.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Process](#process)
- [Requirements](#requirements)
- [Installation](#installation)

## Project Overview
In this project, we applied K-Means clustering to segment customers of a retail store based on historical purchase data. Identifying different customer segments helps in optimizing marketing efforts, improving customer retention, and tailoring services.

## Dataset
The dataset used for this project includes customer purchase history, covering:
- **Customer ID**
- **Total amount spent**
- **Number of transactions**
- **Product categories purchased**
- **Frequency of purchases**

**Dataset Source:** [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## Process
1. **Loading the Dataset**: The dataset is structured for clustering analysis.
2. **Data Exploration**: Performed exploratory data analysis (EDA) to understand the dataset's structure and patterns.
3. **Data Preprocessing**: Handled missing values, scaled the data, and selected relevant features.
4. **Building the K-Means Model**: Applied the K-Means algorithm to create customer clusters. The Elbow method was used to determine the optimal number of clusters.
5. **Evaluating and Visualizing Clusters**: Assessed cluster cohesion and separation, followed by creating visualizations to illustrate customer segments.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/KanzaKashaf/PRODIGY_ML_02
