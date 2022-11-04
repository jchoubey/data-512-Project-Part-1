# data-512-Project-Part-1
This repo holds the Part 1 Analysis of the Project in Data 512 Class

### Project Objective: 
During this Course Project, we are going to begin taking a look at some of the social aspects of the pandemic by conducting a human centered data science analysis of some available COVID-19 data. In Part 1- Common Analysis, we will analyze data for Multnomah County, Oregon of the United States.

### Research Question: 
How did masking policies change the progression of confirmed COVID-19 cases from February 1, 2020 through October 1, 2021?

### Data:

The common analysis research question will require several different datasets. We will need:
1. The RAW_us_confirmed_cases.csv file from the Kaggle repository of [John Hopkins University COVID-19 data](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university). This data is updated daily. We can use any revision of this dataset posted after October 1, 2022.
2. The CDC dataset of [masking mandates by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i). Note that the CDC stopped collecting this policy information in September 2021.
3. The New York Times [mask compliance survey data](https://github.com/nytimes/covid-19-data/tree/master/mask-use).

The majority of this data is by US County by Day. The mask compliance is a single shot estimator that gives you a compliance estimate for every County in the US. You should carefully review the data descriptions that accompany these datasets. They each have some interesting caveats. As well, some of them are explicit with regard to the way you should interpret missing data.


### Libraries Used:

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Scipy
