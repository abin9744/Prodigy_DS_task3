# Prodigy_DS_task3
Bank Marketing Prediction Model
Project Overview
This project focuses on building and evaluating a decision tree classifier to predict whether a customer will subscribe to a term deposit based on demographic and behavioral data. Utilizing the Bank Marketing dataset from the UCI Machine Learning Repository, we aim to assist financial institutions in optimizing their marketing strategies by identifying potential subscribers efficiently.

Dataset
The dataset originates from the UCI Machine Learning Repository and contains a variety of features related to bank clients and their response to direct marketing campaigns (phone calls) of a Portuguese banking institution. The goal is to predict the binary outcome (yes or no) to the question: will the client subscribe to a term deposit?

Dataset Link: Bank Marketing Dataset

Features
The dataset includes several input variables:

Client Information: age, job, marital status, education, etc.
Last Contact Information: contact communication type, month, day of the week, duration, etc.
Other Attributes: campaign, pdays, previous, poutcome, etc.
Social and Economic Context Attributes: employment variation rate, consumer price index, etc.
Methodology
The project follows these steps:

Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
Exploratory Data Analysis (EDA): Visualizing the distribution of variables and identifying relationships between them.
Model Building: Training a decision tree classifier with the preprocessed data.
Model Evaluation: Using accuracy and the confusion matrix to assess model performance.
Feature Importance Analysis: Identifying the most influential features in predicting the outcome.
Results
The initial decision tree model achieved an accuracy of approximately 88.69%.
After hyperparameter tuning with grid search, the optimized model's accuracy improved to 91.50%.
Feature importance analysis revealed that certain demographic and last contact features significantly influence the model's predictions.
Visualizations
Feature Importances: A bar chart showcasing the influence of each feature on the model's predictions.
Confusion Matrix: A heatmap displaying the model's performance in terms of true positives, true negatives, false positives, and false negatives.
Conclusion
The decision tree model demonstrated robust performance in predicting customer behavior towards bank term deposit subscriptions. This model can serve as a valuable tool for banks to enhance their direct marketing strategies, allowing for more targeted and efficient customer outreach.

How to Use
Instructions on how to set up the environment, load the dataset, run the model, and interpret the results are provided in the Jupyter notebooks included in this repository.

Requirements
A list of libraries required to run the project, such as pandas, numpy, matplotlib, seaborn, scikit-learn, etc., is included in the requirements.txt file.
