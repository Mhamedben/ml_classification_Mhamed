# Midterm: Classification Analysis: Heart Disease Prediction**Author:** Mhamed  
**Date:** 04, 05, 2025 


## Project Files:
* [Dataset: Heart_Disease.csv] (https://github.com/Mhamedben/ml_classification_Mhamed/blob/main/Data/Heart_Disease.csv)

* [Jupyter Notebook: Mid_Heart_Disease_Mhamed.ipynb] (https://github.com/Mhamedben/ml_classification_Mhamed/blob/main/Mid_Heart_Disease_Mhamed.ipynb)

* [Peer Review: peer_review.md] (https://github.com/Mhamedben/ml_classification_Mhamed/blob/main/peer_review.md)

## Instructions on how to set up your virtual environment and run your notebook locally:

To run this notebook on your own computer: 
1. Clone the Repository:

git clone https://github.com/Mhamedben/ml_classification_Mhamed/blob/main/Mid_Heart_Disease_Mhamed.ipynb
cd C:\Projects\ml_classification_Mhamed

2. Create a Virtual Environment:
python -m venv .venv

3. Activate the Virtual Environment:
For windows: .\.venv\Scripts\activate
On macOS/Linux: .venv/bin/activate
 
## Introduction
The objective of this classification analysis was to apply classification modeling techniques to predict heart disease risk using a dataset with various patient features, including age, sex, blood pressure, cholesterol levels, and more. The aim was to develop a machine learning model capable of accurately classifying whether a patient is likely to have heart disease based on these features. 

Ultimately, the goal was to create a model that could assist in predicting heart disease risk, while showcasing the practical use of classification algorithms in a real-world healthcare scenario.

## Section 1. Import and Inspect the Data
   - Load the dataset and display the first 10 rows.
   - Check for missing values and display summary statistics
   - Reflection 1: What do you notice about the dataset? Are there any data issues?

## Section 2. Data Exploration and Preparation
   - Explore data patterns and distributions
   - Create histograms, boxplots, and count plots for categorical variables
   - Handle missing values and clean data
   - Feature selection and engineering
   - Reflection 2: What patterns or anomalies do you see? Do any features stand out? What preprocessing steps were necessary to clean and improve the data? Did you create or modify any features to improve performance?
   
## Section 3. Feature Selection and Justification
   - Choose Features and Target
   - Define X and y
   - Reflection 3: Why did you choose these features? How might they impact predictions or accuracy?

## Section 4. Train a Model (Classification: Choose 1: Decision Tree, Random Forest, Logistic Regression)
   - Split the data into training and test sets using train_test_split
   - Train model using Scikit-Learn model.fit() method.
   - Evaluate and Compare Performance
   - Reflection 4: How well did the model perform? Any surprises in the results?

## Section 5. Improve the Model or Try Alternates (Implement a Second Option)
   - Train an alternative classifier (Decision Tree, Random Forest, Logistic Regression)
   - Compare performance of all models across the same performance metrics.
         - A. Logistic Regression.
         - B. Random Forest
         - C. Decision Tree
         - D. Summary 
         - Model Performance Comparison
   - Reflection 5: Which model performed better? Why might one classifier be more effective in this specific case?

## Section 6. Final Thoughts & Insights
   - Summarize Findings
   - Discuss Challenges