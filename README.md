Objective: Develop a predictive model using credit history & demographic data to estimate individuals’
annual income.
Overview:
In this case study, the task is of building your own model to estimate individuals’ annual income based on their credit history &
demographic data. This is a real-world problem commonly faced by insurance companies, where estimating
income accurately helps in determining risk profiles, premium affordability, and coverage levels for clients.
You will be provided with two datasets:
1. Demographic data, which includes actual income and other personal details.
2. Credit history data, which contains detailed information on each individual’s credit behaviour.
Your need to:
1. Evaluate the accuracy of the income estimates compared to actual income.
2. Build a predictive model to estimate income based on credit history.

Dataset Descriptions:
1.Demographic Data (Demographic Details.xlsx):
• Features:
o ID: Unique Identifier of the individual.
o Gender: The gender of the individual.
o Occupation: The individual’s occupation category
▪ 1 : Salaried
▪ 2 : Self – Employed
▪ 3 : Others
o Annual_Income: The true annual income of the individual.
o City_Rank : Rank (Lower the rank better the city) of the city based on the income & health
infrastructure available.
o Pincode : Pincode of the individual.


2. Credit History Data (credit_data.csv, pipe (|) separated):
• Features:
o ID: Unique Identifier of the individual.
o Account_Type: Type of Loan account; Ex. – Home Loan, Credit Card, Personal Loan, etc.
o Balance: The entire amount of credit/loan that is outstanding as on date.
o Sanction_Amount: Loan amount sanctioned for the account; applicable for accounts other than
credit card.
o Credit_Limit: Total borrowing limit on a credit card account.
o Date_Opened: Date when the account was opened.
o Date_Closed: Date when the account was closed.
o Installment_Amount: Monthly payment/EMI amount for the account.
o Past_Due_Amount: The amount that is due (from the past EMI’s) as of the date reported.
o Repayment_Tenure: Number of months of repayment for the account.
o Terms_Frequency: Payment frequency of the account (Weekly, Monthly, Fortnightly and
Quarterly).
o Ownership_Type: Indicates the ownership type of the account (Individual, Guarantor, Joint
holder, etc.).
o Last_Payment_Amount: The last payment amount as of the date reported.
o Last_Payment_Date: Date of last payment.
o Credit_Score : Score between 300 to 900 showing the credit worthiness of the individual.
