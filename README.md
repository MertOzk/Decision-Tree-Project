# Decision-Tree-Project
To be able to view this project you will need Python, Jupyter Notebook and Anaconda installed. You can click on the hyperlinks to look at a guide on how to install them. Please install the workbook and the dataset and change your directory to the downloaded folder to successfully run the workbook.

For this project I explored  [LendingClub.com's](www.lendingclub.com) publicly available data from 2007-2010 provided by [Pieran Data](https://pieriantraining.com/). Lending Club is a platform that brings together investors and borrowers. My goal was to create a model that would predict high return investments. I created a decision tree and a random forest model to predict and classify whether or not the borrower paid back their loan. This could be used to determine who is a better investment, while comparing the performances between random forest and decision tree models. 

Here are what the columns represent:
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
