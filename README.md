# data-512-Project-Repository
This repo holds the Project related documents in the Data 512: Human Centered Data Science Class. It is inclusive of all Part 1-4 of the project.

### Project Objective: 
During this Course Project, we are going to begin taking a look at some of the social aspects of the pandemic by conducting a human centered data science analysis of some available COVID-19 data. In Part 1- Common Analysis, we will analyze data for Multnomah County, Oregon of the United States. Progressing to Part 2-4, the objective of this project is to assess the impact of covid-19 cases on the real estate and housing market in Multnomah County, OR. The duration of this analysis will include a study between 2019-2021 to accommodate for the effect of time before and after a covid-19 surge.

The real estate and housing market is subject to many ups and downs - and largely depends on the standing of customers (humans) either through political amendments, the economy, the spread of diseases (in this case covid-19), or many other human-driven factors. Not just that, the relative fluctuations in real estate are in turn a cause of stir among the general public - and not just people of one socio-economic class, but from every class. Through this study, I aim to assess any connection between the rise/fall of confirmed covid-19 cases and the subsequent variation in the real estate market (housing prices in particular). While a general trend is a base observation for housing prices, I hope to detect any specific/unusual fluctuations that can be connected to the pandemic in a certain way.


### Research Questions:

- For Part 1, we look into how did masking policies change the progression of confirmed COVID-19 cases from February 1, 2020 through October 1, 2021?
- For Part 2-4, we look into the following research questions:
    ➔	Was there a statistically significant difference between housing prices in 2020 and 2021 (during the pandemic) as opposed to 2019 (prior pandemic) in Multnomah County, OR? 
➔	Did the number of confirmed cases have a statistically significant impact on the housing prices between 2020-2021 in Multnomah County, OR?

For a thorough and complete inference, there are many considerations that must be looked at, including political and economic effects, covid-19 severity (not just confirmed cases, but deaths and hospitalizations as well), etc. Due to the lack of availability of such detailed data sources, appropriate assumptions have been made and highlighted throughout the analysis (including the limitations section).


### Data:

The Part 1 Collaborative Analysis research question will require several different datasets. We will need:
1. The RAW_us_confirmed_cases.csv file from the Kaggle repository of [John Hopkins University COVID-19 data](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university). This data is updated daily. We can use any revision of this dataset posted after October 1, 2022.
2. The CDC dataset of [masking mandates by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i). Note that the CDC stopped collecting this policy information in September 2021.
3. The New York Times [mask compliance survey data](https://github.com/nytimes/covid-19-data/tree/master/mask-use).

The majority of this data is by US County by Day. The mask compliance is a single shot estimator that gives you a compliance estimate for every County in the US. You should carefully review the data descriptions that accompany these datasets. They each have some interesting caveats. As well, some of them are explicit with regard to the way you should interpret missing data.

Proceeding to Part 2-4, we will also work with Housing Data procured from Redfin:
4. The weekly housing market data from Redfin: [housing data](https://redfin-public-data.s3-us-west-2.amazonaws.com/redfin_covid19/weekly_housing_market_data_most_recent.tsv)
5. Interest Rate (fixed for 30 years): [interest rate data](https://fred.stlouisfed.org/series/MORTGAGE30US)


### Libraries Used:

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Scipy
