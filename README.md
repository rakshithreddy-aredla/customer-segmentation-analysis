# Customer Segmentation Analysis

## Overview
This project performs customer segmentation using unsupervised learning (K-means clustering) to group customers by purchasing behavior.

## Dataset
- File: data/customers.csv
- Rows: ~150
- Features: age, annual income, spending score, num_purchases, avg purchase value, loyalty years, membership type

## Analysis
- EDA and data preprocessing
- Feature scaling
- Elbow method for optimal k
- K-means clustering
- Segment profiling

## Technologies
- Python
- pandas, numpy, scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

## Getting Started
`ash
pip install -r requirements.txt
jupyter notebook notebooks/customer_segmentation_analysis.ipynb
`

## Key Findings
- Distinct customer segments identified
- Income vs spending score reveals meaningful groups
- Segments support targeted marketing

## Future Work
- Try hierarchical clustering
- PCA for visualization
- Validate with silhouette score
