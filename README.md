# Causes-of-Deaths-across-the-World
![](https://github.com/blessingekwere/Causes-of-Deaths-across-the-World/blob/main/download.jpg)
###### Photo Source: Google

## Introduction

The Causes of Death dataset is a comprehensive collection of mortality data for different countries in the world. It contains information on deaths from all causes for the past several decades. The dataset is a valuable resource for researchers, policymakers, and public health professionals, providing insights into trends and patterns in mortality rates and causes of death over time. 
In this analysis project, we will explore the Causes of Death dataset and investigate the leading causes of death in different countries. By examining the data, we can gain a better understanding of the major health issues affecting the different countries and identify areas where interventions may be needed to improve public health outcomes.
We will start by cleaning and preprocessing the data, including checking for missing values and ensuring consistency across variables. Next, we will perform exploratory data analysis to identify trends and patterns in mortality rates and causes of death over time, as well as examining differences across countries.
Overall, this analysis project aims to provide a comprehensive picture of the causes of death in the world and identify areas where interventions may be needed to improve public health outcomes and reduce mortality rates.

## Problem Statement
Despite advancements in medicine and healthcare, mortality rates remain a crucial public health issue globally. Understanding the leading causes of death is critical for identifying and addressing public health concerns. In this project, we aim to analyze a dataset containing information on causes of deaths in a specific population over a given period. The goal is to identify the most significant causes of death and their trends over time. We also aim to investigate the impact of various demographic factors, such as age, gender, and location, on mortality rates and causes of death. This analysis will provide insights into the key factors contributing to mortality in the population, enabling public health policymakers to make informed decisions and implement targeted interventions to reduce mortality rates and improve overall population health.

## Tool Used
The tool used for this analysis was Microsoft Excel


## Skills Demonstrated
* Data cleaning and manipulation
* Sorting and filtering
* PivotTables
* Charts and graphs
* Formulas and functions
* Conditional formatting


## Data Sourcing
The data was downloaded from Kaggle. It came in two sheets; the difference was that the columns were pivoted on one and the other was it was not. I dropped the one that had unpivoted columns and decided to work with the other. The dataset had 6 columns and 201763 rows; it covers a period of twenty-nine years (1990-2019). You can find the link to the original dataset [here](https://www.kaggle.com/datasets/ivanchvez/causes-of-death-our-world-in-data).

## Data Transformation
To begin the data transformation process, the first thing that I did was to rearrange the columns to the way I want

* I renamed the entity column to ‘Country’ and code column to ‘Country Code’

* I dropped the column that had ‘deaths’, ‘all ages’ and ‘all sexes’ since I would not be needing it for my analysis.

* The death number column had 11,187 blank cells which I had to replace with zero(0)

* I replaced the cells in the country code column such as America, East Timor, Macau and Zaire with their correct country codes.

* Some cells which had countries like Zaire, East Timor and America were replaced their correct and updated names. Zaira was changed to Democratic Republic of Congo, East-Timor was replaced with Timor-Leste and America was changed to United States of America.

You can access the cleaned excel sheet [here](https://docs.google.com/spreadsheets/d/1xkPhxuWKwI2tOI8XGtU-VCU7O3iBwmgg/edit?usp=sharing&ouid=101168326616437085538&rtpof=true&sd=true)

## Analysis
* The total number of years was 29
* The total number of death causes was 33
* The total number of recorded deaths was 1,632,796,256
* The total number of countries was 212

![](https://github.com/blessingekwere/Causes-of-Deaths-across-the-World/blob/main/Total%20Deaths%20By%20Year.png)
*	The total number of deaths kept increasing over the years with 2019 recording the highest number with a total of 61,186,199 deaths.

![](https://github.com/blessingekwere/Causes-of-Deaths-across-the-World/blob/main/Top%205%20causes%20of%20deaths%20in%20Nigeria.png)
*	The most common cause of death in Nigeria was diarrheal disease causing a total of 7,449,328.

![](https://github.com/blessingekwere/Causes-of-Deaths-across-the-World/blob/main/Death%20causes%20by%20death%20count.png)
*	The most common cause of deaths across the world was cardiovascular diseases with a total of 500,783,563

![](https://github.com/blessingekwere/Causes-of-Deaths-across-the-World/blob/main/Top%2010%20countries%20by%20deaths.png)
*	China recorded the highest number of deaths with a total of 265,409,565 deaths

![](https://github.com/blessingekwere/Causes-of-Deaths-across-the-World/blob/main/Total%20deaths%20in%20nigeria%20by%20year.png)
*	Year 2017 recorded the highest number of deaths in Nigeria with 1,580,894 deaths.

![](https://github.com/blessingekwere/Causes-of-Deaths-across-the-World/blob/main/Bottom%205%20causes%20of%20deaths%20in%20Nigeria.png)
*	Execution caused the least number of deaths in Nigeria with a death count of 7

## Visualization
![](https://github.com/blessingekwere/Causes-of-Deaths-across-the-World/blob/main/1_page-0001%20(2).jpg)

## Conclusion and Recommendation
Based on the findings from the causes of deaths data analysis project, it is evident that the total number of deaths has been increasing over the years, with 2019 recording the highest number of deaths. The most common cause of death in Nigeria was diarrheal disease, while cardiovascular diseases were the most common cause of deaths across the world.

It is recommended that measures should be put in place to reduce the incidence of diarrheal diseases in Nigeria through improved sanitation, access to clean water, and awareness campaigns. Additionally, efforts should be made to promote healthy lifestyles and prevent cardiovascular diseases globally.

The fact that China recorded the highest number of deaths suggests the need for further research into the specific causes and factors contributing to the high mortality rate in the country.

Furthermore, the data shows that executions caused the least number of deaths in Nigeria. This could indicate that the country's legal system is effective in reducing the incidence of capital punishment. It is recommended that Nigeria continue to monitor and review its legal system to ensure that it complies with human rights standards.

Overall, this analysis provides useful insights into the causes of deaths in Nigeria and globally, and the findings can inform policy decisions aimed at improving health outcomes and reducing mortality rates.

Thank You for going through this documentation.

Your recommendations and suggestions will be highly appreciated.

See you next time:blush:



