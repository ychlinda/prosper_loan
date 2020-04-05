# prosper_loan
## About the Dataset:
Prosper Loan dataset. Check out the details for this dataset [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000).

## Main findings:
> 1. Almost 70% of the loans are current, and over 20% are complete. Less than 10% are charged off, defaulted or past due.
> 2. The distribution of annual interest rate that borrowers incur looks roughly bimodal. There are a peak around 20% and the second peak around 35%. The majority of the rates fall in the range of 12.5% to 37%
> 3. There are large spikes in frequency at 5k, 10k, 15k and 20k/25k to a lesser extent. They probably represent the focal points as it is less likely for someone to ask for 14,999 compared to 15,000. Most loans are less than or equal to 25k
> 4. Interest Rate has a medium negative correlation with original amount, and a small negative correlation with the non-delinquency rate. Interest rate is more likely to be higher than smaller loans.
> 5. Interest rate has a negative relationship with Prosper score and income. It makes sense intuitively, as borrowing rate is lower for high-ranking loans (low risk) and individuals from high-income brackets. In general, interest rates are also higher for past-due, defaulted and charged off loans.
> 6. Original loan amount has a positive relationship with Prosper score and income. Interestingly, loans that are charged-off or defaulted tend to be small. This is worthy of further investigation with more data points.
> 7. Compared to the current loans, charged-off and defaulted loan are normally small and high interest bearing. Completed loans also tend to be small.
> 8. For USD5,000 and USD15,000 loans (the most popular on Prosper), borrower APRs are noticeably lower for high-rating loans. Nevertheless, APR may not decline further after income passes a certain theshold. In some cases, those in the income range of 100,000+ may incur a higher APR than those in the range of 50,000-74,999,with prosper score being equal.
> 9. The mean loan amount differentials across income range at a given prosper score play differently for 20% and 35% APR loans. Perhaps loans with 35% APR are deemed very risky and the impacts of income range and prosper score on loan amounts are therefore muted.


## Key Insights for Presentation

> 1.The distribution of annual interest rate that borrowers incur looks roughly bimodal. There are a peak around 20% and the second peak around 35%. 
> 2.Interest rate has a negative relationship with Prosper score and income. In general, interest rates are also higher for past-due, defaulted and charged off loans.
> 3.Compared to the current loans, charged-off and defaulted loan are normally small and high interest bearing. Completed loans also tend to be small.
> 4.For $5,000 and $15,000 loans (the most popular on Prosper), borrower APRs are noticeably lower for high-rating loans. Nevertheless, APR may not decline further after income range passes a certain theshold. In some cases, those in the income range of 100,000+ may incur a higher APR than those in the range of 50,000-74,999, with prosper score being equal.

## Sources:
>[Matplotlib documentation](https://matplotlib.org/3.2.1/api/_as_gen/matplotlib.pyplot.legend.htmlhttps://matplotlib.org/3.2.1/api/_as_gen/matplotlib.pyplot.legend.html)
>[Stackoverflow post: rotate label text in seaborn](https://stackoverflow.com/questions/26540035/rotate-label-text-in-seaborn-factorplot)
>[Stackoverflow post: show axe labels for each subplot](https://stackoverflow.com/questions/33377243/seaborn-pairgrid-show-axes-labels-for-each-subplot)
