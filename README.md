# Insurance-Cross-Selling-Prediction

### Introduction:
In this project, the goal is to develop a predictive model for insurance cross-selling. The objective is to determine whether customers are likely to purchase additional insurance products when presented with cross-selling opportunities. Accurate predictions of customer behaviour can enhance marketing strategies and increase the success rate of cross-selling campaigns.

### Task:
The primary task involves creating a machine learning model capable of classifying customers into two categories: those inclined to purchase additional insurance (positive class) and those not inclined (negative class). This binary classification facilitates targeting the right customers and optimizing cross-selling efforts.

### Steps:
1. Data Exploration
2. Data Pre-processing
3. Model Selection and Implementation
4. Model Performance Evaluation:

### Results:
The final output table summarizes the performance of each implemented machine learning model on both the training and testing datasets. The following metrics are presented:

* Accuracy Score Train: The accuracy of the model on the training dataset.
* ROC-AUC Score Train: The ROC-AUC score of the model on the training dataset.
* Accuracy Score Test: The accuracy of the model on the testing dataset.
* ROC-AUC Score Test: The ROC-AUC score of the model on the testing dataset.

The table lists various models and their corresponding performance metrics, allowing easy comparison and identification of the top-performing models.

| Model                      | Accuracy Score (Train) | ROC-AUC Score (Train) | Accuracy Score (Test) | ROC-AUC Score (Test) |
|----------------------------|------------------------|-----------------------|-----------------------|----------------------|
| KNN                        | 0.874                  | 0.954                 | 0.753                 | 0.730                |
| Random Forest Classifier    | 0.990                  | 0.999                 | 0.807                 | 0.765                |
| Logistic Regression         | 0.657                  | 0.706                 | 0.621                 | 0.705                |
