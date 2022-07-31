# Prosper Loan Dataset Exploration

## Dataset
The dataset consists of information regarding 113,937 loan listings from an online peer-to-peer lending company Prosper Marketplace. There are 81 variables in the data, including loan amount, borrower rate, borrowers monthly income, current loan status, etc.A feature dictionary describing the variables in the dataset is available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)


## Summary of Findings

In the exploration, I found that there was a strong relationship between Borrower APR, and Credit Rating, with modifying effects from the Loan Category.

In univariate exploration, I found:

* The frequency of listings reduced as the loan amount increased. Over 50% of listings were for loan amounts between 1000 and 5000 dollar, and the distribution of monthly loan payments shows that over 90% of borrowers pay 500 dollars or less.

* The distributions of loan categories, borrower professions, and states showed that the bulk of listings were for debt consolidation, from borrowers who worked mostly in professional fields, and were residents of California.

* It was also noted worthy that loans that are in charged off and defaulted statuses made up over 30% of the listings when combined even though the employment status distribution shows over 95% of borrowers were in full, self or part time employment.

I also observed that credit rating D had the most amount of listings is D followed by C then B.

During bivariate exploration, I found:

* A relationship between credit rating and loan amount as the median loan amount decreased as credit rating rank decreased.

* I observed a relationship between the Term of the loan and loan amount, a longer loan term presented with a higher median loan amount.

* I also observed that monthly income had little effect on loan distribution as even borrowers whose income were on the higher end tended to borrow amounts not exceeding 25000. Infact, the distribution of borrowers who borrowed amounts greater than 25000 dollars were low income earners below 20000.


In multivariate exploration:

* I observed a strong relationship between Borrower APR, loan amount and credit rating. A higher credit rating often gets a lower  APR rate on a loan listing. I then added a fourth feature Loan Category to the multivariate distribution of loan amount and borrower APR by credit rating this allowed me to observe the effects of borrower APR on loan amount and credit rating by loan category.

* The three features loan category,Borrower APR, and credit rating strengthened each other and added visibility to the listing distribution.


## Key Insights for Presentation

The presentation focuses on, showing the effects of selected borrower and loan features 
that have a pronounced effect on Prosper loan distributions.

I start by introducing the the univariate distributions of loan amount, loan categories, 
borrower occupations,borrower state, loan status, employment status and borrower credit rating.
Afterwards, I explore relationships by adding features to variables plotted in univariate distributions.
I use a clustered bar chart to explore the effect of Borrowers Credit Rating on Listing Frequency 
in the top 5 Borrower States.I explore relationships further to create multivariate plots by 
adding APR to bivariate listing distributions