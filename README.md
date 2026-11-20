# E-Commerce Customer Segmentation & Recommendation Analysis

## Project Overview

This project focuses on analyzing customer purchasing behavior using Unsupervised Machine Learning techniques.

The project uses the UCI Online Retail dataset to identify meaningful customer segments and build a basic product recommendation system.

## Objectives

- Analyze e-commerce transaction data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Calculate Recency, Frequency and Monetary (RFM) features.
- Apply feature scaling.
- Implement K-Means clustering.
- Analyze customer segments.
- Build a product recommendation system using Cosine Similarity.
- Generate business recommendations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- K-Means Clustering
- Cosine Similarity
- Jupyter Notebook

## Dataset

**UCI Online Retail Dataset**

Source: https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains retail transaction information, including invoice numbers, product details, quantities, invoice dates, prices, customer IDs and countries.

## Project Workflow

1. Dataset collection and loading.
2. Data exploration.
3. Data cleaning and preprocessing.
4. Exploratory Data Analysis.
5. RFM feature engineering.
6. Feature scaling.
7. Optimal cluster analysis.
8. K-Means customer segmentation.
9. Customer cluster visualization.
10. Product recommendation using Cosine Similarity.
11. Business recommendations.
12. Model evaluation.

## Customer Segmentation

The project initially uses four customer segments:

- Champions
- Regular Customers
- Occasional Buyers
- At-Risk Customers

The final segment labels are interpreted using the actual customer cluster profiles.

## Recommendation System

Cosine Similarity is used to calculate product similarities based on customer purchasing patterns.

The system recommends products that are similar to products previously purchased by a customer.

## Evaluation

The project uses:

- Elbow Method
- Silhouette Score
- Cluster distribution
- Customer segment profiles

## Project Structure

- dataset/: Original dataset.
- outputs/: Generated CSV files.
- charts/: Visualization images.
- models/: Saved machine learning model.
- screenshots/: Project execution screenshots.

## How to Run

1. Clone or download the repository.
2. Install the required libraries:

   `pip install -r requirements.txt`

3. Open the Jupyter Notebook.
4. Run all cells sequentially.

## Expected Outcomes

- Cleaned transaction dataset.
- Customer-level feature table.
- RFM analysis.
- Customer segments.
- Product recommendations.
- Business recommendations.
- Visualizations and evaluation results.

## Conclusion

This project demonstrates how Unsupervised Machine Learning can be used to understand customer purchasing patterns, identify customer segments and provide product recommendations for e-commerce businesses.
