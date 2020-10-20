# How census tracts are grouped in Baltimore City based on individual income, household income, incarceration rate, and employment rate?

## Background

Nicholas Bogel-Burroughs and Lorraine Mirabella [published an article](baltimoresun.com/maryland/baltimore-city/bs-md-ci-choice-neighborhoods-hud-grant-20180719-story.html) on _The Baltimore Sun_ approximately two years ago about how Baltimore City's $889  million plan to transform "a swath of East Baltimore" was awarded $30 million federal grant, which included tearing down Perkins Homes public housing and moving residents to new housing. As they made new housing guaranteed, the city was optimistic about the redevelopment. As this is the right direction and had an optimistic start to "create the new mixed-income community" with projects that include "a new school, parks and services to help families and job-seekers, and officials", how are different neighborhoods grouped in Baltimore City? We will analyze the data from [Opportunity Atlas](https://www.opportunityatlas.org) to further look into how different parts of the city are grouped based on different population metrics.

## Business Questions

_How are census tracts in Baltimore City grouped based on individual income, household income, incarceration rate, and employment rate?

## Data Question - Open Data

We'll use open data from one source:

- [Opportunity Atlas](https://www.opportunityatlas.org): We will look into 4 different population metrics for a cluster analysis.

    i. Individual Income: Average annual individual income
    
    ii. Household Income: Average household income for children
    
    iii. Incarceration Rate: Fraction of who grew up in this area who were in prison or jail
    
    iv. Employment Rate: Fraction of who grew up in this area have positive wage earnings

## Data Question - Metrics

We will use Microsoft Excel to answer:

- __How are different tracts clustered based on the four variables?__ Applying Excel Solver operations for a cluster analysis on a database that is constructed with variable z-scores, and cluster categories. 

## Data Answer

### How are different tracts clustered based on the four different population metrics?

![alt_text](https://github.com/schoi74/how-census-tracts-are-grouped-based-on-population-metrics/blob/main/cluster%20analysis%200.png)

__Anchor__ 1 is a cluster of _slightly greater_ individual income, _slightly greater_ household income, _less than average_ incarceration rate, and _greater_ employment rate

__Anchor 2__ is a cluster of _less than average_ individual income, _less than average_ household income, _slightly greater_ incarceration rate, and _less than average_ employment rate

__Anchor 3__ is a cluster of _one standard deviation less than average_ individual income, _one standard deviation less than average_ household income, _more than one standard deviation greater incarceration rate, and way less than average_ employment rate.

__Anchor 4__ is a cluster of _more than two standard deviations greater_ individual income, _slightly less than two standard deviations greater_ household income, _one and a half standard deviations less than average_ incarceration rate, and _slightly more than one standard deviation greater_ employment rate.

![alt_text]()

- __Anchor #1



## Summary

## Step-by-Step Excel Analysis
