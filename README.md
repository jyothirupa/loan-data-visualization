# loan-data-visualization

## Installation

```
git clone https://github.com/jyothirupa/loan-data-visualization
cd loan-data-visualization
pip install -r requirements.txt
```


## Dataset

The dataset consists of 113,937 loan records with 81 features out of which 11 
features have been carefully selected and retained in order to limit the scope 
of the analysis. Univariate, bivariate and multivariate visualizations will be 
used in order to visualize the various insights that can be obtained from the 
data. After performing preliminary data wrangling on the dataset, both exploratory 
and explanatory analysis will be performed in order to present the insights.


## Summary of Findings

In the exploration, I found that there was a strong relationship between the
borrower APR (Annual Percentage Rates) of a loan and its original amount, with 
modifying effects from the prosper rating given to the loan. The borrower APR of a 
loan and its original  amount are negatively correlated with each other. The 
prosper rating is positively correlated to loan original amount and negatively 
correlated to the borrower APR.

I found a somewhat surprising result when I looked at the effect of prosper
rating on a plot of loan original amount vs borrower APR. The relaionship 
converted gradually from a negative to a slightly positive one from 'HR' (lowest 
rating) to 'AA' (highest rating). This could be so as to encourage people to take 
big loans but when the amount is large enough, they are penalized with increased 
borrower ARP.

Outside of the main variables of interest, I also found that the loan original 
amount is positively correlated with term and stated_monthly_income. This indicates 
that applicants who make more money per month end to take out a bigger loan. 
However, this is not always the case explaining the weak correlation. And when 
someone takes out a bigger loan, it will take them some time to pay it back. Hence, 
the positive correlation. However, this is not always true.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the loan original 
amount and prosper rating and leave out most of the intermediate derivations. 
I start by introducing the borrower APR variable, followed by the patterns in 
loan original amount and prosper score distribution.

Then I introduce the scatter plot showing the relationship between loan originaion 
amount and borrower APR. Finally, I depict the effect of prosper rating on the 
scatter plot between the above two mentioned features.