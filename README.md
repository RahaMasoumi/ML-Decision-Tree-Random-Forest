# ML-Decision-Tree-Random-Forest
This is the forth exercise that I have done during the course for "Data Science and Machine Learning Bootcamp" in Udemy.
For this exercise I have used the public data ("Lending Club"), avaible on [LendingClub.com](www.lendingclub.com). 
Lending Club connects people who need money (borrowers) with people who have money (investors).

The data is from 2007-2010. We will try to classify and predict whether or not the borrower paid back their loan in full. You can download the data from [LendingClub.com](www.lendingclub.com). But I have used the csv file provided by Udemy without NA values.
Below I am explaining 
* credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
* purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
* int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* installment: The monthly installments owed by the borrower if the loan is funded.
* log.annual.inc: The natural log of the self-reported annual income of the borrower.
* dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* fico: The FICO credit score of the borrower.
* days.with.cr.line: The number of days the borrower has had a credit line.
* revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
* revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
* inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).
