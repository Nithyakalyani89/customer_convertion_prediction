# customer_convertion_prediction
This project aims to predict customer conversion for an insurance company. Using historical data, we will develop a machine learning model that can identify which customers are most likely to purchase a policy. By understanding the patterns and behaviors of previous customers, the model can make predictions and provide valuable insight to the company. The objective is to increase the rate of successful conversions and ultimately improve the company's bottom line.
# Project Aproach:
For this project, I utilized Google Colab as my integrated development environment (IDE) for programming in Python. Google Colab is a robust tool provided by Google that is well-suited for implementing machine learning algorithms, performing data analytics and cleaning operations, and developing data science models.
# Steps:
1. Libraries Import and Load Dataset
   I have imported requrired libraries and also loaded dataset.
2. Clean Dataset
   I have used functions like remove duplicates,dropped null values,missing values,check data type and removal of outlires.
3.Exploritory Data Analysis
   For the good model fit and accuret prediction we've explore the data and done Univariate Analysis, Bivariate Analysis, Correlation Check. Data type check and take dummies.
* Univariate Analysis
  The class distribution in the target variable is ~89:11 indicating an imbalance dataset.
* Bivariate Analysis
  I have check and learn that which type of occupations have more chances to subscribe our term insurance policy.
* Correlation
  I have checked correlation between differant variables. We can see here Duration of Call is Highly correlated to our target variable.
 # Encoding
  I have used Label and one hot encodeing for this features['job', 'marital', 'education_qual', 'call_type', 'mon', 'prev_outcome']
 # Split Dataset
  SMOTE Oversampling we are using due to imbalence data.
# Scalling
  I used StandardScaler.
# Models
  I used Logistic regression,xgboost and Random Forest.
  I can see that Dur(Duration) is most important feature in dataset.
# Model Evaluation
We are going to compare auroc curve.
# Conclusion
Based on the results obtained from the evaluation of the three classification models (Logistic Regression, XGBoost, and Decision Tree Classifier) on the given historical data, XGBoost outperformed the other models with the highest accuracy score of 93.54% and the highest AUROC score of 0.986.
This implies that XGBoost is a suitable model for predicting whether a client will subscribe to the insurance or not. It is recommended to deploy this model in the production environment to accurately target potential customers and optimize marketing costs.

   
