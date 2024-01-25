**Module_20_Challenge-Credit_Risk_Classification**

The goal of this project is to create a logistic regression model for classifying credit risk. The aim is to forecast whether a loan is low-risk or high-risk, relying on diverse features supplied by the lending company.

**Requirements**

Python v3.10.9

The following libraries are required to run the analysis code:

1. numpy (imported as np): A library for numerical computations and array operations.
2. pandas (imported as pd): A library for data manipulation and analysis.
3. pathlib from the Python Standard Library: A module for working with file paths.
4. confusion_matrix from sklearn.metrics: A function to compute the confusion matrix for model evaluation.
5. classification_report from sklearn.metrics: A function to generate a classification report, including precision, recall, and F1-score.
6. LogisticRegression from sklearn.linear_model: A class for logistic regression model implementation. Make sure to have these libraries installed in your environment before     running the analysis code.

**Workflow of the Project**

The project adheres to the subsequent workflow:

1. Data Splitting into Training and Testing Sets: The "lending_data.csv" file from the Resources folder is imported into a Pandas DataFrame. The "loan_status" column is utilized   to generate the labels set (y), while the remaining columns contribute to the creation of the features DataFrame (X). Subsequently, the data undergoes division into training and testing datasets using the train_test_split function.
2. Development of a Logistic Regression Model with the Original Data: The logistic regression model is constructed using the training data (X_train and y_train) through the logistic regression algorithm. The model is then employed to predict labels for the testing data (X_test). The model's performance is assessed by producing a confusion matrix and presenting the classification report. Additionally, an evaluation is conducted on the model's capability to predict both healthy loans (0) and high-risk loans (1).
3. Credit Risk Analysis Report: The project integrates a file named "CreditRiskAnalysisReport.md," which furnishes a concise analysis of the logistic regression model's performance. The report adheres to the structure outlined in the provided report template and encompasses the subsequent segments:

**Analysis Overview:** This section articulates the purpose of the analysis, focusing on the development of a logistic regression model for credit risk classification based on the supplied dataset.
**Results**: A list in bullet points delineates the accuracy score, precision score, and recall score of the logistic regression model. These metrics offer insights into the model's efficacy in predicting loan classifications.
**Summary:** This segment encapsulates a condensed version of the results obtained from the logistic regression model. It provides a rationale for recommending the model for adoption by the lending company. In instances where the model is not recommended, the rationale behind this decision is also expounded upon.

**Repository Structure**

1. The Credit_Risk_Classification_Analysis.ipynb file contains the code for the analysis, including data preprocessing, model creation, and evaluation.
2. The CreditRiskAnalysisReport.md file houses the Credit Risk Analysis Report, which provides a summary and analysis of the model's performance.
3. The Resources folder contains the lending_data.csv file, which is the dataset used for the analysis.

   **Conclusion**

In conclusion, the logistic regression model developed for credit risk classification exhibited a strong performance in predicting loan statuses. The model leveraged the provided dataset and utilized various features to distinguish between healthy and high-risk loans. The Credit Risk Analysis Report, which provides a comprehensive summary and analysis of the model's performance, can be accessed here. It includes an overview of the analysis, detailed results, and a justification for recommending the model for use by the lending company.

