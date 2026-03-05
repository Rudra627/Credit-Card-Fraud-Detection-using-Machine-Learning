<h1>Credit Card Fraud Detection using Machine Learning</h1>

This project focuses on detecting fraudulent credit card transactions using machine learning techniques and data analysis. The goal is to analyze transaction data, reduce feature complexity, and identify patterns that help distinguish fraudulent activities from normal transactions.

The project begins with data preprocessing and cleaning, where missing values are handled and additional features such as transaction hour are created. Exploratory Data Analysis (EDA) is performed using correlation heatmaps and visualizations to understand relationships between features.

To reduce dimensionality and improve performance, Principal Component Analysis (PCA) is applied to the dataset. Clustering techniques such as K-Means are then used to group similar transaction patterns, and the optimal number of clusters is determined using the Elbow Method.

Finally, a Random Forest Classifier is trained on the processed dataset to classify transaction patterns and analyze potential fraud behavior.

Key Features

Data preprocessing and feature engineering

Exploratory Data Analysis (EDA) with visualizations

Dimensionality reduction using PCA

Clustering using K-Means algorithm

Optimal cluster detection using Elbow Method

Fraud pattern classification using Random Forest

Technologies Used

Python

Pandas & NumPy

Scikit-learn

Matplotlib & Seaborn

K-Means Clustering

PCA (Principal Component Analysis)

Goal

The main objective of this project is to explore machine learning techniques that can help identify suspicious transaction patterns and support fraud detection systems in financial applications.
