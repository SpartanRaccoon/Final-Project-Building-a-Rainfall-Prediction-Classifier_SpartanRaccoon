# Final Project: Building a Rainfall Prediction Classifier_SpartanRaccoon
# click STAR
check this out if you need some hint for the code
please note that there might be some mistakes in the original code:

You have to define important_df by yourself.

You should use gridsearch.fit instead of model.fit (the model is not defined in the original code).

Question 3 :76%

Question 5:
Accuracy
Logistic Regression: 84%
Typically performs well on high-dimensional data or linearly separable data, but may perform poorly on non-linear data.

Random Forest Classifier: 83%
Due to its ensemble learning approach, it generally performs better on non-linear data and is capable of capturing complex feature interactions.

True positive rate
Logistic Regression:
No: 93%
Yes: 51%

Random Forest Classifier:
No: 95%
Yes: 50%

Both models have a high recall for the "No" class, indicating they are good at identifying non-rainy days. However, the recall for the "Yes" class is relatively low for both models, suggesting they struggle to correctly identify rainy days.

 the Random Forest Classifier is a slightly better predictor of whether it will rain tomorrow
