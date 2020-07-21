## HR_Analytics - Understanding Workforce of a company by using Machine learning algorithm

HR can hugely contribute to success of a company. This is because it manages the workforce of a company. 
The good understanding of an employee is important. That is, various factors such as education, age, degree, work experience, city and so on of an employee can play significant role. The information about these factors can be accumulated as dataset. These data, in turn, can be analysed and which can be used for recruiting, staff rtention, analysis of employement market or development of employee. With the help of HR-Anlytics, HR department can react dynamically and swiftly. 

HA needs a model to find answers to a couple of question such as job change or incentive measures for a certain group of employees. 
HA also wants to know the likelihood of job change by a new employee.

Important steps towards understanding HR-Analytics:

- [ ] Data cleaning, handling of missing value:

     There are many categorical variables with missing values. Different approaches have been taken to handle missing values.
     Label encoding and Dummy variables have been created for modeling.
       
- [ ] Data Analysis
- [ ] Building a Model
- [ ] Prediction Accuracy

     The accuracy of the model is important to consider if it reflects the real-like situation. Usually the higher the Accuracy Score, 
     the better the Model prediction is.To understand them in statistical detail, confusion_matrix is appropriate. 
     **Accuracy-Score from both Logistic Regression and XGB Classifier is 0.87**.
     But the **number of employees with a job change request predicted by these models is 9 and 46**, respectively.
     Although the Accurray Score for XGB Classifier and Logistic Regression is the same,
     the number of employees with **a job change request that the XGBoost model predicted is higher**. 
     This demonstrastes the better predicting power of XGBoost model.
      
  
  
[README in German](https://github.com/onarayan/HR_Analytics/blob/master/README.md.de)     


[Data Source: JanataHackathon](https://datahack.analyticsvidhya.com/contest/janatahack-hr-analytics/)
