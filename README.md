<img src="https://github.com/ajayvighnesh/PRODIGY_DS_01/blob/main/DS_TASK 01.png"   >

# NET MIGRATION DYNAMICS: A GLOBAL OVERVIEW

## ANALYZING AND VISUALIZING GLOBAL NET MIGRATION TRENDS (2000-2023)
### PROBLEM DEFINITION
The aim of this project is to analyze global net migration trends over the period from 2000 to 2023, using data sourced from the World Bank. Net migration refers to the difference between the number of immigrants and emigrants for each country. Understanding these patterns can shed light on social, economic, and political factors affecting population dynamics. 

### OBJECTIVE
The project will focus on identifying key trends (inflows/outflows), visualizing migration patterns and highlighting potential factors influencing migration.

### DATASET
Dataset Overview
The dataset is formed by merging two World Bank datasets. One dataset contains net migration data, while the other includes region and income group classifications for each country. Net migration measures the difference between the number of immigrants and emigrants over a given period. A positive value indicates more people moving into the country than leaving, while a negative value suggests more people are leaving. The dataset spans from 2000 to 2023, covering over 200 countries, reflecting global population movements influenced by factors such as economic conditions, wars, and policy changes. The merging of these two datasets ensures that each country's migration trends can be analyzed not only in terms of raw net migration values but also in relation to their geographic region and income level classification.

Variables of the Dataset
The variables allow for a comprehensive analysis of migration trends over time and across different countries.

VARIABLE	DESCRIPTION
Country Name	The name of the country for which the data is collected
Country Code	A unique identifier for each country (ISO codes)
Region	The geographical region to which the country belongs
Income Group	The classification of countries based on income levels
Year	The year for which data is recorded, ranging from 2000 to 2023
Net Migration Value	The numerical value indicating the net migration for the given country and year
The World Bank's Net Migration dataset consists of both categorical and continuous variables:

VARIABLE TYPE	VARIABLE NAME	DESCRIPTION
Categorical	Country	The name of the country or region for which net migration data is reported
Categorical	Region	The geographical region to which the country belongs
Categorical	Income Group	The classification of countries based on income levels
Categorical	Year	The specific year of the net migration data
Continuous	Net Migration Rate	The net number of migrants per 1,000 population, indicating migration trends
Constants of the Dataset
Constants refer to elements that remain unchanged throughout the dataset. These constants help maintain the dataset's structure and standardize the measurement of net migration across all countries and time periods.

CONSTANT	DESCRIPTION
Indicator Name	Always "Net Migration" (constant across all countries and years)
Indicator Code	Always the same ("SM.POP.NETM")
