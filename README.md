# Zomato-Machine-Learning-Project
A Machine Learning project on the Zomato Restaurant dataset featuring rating prediction, rating category classification, cuisine classification, and a content-based restaurant recommendation system using Python, Scikit-learn, XGBoost, TF-IDF, and Cosine Similarity.

# 🍽️ Zomato Machine Learning Project

## 📌 Overview

This repository contains four end-to-end Machine Learning projects built using the Zomato Restaurant Dataset. The goal is to analyze restaurant data and solve different real-world business problems using regression, classification, and recommendation techniques.

The project demonstrates the complete machine learning pipeline, including data preprocessing, feature engineering, model building, evaluation, and recommendation systems.

---

# 📂 Project Modules

## 1️⃣ Restaurant Rating Prediction

### Objective
Predict the aggregate rating of a restaurant based on its features.

### Problem Type
Regression

### Algorithms Used
- Random Forest Regressor
- XGBoost Regressor

### Evaluation Metrics
- MAE
- RMSE
- R² Score

### Workflow
- Data Cleaning
- Feature Engineering
- Label Encoding
- Model Training
- Hyperparameter Tuning
- Model Comparison
- Feature Importance
- Residual Analysis

---

## 2️⃣ Restaurant Rating Category Classification

### Objective

Classify restaurants into rating categories such as:

- Excellent
- Very Good
- Good
- Average
- Poor

### Problem Type

Multi-Class Classification

### Algorithms Used

- Random Forest Classifier
- XGBoost Classifier

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score

### Workflow

- Data Cleaning
- Feature Engineering
- Label Encoding
- Model Training
- Hyperparameter Tuning
- Confusion Matrix
- Classification Report

---

## 3️⃣ Cuisine Classification

### Objective

Predict the cuisine served by a restaurant.

### Problem Type

Classification

### Algorithms Used

- TF-IDF Vectorization
- Logistic Regression

### Workflow

- Text Preprocessing
- TF-IDF Vectorization
- Model Training
- Evaluation
- Confusion Matrix

Example Predictions:

- North Indian
- Chinese
- Italian
- Bakery
- Cafe

---

## 4️⃣ Restaurant Recommendation System

### Objective

Recommend similar restaurants based on cuisine similarity.

### Recommendation Technique

Content-Based Filtering

### Technologies

- TF-IDF Vectorizer
- Cosine Similarity

### Workflow

- Data Cleaning
- TF-IDF Feature Extraction
- Similarity Matrix
- Recommendation Function

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- LightGBM
- TF-IDF
- Cosine Similarity

---

# 📊 Machine Learning Workflow

```
Import Libraries
        │
Load Dataset
        │
Exploratory Data Analysis
        │
Data Cleaning
        │
Feature Engineering
        │
Label Encoding
        │
Train-Test Split
        │
Model Training
        │
Hyperparameter Tuning
        │
Model Evaluation
        │
Visualization
        │
Model Saving
```

---

# 📁 Repository Structure

```
Zomato-Machine-Learning-Project
│
├── 01_Restaurant_Rating_Prediction
├── 02_Rating_Category_Classification
├── 03_Cuisine_Classification
├── 04_Restaurant_Recommendation_System
├── Dataset
└── README.md
```

---

# 🚀 Future Improvements

- Deploy all models using Streamlit
- Build a complete Restaurant Analytics Dashboard
- Hybrid Recommendation System
- Deep Learning Models
- Docker Deployment
- Cloud Deployment

---

# 👨‍💻 Author

**Lokesh Hate**

B.Tech Computer Science Engineering

Aspiring Machine Learning Engineer
