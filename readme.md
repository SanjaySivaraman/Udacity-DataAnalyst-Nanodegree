# Analysis of Loan Prosper Data
## by Sanjay

## Dataset

> Dataset Information :
* The dataset chosen is Loan Data from Prosper.
* This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
* It was last updated on 03/11/2014.
> Data Wrangling :
* Since the dataset was found to be huge in the preliminary descriptive analysis,Necessary columns for visulaisation were shortlisted and Data Wrangling was performed as an iterative columnwise process whenever the variable(column) was used. 

## Summary of Findings

* Almost 75% of the Loan amount provided by the bank is lunder 12000.
* Most loans are currently ongoing,followed by loans completed and charged off.
* People who are employed are the ones who prosper a loan the most.
* The Borrower rate and the Borrower annual pecentage rate shares a strong relationship with each other.
* The loan amounts tends to be higher wih lower Borrower rate and Borrower annual percentage rate.  
* People in the median income range are the ones who most prosper the loan.
* The median loan amount increases steadily with a increase in proserity rating.
* The house owners always recieve a higher loan amount irrespective of the prosperity rating.

## Key Insights for Presentation

>Our Key Insights are based on the features of interest : Status of the Loan and Amount of the Loan.

* Most loans are current and completed while the defaulted, past-due loans frequency are comparitively lesser. This metric indicates the stringent perfomance of the bank and aids the cash flow.

* There is a steady increase in the loan amount granted with higher prosperity rating and by owning a home at each prosperity rating.

* A cut down in Borrower rate, would increase the loan amount prospered due t0 their inverse relationship.

## Feedback recieved and adhered

* Using color only when they are needed to differntiate.
* Labeling all the axes and adding title.
* Ordering Ordinal Categorical Variables in their increasing order.

## Resources :

* https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0
* https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.api.types.CategoricalDtype.html
* https://stackoverflow.com/questions/27965295/dropping-rows-from-dataframe-based-on-a-not-in-condition
* https://stackoverflow.com/questions/23307301/replacing-column-values-in-a-pandas-dataframe