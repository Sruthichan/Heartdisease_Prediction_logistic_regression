# Heartdisease_Prediction_logistic_regression
Heart Disease prediction using Machine learning algorithm Predicting Heart disease is crucial for timely intervention and effective treatment. I hereby propose a data-driven approach that leverages Logistic Regression, a proven statistical method, to improve our predictive capabilities for heart disease diagnosis.


Data Exploration and Analysis: We begin by thoroughly exploring the dataset, employing statistical measures such as mean, median, skewness, and kurtosis to understand the distribution and characteristics of the health indicators. This analysis helps us identify key patterns and potential anomalies in the data.

Visualization: Utilizing histogram and box plots, we will visualize the distribution of various health metrics, allowing us to detect outliers and understand the spread of the data. This step ensures that we accurately capture the range and variability of the features used in our model.

Males: The count plot shows a certain number of males categorized under "HighRisk". This group will likely have a higher number compared to females if males generally have higher cholesterol levels.

Females: The count of females in the "HighRisk" category is typically lower compared to males. This indicates fewer females are in the high cholesterol risk category.

Using correlation analysis, we can focuse on age, cholesterol, fasting blood sugar, ST slope, and chest pain type, how these variables interact with each other and their relationship with the target variable. The correlation matrix and heatmap will help to visualize and interpret these relationships, which helps in feature selection and model building.

 Logistic Regression is used to build a model that predicts the likelihood of heart disease based on the features we’ve prepared. Logistic Regression helps us understand how different features, especially those strongly correlated with heart disease, affect the probability of having the condition.
