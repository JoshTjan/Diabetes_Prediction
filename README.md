# Diabetes_Prediction
In this project, I aim to predict the onset of diabetes based on diagnostic measures. We use a dataset that includes several medical predictor variables and one target variable, Outcome. Predictor variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and more.

Here's a summary of the steps we followed in this project:

* Data Exploration: We started by exploring the data using Python. We analyzed the distributions of the features and the relationships between them. This step helped us understand the data better and informed our subsequent steps.
* Data Preprocessing: We preprocessed the data by handling missing values and scaling the features. This step is crucial as it can significantly impact the performance of the machine learning models.
* Model Training and Evaluation: We trained and evaluated several machine learning models, including Logistic Regression, Random Forest, and Support Vector Machine. We calculated several metrics, such as accuracy, precision, recall, and F1 score, to evaluate the performance of the models.
* Hyperparameter Tuning: We improved the performance of the Random Forest model by tuning its hyperparameters using grid search. Hyperparameter tuning is an important step as it can help us find the most optimal parameters for our model, thus improving its performance.

We trained and evaluated several machine learning models, including Logistic Regression, K-Nearest Neighbors, and Random Forest. We found that the Random Forest model had the best performance on the cross-validation sets. We then improved the performance of the Random Forest model by tuning its hyperparameters using grid search.
The best model achieved an accuracy of approximately 76.6% on the test set. It had a precision of approximately 66.7%, meaning that when it predicts a patient has diabetes, it's correct about 66.7% of the time. It had a recall of approximately 69.1%, meaning that it correctly identifies 69.1% of all diabetic patients. The F1 score, which is the harmonic mean of precision and recall, was approximately 67.9%.
These results suggest that the model could be a useful tool for predicting diabetes. However, there's still room for improvement. Future work could explore other preprocessing techniques, feature engineering, other machine learning models, and more extensive hyperparameter tuning.
