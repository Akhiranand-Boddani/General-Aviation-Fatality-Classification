# Aviation Accident Fatality Classification

This repository contains code and sample data for classifying general aviation accidents as fatal or non-fatal using machine learning and deep learning models. The project demonstrates the use of multiple supervised learning algorithms and emphasizes the challenges of class imbalance in safety-critical prediction systems.

## Project Overview

- **Objective**: Predict whether a general aviation accident results in fatalities based on aircraft configuration, operational factors, and weather conditions.
- **Data**: 38,753 historical accident records (sample dataset included).
- **Models Implemented**:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Support Vector Machines (Linear and RBF)
  - Gradient Boosting
  - XGBoost
  - Multi-Layer Perceptron
  - 1D Convolutional Neural Network
  - TabNet
  - Stacking Classifier
- **Evaluation Metrics**:
  - Accuracy
  - ROC AUC
  - Precision
  - Recall
  - F1-Score (Fatal Class emphasized)

## Folder Structure

general-aviation-fatality-classification/
│
├── 1_Final EDA.ipynb # Exploratory Data Analysis
├── 2_Model 60-40.ipynb # Model training on 60 - 40 Train Test Split
├── 3_Model 70-30.ipynb # Model training on 70 - 30 Train Test Split
├── 4_Model 80-20.ipynb # Model training on 80 - 20 Train Test Split
├── 3_Predictions.ipynb # Sample predictions
├── sample_ADC_fil.csv # Example subset of dataset
├── README.md
├── requirements.txt
└── .gitignore


## How to Run

1. Install dependencies:

2. Launch Jupyter Notebook:

3. Open and execute the notebooks in sequence.

## Citation

This project was presented at the National Conference organized by the Indian Statistical Institute, Hyderabad, on the occasion of National Statistics Day.

## License

This repository is for educational and research purposes only. Please contact the author for any reuse or adaptation.
