# Machine-Learning-Assignment-4-Classification
This repository contains the implementation of classification algorithms applied to the breast cancer dataset, as part of an assignment in Jupyter Notebook. The goal is to evaluate various classification models and compare their performances based on different evaluation metrics

Data Loading and Preprocessing:

The dataset is imported and preprocessed to handle missing values, scale features, and encode categorical data where necessary.
Model Selection:

Various classification algorithms are implemented:
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
k-Nearest Neighbors (k-NN)
Performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are used for model evaluation.
Insights and Analysis:

The best and worst-performing algorithms are identified based on the evaluation metrics.
Overview of Results:
The performance of each algorithm is assessed based on several key metrics. The accuracies achieved by the models are as follows:

Logistic Regression: 97.37%
Decision Tree: 94.74%
Random Forest: 96.49%
SVM: 95.61%
k-NN: 94.74%
Best-Performing Algorithm:
The Logistic Regression model achieved the highest accuracy at 97.37%, making it the best-performing algorithm. Its classification report shows high precision, recall, and F1-scores for both classes, indicating its robustness for this dataset. Logistic regression is particularly effective for linearly separable data and performs well when the dataset features clear decision boundaries.

Worst-Performing Algorithm:
The Decision Tree and k-Nearest Neighbors (k-NN) models tied for the lowest accuracy at 94.74%. Both models performed competitively in terms of precision, recall, and F1-score, but their slightly lower accuracy indicates they may not generalize as well as the other models. Decision Trees are prone to overfitting, while k-NN performance depends on the choice of k and the distribution of the data. Further tuning could improve their performance.

