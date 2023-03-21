# Prosper Loan Data
## by Tunmise Oluwadare


## Dataset

> The Prosper Loan dataset is a publicly available dataset containing information on loans facilitated through the online lending platform, Prosper. The dataset contains data on over 100,000 loans originated between 2006 and 2014. Each loan in the dataset includes information on the borrower's credit score, income, employment status, loan amount, loan status, and other relevant borrower and loan characteristics. The  exploration of these variables in the Prosper Loan Dataset can provide insights into the characteristics of borrowers and loans, which can help inform lending practices and investment decisions on the platform.

## Summary of Findings

> BorrowerAPR - BorrowerAPR initially looked unimodal with peak values just a little lower than 0.2 but on a closer inspection, it seems values between 0.3 and 0.4 have the highest occurence with a very distinct peak greater than 7000 but less than 8000

> IncomeRange - The distribution of IncomeRange shows that the most common income range is $25,000 to $49,999, followed by $50,000 to $74,999.

> ListingCategory - The visualization of ListingCategory shows that the most common loan purpose is debt consolidation, followed by home improvement and business loan aside the the 'not available' and 'others' option.

> CreditScore - The distribution of CreditScore shows that most borrowers have a credit score between 600 and 800, with a peak around 700 which is close to the median credit score in the US

> LoanTerm - There are three loan categories- 12-, 36- and 60- month loans. Most of the loans registered were for 36 months while the least popular category was the 12 months loan term

> BorrowerState - It can be concluded that this loan dataset is for US only and California has the highest number of borrowers followed by Texas and New York. It can be observed also that the top 4 countries with the highest loan listing are also the top 4 most populated states in the US.

> Occupation - Majority of the borrowers did not specify their occupation but instead selected 'others' as occupation. The most common occupation was 'professional'

> DebtToIncomeRatio - The Debt-to-Income distribution is right-skewed, meaning that the majority of borrowers have a DTI below the median. The median Debt-to-Income in the dataset is around 22%, indicating that the majority of borrowers have a manageable level of debt relative to their income

> EmploymentStatus - Most of the borrowers granted loan were employed. This makes sense because it would be easy for them to repay the funds borrowed. The documentation of employment is not clear enough because an employed person can either be working full time or part time. Also a Self-employed person is still employed! The data will be more concise if it were grouped in the following categories: Employed, Not Employed, Retired, Others and Not Available

> LoanOriginalAmount -  Notable amount borrowed fall between 4000 and 5000 dollars, 10000 and 20000 dollars. On a loagrithmic scale, amount of Loan Borrowed distribution is a unimodal distribution, with the majority of loans falling within the range of  4,000 𝑡𝑜 12,000. The median loan amount is around 10,000 𝑎𝑛𝑑 𝑡ℎ𝑒 𝑚𝑒𝑎𝑛 𝑙𝑜𝑎𝑛 𝑎𝑚𝑜𝑢𝑛𝑡 𝑖𝑠 𝑎𝑝𝑝𝑟𝑜𝑥𝑖𝑚𝑎𝑡𝑒𝑙𝑦 8,500. it was noticed that round figure loans (e.g 5000, 10,000, 15,000) have a higher peak compared to other amounts.

> BorrowerRate -The Borrower Rate Distribution has two peaks. The first between midpoint 10% and 20% and the second peak at a higher peak around 30%. Also the average Brorrower Rate is 19.2%

> Borrower's CreditScore and LoanOriginalAmount are positively correlated, meaning that borrowers with higher credit scores tend to receive larger loans.

> Relationship Between Borrower's APR and Amount of Loan Borrowed: We can see that as the loan amount increases, the distribution of Borrower's APR shifts towards higher rates. This suggests that borrowers who take out larger loans may be charged higher interest rates to compensate for the higher risk associated with larger loans. We can also see that there are some loan amounts, such as $25,000 and $35,000, that have a higher concentration of loans with higher APRs compared to other loan amounts

> Borrower APR vs. Borrower rate: The scatterplot shows a roughly linear relationship between Borrower APR and Borrower rate, which means that as the interest rate increases, the APR also increases. There is some variation in the data, with some loans having higher APRs than what would be expected based on the interest rate alone, and vice versa. The scatterplot can provide insights into the factors that influence the APR charged on loans. For example, lenders may charge higher fees on some loans, which would increase the APR above what would be expected based on the interest rate alone. Additionally, the risk level of the loan may also play a role in determining the APR. Higher-risk loans may require a higher interest rate and higher fees, which would result in a higher APR.

> Borrower's APR vs. Employment Status: Self-employed borrowers tend to have the highest APRs, followed by borrowers who are not employed. Employed and full-time employed borrowers tend to have lower APRs, with full-time employed borrowers having the lowest APRs. The relatiosnhip between Borrower's APR and employment status can provide insights for example, lenders may charge higher interest rates and fees to self-employed and unemployed borrowers to compensate for the higher risk associated with these borrowers. On the other hand, full-time employed borrowers may be seen as lower-risk borrowers, which may lead to lower interest rates and fees.

> Borrower's APR vs. Credit Score: it is observed that borrowers with lower credit scores tend to have higher APRs, and that this relationship becomes weaker for borrowers with higher credit scores.

> Boxplot of Borrower's APR vs. Loan Term: The median APR tends to be lower for longer loan terms, while the IQR tends to be wider for shorter loan terms. We may also observe that the range of borrower APR is wider for longer loan terms, which suggests that borrowers with longer loan terms may be subject to a wider range of APRs


> Borrower's APR vs. Debit-to-Income Ratio: One key insight from this plot is that there is a wide range of APRs for borrowers across all DTI ratios. However, we can observe that there is a strong concentration of borrowers with a DTI ratio between 0 and 0.5, and that APRs for these borrowers tend to be lower overall. Another insight from this plot is that there are some borrowers with a relatively low DTI ratio but a high APR, and vice versa. These outliers may indicate other factors that are influencing the borrower's APR, such as credit score or loan amount.


> Borrower's APR vs. Income Range:One key insight from this plot is that borrowers with higher income ranges tend to have lower APRs, on average. For example, we may observe that the median APR tends to be lower for borrowers in the highest income range category, while the IQR tends to be wider for lower income range categories. This indicates that higher income borrowers may be offered more favorable lending terms than lower income borrowers.

> Relationship between Borrower's APR and Debt-to-Income Ratio and Borrower's Credit Score: Borrowers with lower credit scores have higher APRs compared to borrowers with higher credit scores, irrespective of their debt-to-income ratio. The trendline shows a positive correlation between debt-to-income ratio and APR, indicating that borrowers with higher debt-to-income ratios tend to have higher APRs. The color-coded data points show that borrowers with lower credit scores and higher debt-to-income ratios have the highest APRs, which indicates that these borrowers are considered high-risk by the lenders. Borrowers with credit scores above 700 have lower APRs compared to borrowers with credit scores below 700, regardless of their debt-to-income ratio. This suggests that credit score plays a significant role in determining the interest rate a borrower is offered. It also shows that borrowers with higher credit scores and lower debt-to-income ratios are more likely to get favorable interest rates.

> Employment status' and 'Borrower APR' with 'Borrower Rate: Borrowers who are not employed, retired, or have a part-time job have the highest APR and Borrower Rate, while those who are employed full-time have the lowest APR and Borrower Rate.
Borrowers who are self-employed have the highest range of APR and Borrower Rate, suggesting that being self-employed is considered a high-risk factor by the lenders.
The heatmap also shows that the highest range of APR and Borrower Rate is observed among the unemployed borrowers, indicating that being unemployed is a significant risk factor.
Borrowers who are employed but have an unknown employment status have a higher range of APR and Borrower Rate compared to other employed categories, suggesting that unknown employment status is also considered a high-risk factor by the lenders.
The heatmap highlights the importance of employment status in determining the interest rate a borrower is offered by the lender. It also shows that unemployed borrowers and self-employed borrowers are considered high-risk by the lenders, and therefore, have higher APR and Borrower Rate.



## Key Insights for Presentation

> Borrower's APR (Annual Percentage Rate) is an important metric in lending and borrowing. It represents the cost of borrowing, including interest and other fees, as an annualized percentage of the loan amount. so for the aim of the investigation was to to evaluate key Loan attributes that influence a Borrower's APR. 

> I start the presentation by introducing the importance of the main variable and a brief description of the dataset. Then i proceed to introduce the univariate variables of interest: Borrowers APR, EmploymentStatus, Debt-to-Income Ratio, LoanOriginalAmount, and BorrowerRate. The LoanOriginalAmount variable was plotted on a logarithmic scale.

> Then i introduced a heatmap showing the Interaction Between Borrower APR and Employment status with Borrower Rate.
During exploratory visualization i noticed an interaction between variables, i show this interaction with a heatmap of Variable Interaction Between Employment Status, Loan Original Amount and Debt-to-Income Ratio
