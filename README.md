# Loan-Approval-Prediction

**Indroduction**

The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling out the online application form. 
These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. 
To automate this process, they have given a problem identifying the customer segments eligible for loan amounts to target these customers specifically. 
Here they have provided a partial data set.

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
