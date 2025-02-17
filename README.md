# Breast Cancer Prediction Using Deep Neural Networks (DNN)
## Overview
This project applies Deep Learning techniques to classify breast cancer tumors as benign or malignant using the Wisconsin Breast Cancer Diagnostic Dataset from Kaggle. The goal is to assist radiologists by developing an automated detection system based on Fine Needle Aspirate (FNA) sample images.

Our model, built with TensorFlow (Keras), achieved exceptional performance, with an AUC score of 0.9967 and an accuracy of 98.25%.

## Dataset
- Source: Kaggle – Wisconsin Breast Cancer Diagnostic Dataset
- Data Composition:
  - 62.7% Benign tumors
  - 37.3% Malignant tumors
- Features: Extracted from digitized FNA images of breast masses
  
## Workflow
### 1. Data Wrangling & Exploratory Data Analysis (EDA)
- Analyzed the dataset for distribution, class imbalance, and feature importance
- Visualized data patterns and feature correlations
- Handled missing values and standardized input features
- Notebook: Data_wrangling_and_EDA_Breast_Cancer_Prediction_final_version.ipynb
### 2. Deep Neural Network (DNN) Model Development
- Built a DNN classifier using TensorFlow (Keras API)
- Train-Validation-Test Split:
  - 80% Training
  - 10% Validation
  - 10% Testing
- Notebook: Breast_Cancer_Prediction_DNN_TensorFlow2_Capstone_2.ipynb
### 3. Model Performance & Evaluation
- Achieved AUC: 0.9967 (Near perfect classification capability)
- Accuracy: 98.25%
- Performance evaluated using:
  - Confusion Matrix
  - Precision-Recall curves
  - ROC curves
### 4. Final Report & Presentation
- Final Report: Final_Report_Breast_Cancer_Prediction_DNN_Capstone_II.ipynb
- Presentation Slides: Final_Slide_BCA_DNN_Capstone_II_Frew_Berhe_ppt
## Technologies Used
- Python
- TensorFlow (Keras API)
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-Learn

## Future Improvements
- Implement CNNs for image-based feature extraction
- Explore transfer learning with pre-trained models
- Deploy the model as a web-based application for real-time predictions
