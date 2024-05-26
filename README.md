# ML_Algorithm-Random_Forest
In this notebook, we have used the random forest to build the model that can predict the customer churn of telecommunication services. 'Churn' column in the dataset has been considered as the target column.
The independent columns are 'gender', 'SeniorCitizen', 'Partner', 'Dependents', 'tenure','PhoneService', 'MultipleLines', 'InternetService', 'OnlineSecurity','OnlineBackup', 'DeviceProtection', 'TechSupport', 'StreamingTV', 'StreamingMovies', 'Contract', 'PaperlessBilling', 'PaymentMethod','MonthlyCharges', 'TotalCharges'.
In the context of the Churn dataset, the churn label indicates whether a customer has churned or not. A churned customer is one who has decided to discontinue their subscription or usage of the company's services. On the other hand, a non-churned customer is one who continues to remain engaged and retains their relationship with the company.
I have included the steps I have taken to build the model on this dataset:
## Table Of Content
### Importing the Library
I have imported almost all the libraries that will be used from EDA till model building and predicting the model accuracy.
### Uploading the Dataset
I have uploaded the dataset from the google drive to my colab notebook on which I have built this model. You can find the similar dataset in the Kaggle.
### Exploratory Data Analysis
We have used the pandas for data wrangling purpose. Pandas has been very useful tools to understand the nature of independent and dependent columns. Also they have useful for manipulating the data so that it can useful for building the models.
### Data Cleaning
We have done analysis of missing values and outliers on this dataset. Since the volume of null values were less than 1 precent so we have dropped the null values.
### Label Encoding
We have imported the module 'LabelEncoder' that has been used to convert the independent columns of object datatype to numerical values. This is one of the crucial steps in order to use this Algorithm for building the model.
### Splitting the Data and Model Building
I have splitted the data in train and test data. It will include x_train, x_test, y_train, y_test. x_train and y_train has 80% of the data. while x_test and y_test have remaining 20% of the data. I have imported the 'Random Forest' algorithm from scikit-learn and used it to build the model by using the x_train and y_train data.
### Predicting the model efficiency
I have import accuracy_score from sklearn and used to predict it the model accuracy. We have imported 'Classification Report' from Sklearn. I have built the classification report based on prediction data and test data.


