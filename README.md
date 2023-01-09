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

# FINDINGS

#### LAYOFF TREND OVER TIME

* It wad found a significant spike in layoff at the beginning of 2020, corresponding with the first lockdown announcement. 
* The situation stabilised after May 2020. 
* During 2022 we didn’t assist to similar figures, but another layoff trend took off during the 2022 summer and before the Christmas festivity.


#### WORLD DATA

* __Most of the companies have moderate loss of workforce: under 50 people.__
* __Most of the companies lost 20% of the workforce.__
* __On average, a company would expect to lose less than 0.3 workforce (<30%)  __

* __Amazon, Meta and Cisco registered the highest layoff.__

* __There is not a direct strong correlation between Financial Stage and Percentage-loss of a company.__

* __Companies with the highest financial funds survived.__

* __For some companies at the beginning of the financial stage bankrupt (loosing 100% workforce.__

* __Series H and Series J were confirmed to be the Financial Stages with the highest cash available.__
* __Companies with stage:   IPO.      Serie J.     Serie H,  were the most affected from layoff.__


* __Finance and Retail were  the most affected industries__
* __Followed by Healthcare, Food and Transportation__

* __Most of the people in our data sample lost their jobs in United States .__


#### US DATA 

* __There are  1501 Companies in the dataset and 992 are from us , equal to 65.5% of the whole data. It is therefore a deeper analysis were carried on such Country.__


* __In US the LOCATIONS most affected result to be:__
  * 1. SF Bay Area
  *2. New York city
  *3.  Seattle
  *4. Boston
  *5. Los Angeles

* __In US  the INDUSTRIES most affected result to be:__
  *1. Consumer
  *2. Retail
  *3 Infrastructure
  *4. Transportation
  *5. Real Estate
    
* __The sector less at risk were:__
  *1. Aerospace
  *2. HR
  *3. Legal
****4. Data

* __Companies in IPO financial stage were the most at risk.__

