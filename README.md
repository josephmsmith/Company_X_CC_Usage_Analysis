# Company X Credit Card Usage Analysis
Data given in CSV, EDA completed in Python(Pandas), exported to PostgreSQL, and visualized in Tableau. 

## Introduction
Company X offers its customers the ability to accept payments by card within the app. 
Each time Company X processes a payment it earns revenue, which makes increasing the adoption of card payments by customers a key driver of financial performance. 
Company X is considering a new initiative to grow their card payments business. 
The solution provided outlines targeting existing organizations who have low credit card payment adoption.

## Purpose 
What organizations will be good candidates for a credit card usage campaign for the strategy and operations team and why? 
The goal is to increase credit card usage since adoption is a key driver of Company X long-term financial performance. 

## About the Data
The data source being used for this presentation is the “BizOps - Fintech Data Set” provided by Company X. The data set gives general info about organizational specifications, like enrollment date, industry, size, and plan as well as some financial insights like expected life value at enrollment, total paid gross merchandise value in the last 30 days, and total credit card GMV. 

Exploratory Data Analysis:
1000 rows x 15 columns. Dates: 03/2015-03/2021. HVAC has the highest organization count, company size has a positive skew (1 - 6 employees most frequent), small tier plan is the most popular, monthly plan the most popular, (CA, FL, TX) contain highest number of organizations, expected lifetime value has positive skew, and 39 companies have 100% CC_USAGE.

Limitations: 
1. 1000 rows of data
2. Data is limited to 2016 - 2021
3. No profit data
4. No remaining org value.

Assumptions: 
1. Campaign will target the highest-value customers with the lowest credit card utilization

## Anaysis
KPIs: Customer segmentation: industry, plan tier, plan term and geography. Analyze segment behavior against  payment method usage, enrollment date, and expected lifetime value. 
Starting questions for analysis:  
1. What segments of organizations have the lowest credit usage? 38.7% is the avg CC_USAGE
2. What segments under credit usage average have the highest lifetime expected value?
3. What industries have the highest CC_GMV present? Indicator of long term potential.
4. How has CC usage/GMV increased or decreased over time? How can we forecast?
5. Are there any Pareto relationships? Any other theories?

## Conclusion
Identified 59 potential organizations. Next steps should include an analysis further filtering this group with information such as lifetime_value_left and profit_margin. Subsequent analysis on Plumbing. 

## Resources
[Housecall Pro](https://www.housecallpro.com/)

[PNAS](https://www.pnas.org/doi/10.1073/pnas.2006991117#:~:text=Across%20the%20full%20sample%2C%2043,being%20less%20of%20a%20factor.)

[US Home Service Market Size](https://www.verifiedmarketresearch.com/product/us-home-service-market/)

[Credit Card Processing](https://www.merchantmaverick.com/the-complete-guide-to-credit-card-processing-rates-and-fees/)
