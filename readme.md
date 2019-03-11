# Prosper Loan Data
## by E.Karaseva


## Dataset

Prosper Marketplace is America's first peer-to-peer lending marketplace, with over 7 billion USD in funded loans. Borrowers request personal loans on Prosper and investors (individual or institutional) can fund anywhere from 2,000 USD to 35,000 USD per loan request. Investors can consider borrowers’ credit scores, ratings, and histories and the category of the loan. Prosper handles the servicing of the loan and collects and distributes borrower payments and interest back to the loan investors. [ref. https://en.wikipedia.org/wiki/Prosper_Marketplace]

The data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

Details with regards to variables can be found here: https://docs.google.com/spreadsheet/ccc?key=0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE&usp=sharing and here: https://www.prosper.com/Downloads/Services/Documentation/ProsperAPI_Objects_Details.html

## Summary of Findings

By examining single variables we saw that Borrower Rate/APR is normally distributed with mean at about 18-20%. The user score range looks a bit skewed left, with few strange gaps. Furthermore, we observed quite a big percentage of non-performing (charged off, defaulted, Past-Due) loans in the data. As an investor, you should be conscious about performance of your money. The model that provide such high amount of bad loans requires improvement.

The highest average Prosper Borrower Rate had its maximum in q4 2010, after that it decreased. 

Bad performing rate is quite high over the years and didn't improve a lot after 2008 financial crisis.

Borrower Rate is strongly dependent on Prosper Rate and has different behaviour for users with different income. 

We saw clear different patterns of Borrower Rate for different loan duration over the years and it gives some understanding on how choice between different loan durations is made.

We saw clear difference in relation between Loan Amount and Monthly Payment with regards to different loan durations. 
