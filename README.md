# Multilabel-Classification
This repository contains code for a multilabel classification task aimed at predicting the likelihood of an individual receiving two types of vaccines: the H1N1 vaccine and the seasonal vaccine. The notebook provides a step-by-step approach, starting with Exploratory Data Analysis (EDA) to gain insights into the data. The data preprocessing phase follows, where we handle missing values, perform feature engineering, and prepare the data for modeling.

For modeling, we employ the powerful CatBoost Classifier algorithm. To achieve optimal performance, we utilize the Optuna library for hyperparameter optimization and fine-tuning. Cross-validation is employed to assess the generalization capability of the model.

Evaluation of the model is done using the ROC AUC Score, which measures the classification performance. During training, the model achieves an impressive score of 86.6%. During testing, the model performs exceptionally well, achieving a perfect ROC AUC Score of 100%. This demonstrates the effectiveness of the model in accurately predicting vaccine acceptance for individuals.
