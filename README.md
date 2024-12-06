# Using Machine Learning for the recommendation of plans for the company MEGALINE

## PROJECT OVERVIEW

Mobile company Megaline is not happy to see that many of its customers are using legacy plans, which are mobile plans that a person has had for a long time and are no longer available to new customers or users. We need to develop a model that can analyze customer behavior and recommend one of Megaline's new plans: Smart or Ultra.

We have access to behavioral data of subscribers who have already switched to the new plans. The classification model must choose the right plan for the customer based on their consumption habits.

Develop a model with the highest possible accuracy. In this project, the accuracy threshold is 0.75. Use the dataset to check the accuracy.

For the development of the model we will use the following machine learning algorithms:

- Decision Tree
- Random Forest

The overall data will be split into training, validation, and test sets. Both models will be trained and fine-tuned using the training and validation sets, with the goal of optimizing the hyperparameters to achieve maximum accuracy. Once the optimal hyperparameters are established, the models will be evaluated using the test set, and the one with the highest accuracy will be selected as the final model.


## STEPS:

### STEP 1: IMPORTING LIBRARIES

### STEP 2: IMPORTING DATABASES

### STEP 3: DATA EXPLORATION

### STEP 4: MODELING

### STEP 5: TEST MODEL

### STEP 6: SANITY CHECK


## CONCLUSION

Mobile operator Megaline requested a trained model that would recommend one of its newer plans to customers continuing to use legacy plans. It was determined that this was a binary classification task as only the Ultra or Smart plan could be recommended. Therefore, the two models that were trained were a Decision Tree model and a Random Forest.

The features and target data were divided into 3 datasets as follows:

Training dataset (60%)
Validation dataset (20%)
Test dataset (20%)

Multiple models were created with various combinations of hyperparameters. They were trained on the same data and then their accuracy was compared. The Decision Tree and Random Forest models were then tested with higher accuracy using the test data. The accuracy of the best Decision Tree model was calculated to be 79.32% and the accuracy of the best Random Forest model was calculated to be 80.09%. Both models exceed the accuracy threshold of 75%. The best Random Forest model is slightly more accurate than the best Decision Tree model, so that should be the model delivered to Megaline.

PROJECT BY: GIORGIO RAMIREZ QUIROZ
