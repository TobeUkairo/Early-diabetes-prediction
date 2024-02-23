# Early-diabetes-prediction
This repository hosts a comprehensive machine learning project focused on predicting the likelihood of diabetes in patients based on a variety of influential factors.
# Executive Summary

**Objective**: Create a predictive model to determine if a patient has diabetes or is potentially diabetic.

**Key Findings**: 
- the features “polydipsia” and “polyuria” are critical factors for predicting if a patient has diabetes or is potentially diabetic. 

- The 'age' column appears to exhibit a normal distribution.

- 63% of our patients are male.

- Approximately 42% of our patients had experienced weight loss.

- the following columns were fairly balanced; Polyuria, Polyphagia, Polydipsia, Delayed healing, Partial paresis, itching, visiual blurring.

- Approximately 59% of our patients had experienced weakness.

- 78% of our patients had experienced genital thrush.

- Approximately 24% of our patients had experienced irritalbility.
  
- 38% of our patients had experienced muscle stiffness.
  
- 34% of our patients had alopecia.
  
- 17% of our patients were obese.
  
- The target column was slighly imbalanced with approximately 62% of the patients labelled positive.

**Recommendation**: Focus on acquiring high-value brands and adjust pricing strategies based on age, mileage, and fuel type.


## Data Overview

**Dataset Description**: This dataset contains the sign and symptpom data of newly diabetic or would be diabetic patient.



## Data Preparation

**Transformation**: Applied standard scaler to the X_train dataset and X_test dataset.

**Feature Engineering**: used label encoder to encode all categorical variables.

**Model Selection**: compared between KNN, Decision Tree, Logistic Regression and SVM models.

**Hyperparameter Tuning**: Employed GridSearchCV for optimal parameter selection.

## Model Insights and Interpretation

**Model Performance**:

the logistic regression model performed best out of the models compared. after hyper parameter tuning it was able to predict the target variable with 93.6% accuracy, 95% precision, 95% recall, and an F1-score of 95%


## Limitations and Future Work

**Limitations**:

slightly imbalanced dataset. 


## Future Directions

Aim to get a more records of patient data in order to make the model more robust.

## Conclusion

The analysis provides valuable information into factors that help predict if a patient has diabetes or is potentially diabetic. these findings can be used to identify critical factors affecting success of model prediction.
