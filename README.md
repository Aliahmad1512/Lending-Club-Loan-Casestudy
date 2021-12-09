# Lending-Club-Loan-Casestudy
### We will be exploring publicly available data from LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors). Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
### Borrowers can easily access lower interest rate loans through a fast online interface. These files contain complete lending data for all loans issued from 2007-2010 and try to classify and predict whether or not the borrower paid back their loan in full. The file is a matrix of about 9500 observations and 14 variables.

We will use different Classifiers models like Logistic Regression, Decision Tree and Random Forest to see that which model will give the better accuracy and lower root mean square error (RMSE).

### Data dictionary:
* credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
* purpose: The purpose of the loan (takes values “credit_card”, “debt_consolidation”, “educational”, “major_purchase”, “small_business”, and “all_other”).
* int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* installment: The monthly installments owed by the borrower if the loan is funded.
* log.annual.inc: The natural log of the self-reported annual income of the borrower.
* dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* fico: The FICO credit score of the borrower.
* days.with.cr.line: The number of days the borrower has had a credit line.
* revol.bal: The borrower’s revolving balance (amount unpaid at the end of the credit card billing cycle).
* revol.util: The borrower’s revolving line utilization rate (the amount of the credit line used relative to total credit available).
* inq.last.6mths: The borrower’s number of inquiries by creditors in the last 6 months.
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: The borrower’s number of derogatory public records (bankruptcy filings, tax liens, or judgments).
* not.fully.paid (Target Variable): Whether or not the borrower paid back their loan

![https___specials-images forbesimg com_imageserve_5e4e8eb1765d4500072cc7b4_US-ECONOMY-LENDING-CLUB_960x0 (1)](https://user-images.githubusercontent.com/88396377/145459456-2c151c58-c1e4-4a01-8b93-463cf1c3d065.jpg)
