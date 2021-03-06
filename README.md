# Loan-Data-from-Prosper
Communicate Data Findings on Loan Data from Prosper

## Dataset

The data consisted of approximately 113,937 loans with 81 variables on each loan. This too much data to be analyzed which need to be reduction to focus only the affected factors on the estimated return. Select only data after July 2009 to detect Estimated Return without null values to get a new size of data which contains 84,964 loans and 14 factor.


## Summary of Findings

In the exploration, I found that there was an approximately linear relationship was observed when Estimated Return was plotted with BorrowerAPR. And when plotted Estimated Return with different levels of income ranges to find a
somewhat surprising result initially that Estimated Return was much higher for who Not Employed or have low income than who have larger income, that may mean that low income make people more interest getting loan to start their own business.

And for Loan Original Amount, when it was plotted with the Loan Status, current loans in data set have the larget original amount about 10K and the count mendian of chargedoff loans have the smallest which considerd amounts below 5K. And outside the main variables, Expected relationship between the Loans Amount and Monthly Payment identified the strong correlation between both of them: the larger amount of loan, the higher monthly payment.



## Key Insights for Presentation

For the presentation, I focused on just the influence factors the Estimated Return. Starting by introducing the
Estimated Return variable, followed by the pattern in Loan Original Amount distribution, then plot Estimated Return and BorrowerAPR scatterplot and violinplot Estimated Return with different levels of income ranges.

After showing the relations between loan Term levels, Income Ranges and Loan Status I decided to use the pointplot to show that the Estimated Return from the completed loans was higher for those had the loan over 60 and the same appeared for the chargedoff loans. For the current loans, the estimated return is Convergent for both terms 60 and 36. For loans that their final payment in progress gave lower estimated return than the completed and chargedoff loans. So there indeed is a positive effect of increased the loan term on estimated return.

Looking back on the point plots, it seem like there's an inverse relationship between Loan Amount and the Estimated Return which appeared when dicoved the income range: the higher income range the higher loan amount and the lower Estimated. Which mean that the lower amount of loan the higher estimated return will get.
