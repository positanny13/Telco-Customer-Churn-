# Telco-Customer-Churn-(Random Forest and Decision Trees)
The goal of this project is to build a predictive model for customer churn in the telecommunications industry. Customer churn refers to the phenomenon where customers stop using a company's services. 
In this case, the company wants to predict which customers are likely to churn so that they can take proactive measures to retain those customers.


Data Exploration and Preprocessing:

The project begins with data exploration, where you load and examine the dataset using Python and the Pandas library.
The dataset contains information about customers, including features like gender, senior citizen status, partner status, dependents, tenure, phone service, internet service, and more.
You analyze the data, check for missing values, and perform necessary data preprocessing tasks, such as converting data types and performing one-hot encoding on categorical variables.
Machine Learning Models:

Two machine learning models are used for this project: Decision Trees and Random Forests.
Decision Trees are initially applied to the preprocessed data. A Decision Tree Classifier is trained on the training dataset.
Random Forests, a more advanced ensemble technique, are then employed. A Random Forest Classifier is trained on the same data.
Model Evaluation:

Model accuracy is evaluated to determine how well each model performs in predicting customer churn.
Classification metrics such as precision, recall, and F1-score are calculated to assess model performance further.
The results are presented in the form of accuracy scores and classification reports.
Conclusion:

The project concludes by comparing the performance of the Decision Tree and Random Forest models.
It appears that the Random Forest model outperforms the Decision Tree model, as indicated by a higher accuracy score.
The classification report provides a more detailed assessment of model performance, including precision, recall, and F1-score for both classes (Churn and No Churn).
In summary, this project aims to help Telco Customer Services identify customers who are likely to churn, allowing the company to take proactive steps to retain those customers and reduce churn rates. Machine learning models are used to make these predictions based on customer data.




