# Customer Segmentation and Product Recommendation System

## Project Overview

This project focuses on analyzing customer purchasing behavior and providing personalized product recommendations using Machine Learning techniques. The goal is to help businesses understand their customers better, improve marketing strategies, and increase sales through targeted recommendations.

## Objectives

* Perform customer segmentation using RFM (Recency, Frequency, Monetary) analysis.
* Group customers into meaningful segments using K-Means Clustering.
* Build a Product Recommendation System using Item-Based Collaborative Filtering and Cosine Similarity.
* Deploy the solution using Streamlit for real-time predictions and recommendations.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Streamlit

## Project Workflow

### 1. Data Collection

* Online Retail Dataset

### 2. Data Cleaning

* Removed missing values
* Removed cancelled transactions
* Removed invalid quantity and price values
* Converted date columns into proper datetime format

### 3. Exploratory Data Analysis (EDA)

* Customer purchase behavior analysis
* Sales trend analysis
* Top-selling products
* Country-wise transaction analysis
* Revenue distribution analysis

### 4. Customer Segmentation

* Created RFM features:

  * Recency
  * Frequency
  * Monetary
* Applied StandardScaler for feature scaling
* Used Elbow Method to determine optimal K value
* Applied K-Means Clustering (K = 4)

### Customer Segments

* High Value Customers
* Regular Customers
* Occasional Customers
* At Risk Customers

### 5. Product Recommendation System

* Created Customer-Product Matrix
* Applied Item-Based Collaborative Filtering
* Used Cosine Similarity to calculate product similarity
* Generated Top 5 Product Recommendations

### 6. Streamlit Deployment

Developed an interactive Streamlit web application that:

* Predicts customer segments based on RFM values
* Recommends similar products based on purchase patterns
* Provides a simple and user-friendly interface

## Files Included

* Customer Segmentation and Product Recommendations_project.ipynb
* app.py
* customer_segmentation.pkl
* product_similarity.pkl
* scaler.pkl
* requirements.txt

## Business Benefits

* Better customer understanding
* Personalized marketing campaigns
* Improved customer retention
* Increased cross-selling opportunities
* Enhanced customer experience

## Author

Gauri Shukla
B.Tech (Computer Science & Engineering)
Aspiring AI & Machine Learning Engineer
