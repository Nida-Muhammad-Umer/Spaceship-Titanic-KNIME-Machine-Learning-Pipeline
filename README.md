# Spaceship Titanic – KNIME Machine Learning Pipeline

## Project Overview

This project was developed as part of a Data Science coursework to solve a real-world classification problem from the Kaggle competition **Spaceship Titanic**.

The objective was to predict whether passengers were transported to an alternate dimension following a spacetime anomaly collision.

Using KNIME Analytics Platform, we built a fully visual end-to-end machine learning workflow to clean, preprocess, train, evaluate, and generate predictions for unseen test data.

for Spaceship Titanic Data : https://www.kaggle.com/competitions/spaceship-titanic/overview

---

## Business Problem

Following a collision near Alpha Centauri, records from the Spaceship Titanic needed to be analyzed to determine which passengers were transported to another dimension.

Accurate prediction enables:

- Identification of transported passengers
- Efficient rescue planning
- Data-driven decision support

---

## Workflow Architecture (KNIME)

The pipeline includes:

### Data Import
- CSV Reader (Train & Test datasets)

### Data Exploration
- Data Explorer
- Statistical inspection
- Missing value analysis

### Data Preprocessing
- Column Rename
- String Manipulation (True/False formatting)
- Missing Value Imputation:
  - Most frequent (categorical)
  - Rounded mean (numerical)
- Domain Calculator

### Model Training
- 70/30 Train-Test Split
- Random Forest Classifier (100 trees)

Why Random Forest?
- Ensemble-based (reduces overfitting)
- Strong predictive performance
- Feature importance insights
- Robust on structured datasets

### Model Evaluation
- Confusion Matrix
- Accuracy, Precision, Recall

Results:
- Training Accuracy: **86.3%**
- Test Accuracy: **79.7%**
- Average Tree Depth: 10
- Number of Trees: 100

### Prediction & Submission
- Random Forest Predictor
- Output formatting
- CSV Writer for Kaggle submission

---

## Key Results

The model demonstrated strong generalization performance with controlled overfitting.

The difference between training (86.3%) and testing accuracy (79.7%) indicates acceptable variance and robust predictive capability.

---

## Tools & Technologies

- KNIME Analytics Platform
- Random Forest (Tree Ensemble)
- Data Preprocessing Nodes
- Kaggle Competition Dataset

---

## Download Workflow

You can download and run the full KNIME workflow from repository.

### Requirements:
- KNIME Analytics Platform 4.x
- Tree Ensemble Extension

---

## What This Project Demonstrates

✔ End-to-end ML pipeline design  
✔ Data cleaning & transformation  
✔ Model selection & evaluation  
✔ Overfitting control  
✔ Deployment-ready output generation  

---

## Author

Nida Muhammad Umer  
Data Analyst | Machine Learning Enthusiast  
