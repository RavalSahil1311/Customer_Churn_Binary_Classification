# Predicting Customer Churn

## Problem Statement

We are presented with a challenging task: predicting customer churn based on a dataset reflecting customer interactions and behaviors. The objective is to create a robust binary classification model capable of accurately predicting whether a customer will exit the service or stay engaged. For detailed information, refer to the Kaggle competition [here](https://www.kaggle.com/competitions/playground-series-s4e1).

## Dataset

The dataset is divided into two files:

- **Train Dataset ([train.csv](https://www.kaggle.com/competitions/playground-series-s4e1/data?select=train.csv))**
  - Features:
    1. `id`
    2. `CustomerId`
    3. `Surname`
    4. `CreditScore`
    5. `Geography`
    6. `Gender`
    7. `Age`
    8. `Tenure`
    9. `Balance`
    10. `NumOfProducts`
    11. `HasCrCard`
    12. `IsActiveMember`
    13. `EstimatedSalary`
    14. `Exited` (Dependent Feature)

- **Test Dataset ([test.csv](https://www.kaggle.com/competitions/playground-series-s4e1/data?select=test.csv))**
  - Contains all features of Train Dataset
  - Excludes the dependent feature **Exited**

## Approach

In the initial stage, the chosen approach is to employ a Decision Tree for binary classification.

## Steps Taken:

1. **Understanding the Problem:**
   - Delved into the Kaggle competition description to comprehend the requirements and constraints.

2. **Exploring the Dataset:**
   - Analyzed the features in the training dataset ([train.csv](https://www.kaggle.com/competitions/playground-series-s4e1/data?select=train.csv)) and testing dataset ([test.csv](https://www.kaggle.com/competitions/playground-series-s4e1/data?select=test.csv)).
   - Noted the absence of the dependent feature **Exited** in the testing dataset.

3. **Decision Tree Implementation:**
   - Applied a Decision Tree algorithm for the binary classification task.
   - Utilized the training dataset to train the model.
   - Predicted the dependent feature from testing dataset.

4. **Submission:**
   - Exported the dependent feature according to the requirements from kaggle into CSV format.
   - Prepare the submission file with predictions for the Kaggle competition.

## Next Steps (Inorder to Improve model performance):

1. **Feature Engineering:**
   - Investigate and identify potential features that may enhance model performance.

2. **Data Preprocessing:**
   - Manage missing values and outliers.
   - Convert categorical variables into a suitable format for the model.

3. **Model Evaluation:**
   - Assess the performance of the Decision Tree model on the training dataset.
   - Consider cross-validation techniques for a robust evaluation.

4. **Hyperparameter Tuning:**
   - Optimize Decision Tree hyperparameters for improved model accuracy.

5. **Prediction on Test Dataset:**
   - Utilize the trained model to predict outcomes on the test dataset ([test.csv](https://www.kaggle.com/competitions/playground-series-s4e1/data?select=test.csv)).

## Additional Notes:

- Regularly document findings, challenges, and insights to facilitate collaboration and track progress.
- Consider exploring alternative algorithms or ensemble methods to enhance model performance.
