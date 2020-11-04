# MTA-Ridership-Impact-of-COVID-19
## How COVID-19 Effected MTA Usage in NYC

  I am a New Yorker, living in Queens, who takes the MTA daily; well, I used to until the quarentines started. One thing I noticed the times I did take the subway was that it is alot less crowded than it usually is. That had me thinking, was it just me or was this the actual case. That is what lead me to do this project and find out if it was all in my head or this was a reality. In this analysis, I perform some Exploritory Data Analysis (EDA) on turnstile data from 2019 and 2020, as well COVID-19 data for the city of New York. I perform a few Hypothesis Tests to see if there was a difference in turnstile usage and how coronavirus cases and tests given correlate with median household income levels. My goal is to find out if COVID-19 had an effect on MTA usage and to find out what nieghborhoods did it effect more.
  
# About the Data
I retreaved the datasets from the following places:
* Turnstile Datasets
  * 2019: https://data.ny.gov/Transportation/Turnstile-Usage-Data-2019/xfn5-qji9
  * 2020: https://data.ny.gov/Transportation/Turnstile-Usage-Data-2020/py8k-a8wg
* COVID-19 Datasets
  * https://github.com/nychealth/coronavirus-data 
  * https://www1.nyc.gov/site/doh/covid/covid-19-data.page
  * https://data.cityofnewyork.us/browse?category=Health&q=covid
* Median Income Dataset:
  * https://pypi.org/project/uszipcode/ 

# Background Information

Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus. Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment.
* The first laboratory-confirmed case of COVID-19 in the United States was confirmed on January 20, 2020, and reported to CDC on January 22, 2020.
* As of September 30, 2020, there has been 8.93M COVID-19 cases and 228K COVID-19 deaths across the United States.
* The NYC MTA subway service has been and still is suspended from 1 a.m. to 5 a.m. for disinfection of stations and trains.
* It is and has been a requirement by law to wear a mask while on MTA subways.

# Economic Impact of COVID-19 for New Yorkers
***NYC***: Coronavirus likely to cost NYC over $10 billion in lost revenue.

***MTA***: The New York MTA projects total coronavirus losses between $7 - $8.5 billion. There are talks about a possible 40% cut in MTA services.

***Individual***: NYC unemployment rate is 16%, twice as high as the rest of the country.

# Exploratory Data Analysis
Before I could run any hypothesis tests to try and help answer the questions I had, I first had to clean and make sense of the turnstile data from the MTA. The first thing I wanted to know before proceeding any further was, is there a difference in turnstile usage between 2019 and 2020. Since the data for the coronavirus didn't start until March 1, 2020. I decided to compare the timeframes of March 1st thru September 30th, for both 2019 and 2020. After cleaning the turnstile data for daily usuage across the city, I found the following results:


