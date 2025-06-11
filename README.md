# 🌿 Project Overview
This project applies core data science, analytics, and machine learning techniques to solve a real-world agricultural problem — predicting the health status of plants based on sensor data. It demonstrates the full data science workflow, from data exploration and visualization to predictive modeling and evaluation.

## 🏢 Business Problem
Modern agriculture increasingly relies on precision farming, where timely insights into crop health can significantly impact yield, resource efficiency, and operational costs. However, manually monitoring large-scale farms is time-consuming and error-prone.

## Business Challenge:
How can we leverage sensor data to automatically detect plant stress or poor health conditions before they escalate, allowing farmers to take preventive or corrective actions?

## 💡 Data Science Solution
By analyzing environmental sensor data and building predictive models, we can classify plants into health categories (e.g., healthy, moderate, stressed). This enables:

Early detection of plant stress

Optimized resource allocation (e.g., water, nutrients)

Reduced manual inspection costs

Improved crop yield and quality

This notebook demonstrates how data-driven approaches can provide scalable, automated solutions to agricultural monitoring.

# 🔍 Key Skills Demonstrated
## 📊 Data Analytics & EDA
Inspected dataset with .info() and .isna() to assess quality

Identified key features like Soil_Moisture using correlation analysis

Compared plant health categories using grouped statistics and visualizations

## 📈 Data Visualization
Count plots for class distribution

Correlation heatmap for feature relationships

Bar plots to communicate feature variation across health statuses

## 🤖 Machine Learning Workflow
Label Encoding for model readiness

SMOTE for handling class imbalance

Model Training: KNeighborsClassifier, RandomForestClassifier

Evaluation: accuracy_score, confusion_matrix, classification_report

## This project demonstrates:

Analytical thinking with business impact

End-to-end pipeline from raw data to model deployment

Capability to turn real-world problems into data-driven solutions

Experience handling imbalanced datasets, interpreting results, and communicating insights

## ⚙️ Tools & Libraries
Python, Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn, imbalanced-learn (SMOTE)

Jupyter Notebook, kagglehub

## ✅ Outcomes
Identified soil moisture as a key predictor of plant stress

Built predictive models that classify plant health with interpretable metrics

Showcased the value of ML in agricultural monitoring and automation
