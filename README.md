# Prosper Loan Data Analysis


## Dataset

The data set contains 84853 loan with 22 columns information like BorrowerAPR, ProsperScore, DebtToIncomeRatio, MonthlyLoanPayment, credit score, StatedMonthlyIncome and so on.
1. I created subset of the columns to 22 from 81 columns.
2. looked for duplicate rows.
3. converted datatypes of ListingCreationDate, ClosedDate, DateCreditPulled to datatime and seperated time from columns.
4. Deleted the rows with out prosper score.

## Summary of Findings

In the exploration part, the following are my finding:-
1. The borrower APR have negative relationship with loan original amount. It means large amount of loans have low ARP.
2. The borrowers with out proper income have more delinquencies.
3. The borrower have employment paid their monthly loan payments on time.
4. The most of the borrowes have good credit score when their income is high. only few borrower have 840 above credit score and AA rating.The borrowers with credit score above 660 have all types of rating except AA.
5. The loan amount for all terms increases with good prosper rating and also there is increase in term for larger loan amount.
6. Lower rating were noted on past due and final payment in progress loans and highest rating were noted on current and completed loans.
7. The most of the loans are active.
8. The most rationg to borrowers is c and least rationg is AA.
9. The most of the borrowers pay upto 250$ monthly for their loans.
10. The most of the borrowers are other and professional. The least borrowers are from students.
11. In the distribution of Borrower APR, there are more loans with 3.5 and 3.6 APRate.
12. There are more number of loans with the amount of below 5000K and small number of loans in the amount from 20K to 35K.
## Key Insights for Presentation

For my presentation, I want to focus on the following ponits.
1. The borrower APR have negative relationship with loan original amount. It means large amount of loans have low ARP. So, I want to know weather any other variables effct borrower APR like prosper rating and term. Then, I showed the relationship between them.
2. The top 3 occupations have high monthly loan payment are Judge, Doctor, and Pharmacist. The plot is consistent with salaries of each occupation. we can say this by seeing plots also employed have high monthly loan payment. Now I want to known weather any other factors like borrower rate effect the loan monthly payment.
