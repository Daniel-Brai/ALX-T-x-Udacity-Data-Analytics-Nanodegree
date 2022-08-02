# Prosper Loan Exploration
## by Daniel Brai


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be downloaded [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) Also, you can see this data dictionary to understand the dataset's variables [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit)

## Summary of Findings

In my the exploration, I found that there was a weak relationship between the Borrower APR and loan amount, with modifying effects to an individual's stated monthly income, and Prosper rating. The relationship is of that the Borrower APR is negatively correlated with Loan original amount because at different size of the loan amount taken, the Borrower APR has a large range but the range of Borrower APR decreases with the increase in Loan original amount. Again, I discovered that most of the Stated monthly incomes were less than 30 thousand US dollars, but some of them were pretty high, reaching 100 thousand US dollars at its peak as such most borowers with a large monthly income borrow less than individual with incomes like than 30 thousand US dollars.

Outside of the main variables of interest, I verified the relationship between
Loan original amount with prosper rating and stated monthly income is such that it is positively correlated since borrowers with more income would loan more money and that borrower with better rating will also have a larger monthly income and loan amount.


## Key Insights for Presentation

In my presentation, the investigation of borrower APR against loan amount by looking at the impact of the Prosper rating. Using facetgrid with scatter plot shows that the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings increased from HR to AA. Again, I explored the rating and term effects on loan amount, it shows that with better Prosper rating, the loan amount of all three terms increases, the increase amplitude of loan amount between terms also becomes larger.

Also, I showed that the BorrowerAPR and Loan original amount turned out to be negatively correlated with Prosper ratings when it is in the range of HR to B, but the correlation is turned out to be positive when the Prosper ratings are A and AA. Also, a decrease in BorrowerAPR correlated with an increase in the term for loan in the range of HR and C Prosper ratings while those with B and AA ratings, there is a direct increase in BorrowerAPR as term increases.
