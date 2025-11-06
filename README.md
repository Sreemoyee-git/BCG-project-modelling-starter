# BCG-project-modelling-starter

Problem Statement:

"As a Junior Data Scientist at BCG X, you are tasked with investigating a customer churn problem for a client, PowerCo. PowerCo suspects that price sensitivity is driving their customers to switch providers, and you need to leverage data science techniques to solve this challenge. The problem involves analyzing and cleaning real-world datasets, engineering features, building predictive models, and translating insights into actionable business recommendations.

Your objective is to identify the factors that contribute to customer churn, predict future churn behavior, and provide strategic recommendations to PowerCo that can help reduce churn and improve customer retention." (According to Forage problem statement)

What I Did:

1. Evaluation:

I evaluated the trained Random Forest model using various metrics to assess its performance. The key metric used for evaluation was the Accuracy Score, which stood at 90.1%. This score indicates that the model correctly predicted customer churn 9 times out of 10.

Classification Report: I examined precision, recall, and F1-score for each class to understand how well the model performed in identifying both the churned and non-churned customers.

Confusion Matrix: I used the confusion matrix to visualize the model’s prediction errors, which helped in understanding false positives and false negatives.


2. Modeling:

Random Forest Classifier: I used the Random Forest classifier, which is an ensemble algorithm. This method aggregates predictions from multiple decision trees to improve the overall model accuracy and generalization. The model was trained using training data, and predictions were generated on the test data.

Feature Engineering: The dataset was pre-processed by handling missing values and encoding categorical features to make them suitable for machine learning algorithms.

Tools Used:

Python, Libraries like - Scikit-learn, Pandas

Recommendation:

1. Model Performance Improvement:

While the model achieved a good accuracy of 90%, further improvements can be made by tuning the hyperparameters of the Random Forest algorithm. Techniques such as Grid Search or Randomized Search could be used to find the best-performing parameters (e.g., number of trees, max depth).

Feature Selection: Additional feature engineering could be performed to identify important features that impact churn, which might improve model performance.

2. Evaluation Metrics:

While accuracy is useful, it’s important to balance precision, recall, and F1-score based on the business context. If the goal is to minimize false positives (predicting a customer will churn when they won't), improving precision might be critical.

Conclusion:

The Random Forest model has performed well in predicting customer churn with an accuracy score of 90%. The classification report and confusion matrix show that the model maintains a good balance between precision and recall. This model is reliable for predicting churned customers, but there’s room for improvement in performance by fine-tuning hyperparameters and optimizing features. The insights from this analysis will help PowerCo identify high-risk customers and take preventive actions to reduce churn. Future iterations should focus on deeper feature engineering and exploring other algorithms like Gradient Boosting or XGBoost for potential performance gains.
