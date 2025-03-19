# Titanic Survival Prediction

**Project Overview**

This project aims to predict the survival of passengers on the Titanic using machine learning. 

**Dataset**

The project uses the "tested.csv" dataset, which contains information about passengers such as age, sex, class, etc.

**Methodology**

1. **Data Preprocessing 
    * Handling missing values (imputation).
    * Encoding categorical features (one-hot encoding, label encoding).
    * Feature engineering (e.g., creating 'TicketPrefix', 'TicketLength').
2. **Model Selection and Training 
    * Logistic Regression is used as the prediction model.
    * Data is split into training and testing sets.
    * The model is trained on the training data.
3. **Model Evaluation 
    * Model performance is evaluated using metrics like accuracy, confusion matrix, and probability predictions.
    * A DataFrame is created to store actual values, predicted values, and probabilities.

**Results**

* Training Accuracy: [100]
* Testing Accuracy: [100]
* Overall Accuracy: [100]

**Confusion Matrix:**

[[50  0]
 [ 0 34]]

**Probability DataFrame:**

  Probability_Class_0   Probability_Class_1  Actual_Value  Predicted_Value
0                  1.00                 0.00             0                0
1                  0.01                 0.99             1                1
2                  0.99                 0.01             0                0
3                  1.00                 0.00             0                0
4                  0.01                 0.99             1                1
..                  ...                  ...           ...              ...
79                 1.00                 0.00             0                0
80                 1.00                 0.00             0                0
81                 0.00                 1.00             1                1
82                 1.00                 0.00             0                0
83                 0.01                 0.99             1                1


**Contributing**

Feel free to contribute to this project by opening issues or submitting pull requests.

**License**

[ MIT License]
