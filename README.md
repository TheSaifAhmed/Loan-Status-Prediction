# Loan-Status-Prediction
## Project Overview
This project involves building a SVM (Support Vector Mcahine) machine learning model to predict the status of loan applications. Accurate prediction of loan status can help financial institutions in their decision-making process, allowing them to minimize risk and maximize profit.

## Dataset
The dataset used in this project includes various features related to loan applicants, such as their demographic details, employment information, credit history, and loan amount. The target variable is the loan status, which indicates whether a loan was approved or not.

## Project Steps
### 1. Data Preprocessing
Loading the Dataset: The dataset is loaded into a Pandas DataFrame.
Exploratory Data Analysis (EDA): EDA is performed to understand the distribution of the data, check for missing values, and visualize the features.
Handling Missing Values: Missing values are handled appropriately, either by imputation or removal.
Encoding Categorical Variables: Categorical variables are encoded into numerical values using techniques such as one-hot encoding and label encoding.
Data Splitting: The dataset is split into training and testing sets to evaluate the model's performance.
### 2. Model Construction
Model Selection: Several machine learning algorithms are considered, including Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
Model Training: The models are trained on the training dataset using the fit method.
### 3. Model Evaluation
Performance Metrics: The models' performance is evaluated on the test dataset using metrics such as accuracy, precision, recall, and F1-score.
Model Selection: The best-performing model is selected based on the evaluation metrics.
### 4. Results and Analysis
Model Accuracy: The accuracy of the selected model on the test dataset is 83.33%.
Feature Importance: The importance of each feature in predicting the loan status is analyzed.
Prediction Visualization: The predicted vs actual loan statuses are visualized to assess the model's performance.
## Conclusion
The selected SVM model achieved an accuracy of 83.33% on the test dataset. This result indicates that the model is capable of accurately predicting the loan status based on the input features. The analysis of feature importance suggests that certain factors, such as credit history and employment information, play a significant role in determining loan approval.

By implementing this model, financial institutions can make more informed decisions regarding loan approvals, ultimately reducing risk and enhancing profitability.

## Acknowledgements
The dataset used in this project is available from Kaggle. Special thanks to the creators of this dataset for providing the data.

