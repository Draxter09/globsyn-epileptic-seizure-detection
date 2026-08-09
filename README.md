# EEG-Based Epileptic Seizure Detection

Machine learning-based classification of EEG signals for epileptic seizure recognition using feature selection and multiple classification algorithms.

## Project Overview

- Dataset containing 11,500 EEG records with 178 signal features across five classes.
- Performed exploratory data analysis and feature correlation analysis.
- Applied an 80/20 train-test split for model evaluation.
- Used Random Forest-based Recursive Feature Elimination (RFE) to select the 20 most relevant features.
- Benchmarked multiple machine learning classifiers including Logistic Regression, KNN, Naive Bayes, SVM, Decision Tree, Random Forest, Extra Trees, and ANN.
- Evaluated models using accuracy, confusion matrices, and classification reports.
- Reviewed existing research approaches for EEG-based seizure detection to compare feature extraction and classification strategies.

## Technologies

Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, TensorFlow/Keras

## Notebook

- `EEG_Seizure_Classification.ipynb` — EEG data analysis, feature selection, model training, and evaluation.
