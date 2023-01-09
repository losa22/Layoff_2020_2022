# Layoff_2020_2022
Global Layoff from 2020 to 2022 -  EDA analysis

# PROJECT PURPOSE

The analysis wants to __explore globally the companies registering the highest layoff__, which country was most affected and if there was a pattern on the redundancy process over the years 2020-2022.

* Is there a correlation between the financial stage of the company and layoff?

Two Data cleaning method were used and compared as experiment for this study, the goal is to show whether the deletion of nan values could be complemented by a different approach if it should have been excluded a prior.


# NOTE ON CLEANING METHOD 

The project adopt __two different method of cleaning data__, as explained in __‘eda layodd-backup’__ file.

The correspective exploration was carried mainly in __‘layoff_capstone - imputation cleaning method’__ jupyter notebook.

The second brief analysis and correlated chars can be found inside the file __‘layoff_capstone- drop nan cleaning  data method’__, but all the chars have been included in the eda report

1501  Companies,  992 of those are  from us = 65.5% of the df.



## LAYOFF TREND OVER TIME

We found that in this dataset the data related to the time frame 2021 are missing. Overall, we distinguish a significant spike in layoff at the beginning of 2020, corresponding with the first lockdown announcement. The situation stabilised after May 2020.  Probably it took an uphill turn during the year 2021 but unfortunately, we have no record of it.

During 2022 we didn’t assist to similar figures, but another layoff trend took off during the 2022 summer and before the Christmas festivity, headlighting the theory that the Inflation and an economic crisis is starting


## WORLD DATA

Most of the companies have moderate loss of workforce: under 50 people
Most of the companies lost 20% of the workforce
On average, a company would expect to lose less than 0.3 workforce (<30%)  

Amazon, Meta and Cisco registered the highest layoff.
Layoff Classification by Company:
Meta – Amazon – Uber – Booking – Cisco -Peloton – Better.com – Carvana – Teitter - Bytedance

There is not a direct strong correlation between Financial Stage and Percentage-loss of a company, however, we don't have many samples of big companies.

Companies with the highest financial funds survived.

For some companies at the beginning of the financial stage bankrupt (loosing 100% workforce

Series H and Series J were confirmed to be the Financial Stages with the highest cash available.
Companies with stage:   IPO.      Serie J.     Serie H,  were the most affected from layoff.


Finance and Retail were  the most affected industries
Followed by Healthcare, Food and Transportation

Most of the people in our data sample lost their jobs in United States (however, we know that we had far more data related to such Location) and India, which significantly registered the highest layoff.


## US DATA 

* There are  1501 Companies in the dataset and 992 are from us , equal to 65.5% of the whole data. It is therefore a deeper analysis were carried on such Country.


* In US the LOCATIONS most affected result to be:
1. SF Bay Area
2. New York city
3.  Seattle
4. Boston
5. Los Angeles

In US  the INDUSTRIES most affected result to be:
1. Consumer
2. Retail
3 Infrastructure
4. Transportation
5. Real Estate
    
The sector less at risk were:
1. Aerospace
2. HR
3. Legal
4. Data

Companies in IPO financial stage were the most at risk.

