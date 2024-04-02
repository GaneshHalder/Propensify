# Propensify


**Introduction**

This repository contains code for building a propensity model aimed at identifying potential customers for an insurance company. The model is trained on historical data provided by the company and tested on a separate set of potential customers



**Project Structure:**

**Train.xlsx** 

**Test.xlsx** 

**Propensity_Model.ipynb** 

**Source_code_pipeline.ipynb** 

**Propensify.joblib** 

**Preprocessing_pipeline.joblib**





**In this project:**

Open the Propensity_Model.ipynb notebook in Jupyter Notebook or any compatible environment.

Load and explore the historical training data (train.xlsx).

Preprocess the data, handle missing values, encode categorical variables, and perform feature engineering.

Split the data into training and validation sets.

Build a machine learning model (e.g., Random Forest Classifier) to predict customer propensity.

Evaluate the model's performance using metrics such as accuracy, precision, recall, and ROC-AUC score.

Tune hyperparameters using techniques like GridSearchCV to improve model performance.

Implement an ensemble classifier (e.g., Voting Classifier) combining multiple models for better prediction accuracy.



**Key Findings**

The propensity model achieved an accuracy of approximately 86% on the test data, indicating its effectiveness in predicting customer behavior.

Hyperparameter tuning using GridSearchCV resulted in improved performance of the Random Forest model, enhancing its predictive capabilities.

The implementation of an ensemble classifier, combining Random Forest and Support Vector Machine models using a Voting Classifier, contributed to improved prediction accuracy.





**Conclusion**

Aapproach to building a propensity model for predicting customer behavior has yielded promising results. The model demonstrated a high level of accuracy, indicating its effectiveness in identifying potential customer responses. By leveraging techniques such as hyperparameter tuning and ensemble modeling, we were able to enhance the model's performance and predictive capabilities. These results provide valuable insights for optimizing marketing strategies and targeting potential customers more effectively, ultimately contributing to improved business outcomes and customer engagement.
