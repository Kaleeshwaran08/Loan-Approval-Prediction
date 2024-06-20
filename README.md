# Loan-Approval-Prediction

**Indroduction**

Loan approval prediction is traditional preoblem and given at various Hakathon on various platforms such as Kaggle. Training datset consists of Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area and Loan_Status (Approved/Rejected). Using this data a Machine Learning model is to create such that next time it will predict that if Loan for particular application is to approve or not.

**Data descrption**

* Loan_ID: A unique ID assigned to every loan applicant
* Gender: Gender of the applicant (Male, Female)
* Married: The marital status of the applicant (Yes, No)
* Dependents: No. of people dependent on the applicant (0,1,2,3+)
* Education: Education level of the applicant (Graduated, Not Graduated)
* Self_Employed: If the applicant is self-employed or not (Yes, No)
* ApplicantIncome: The amount of income the applicant earns
* CoapplicantIncome: The amount of income the co-applicant earns
* LoanAmount: The amount of loan the applicant has requested for
* Loan_Amount_Term: The no. of days over which the loan will be paid
* Credit_History: A record of a borrower's responsible repayment of debts (1- has all debts paid, 0- not paid)
* Property_Area : The type of location where the applicant’s property lies (Rural, Semiurban, Urban)

To try most possible ways to get maximum accuracy number of Machine Learning Algorithms are tried with data with Parameter tunning. 
Also tried with Voting Ensemble Method. Aim was to check efficiency of classifiers on the given data.

**Model Building: Train and evaluate multiple classifiers:**

Logistic Regression, Decision Tree Classifier, Random Forest Classifier,KNeighborsClassifier ,XGBoost Classifier,DecisionTreeClassifier ,GaussianNB

**Model Evaluation:**
Select the best-performing model and predict outcomes for the test dataset.
