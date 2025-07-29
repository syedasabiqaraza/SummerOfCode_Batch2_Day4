# SummerOfCode_Batch2_Day4

Wine Quality Prediction with Machine Learning

Overview

This project applies machine learning to predict wine quality using the WineQT dataset. It implements Decision Tree and Random Forest classifiers, with preprocessing, hyperparameter tuning, and performance evaluation using accuracy and confusion matrices. The code is optimized for Jupyter/Colab environments.

Dataset

Source: WineQT.csv (included in the repository)

Features: 11 chemical properties (e.g., fixed acidity, pH, alcohol)

Target: Wine quality (integer scores)

Preprocessing: Handles missing values, drops irrelevant 'Id' column, and splits data into training/testing sets.

Models

Decision Tree: Tuned for max_depth and min_samples_split.

Random Forest: Tuned for n_estimators, max_depth, and min_samples_split.

Evaluation: Accuracy, confusion matrices, and classification reports for initial and tuned models.

Requirements
Python 3.x
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Results
Outputs include initial and tuned model accuracies, confusion matrices, and classification reports.

Visualizations show model performance via heatmaps.

License
MIT License

