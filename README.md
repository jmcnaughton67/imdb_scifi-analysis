# imdb_scifi-analysis
IMDB Sci-Fi Movies Analysis in the context of Public Health
Popcorn and Pathogens: A Critical Analysis of Health Representation in Science Fiction Films

**Python code used for a report for SCOM2003 - Science and Popular Fiction at the ANU**

Code enables the following:
- webscrape IMDB data set to obtain list of top 1000 science fiction films, storing important data for each in pandas web frame
- webscrape synopsis data for each film using dummy user agent header and random sleep functions 
- data cleaning of the dataframe 
- analysis of the captured synopsis for each film to assess number of reference to health terminology relevant to the films plot
- sentimental analysis of the surrounding sentence of each disease reference to assess the sentiment polarity of the health term
- ingestion of comparative data frames obtained online and referenced in the report 
- comparative visualisations of the datasets for discussion in the report 

------

Datasets used:
- Google Trends Data Set (https://trends.google.com/trends/)
Key Terms Searched: ‘Muscle Disease’, ‘Respiratory Disease’, ‘Skin Disease’, ‘Neurological Disease’
Date of Data: 2022
Export Method: Exported as CSV

- Technology Patents Data Set:
Source: OECD - https://stats.oecd.org/Index.aspx?DataSetCode=PATS_IPC# 
Data Set Name: Patents by Technology or IPC Class
Export Method: Downloaded as CSV
Additional Comments: Consolidated the country list through the UI to only show global figures.

- Public Health Expenditure Data Set:
Source: OECD - https://ourworldindata.org/government-spending 
Date of Data: 2017
Data Set Name: Public Healthcare Spending as a Share of GDP for High Income Countries
Countries in Data Set: France, Italy, Sweden, Greece, Germany, Japan, Netherlands, United Kingdom, United States, Australia and Canada
Export Method: Downloaded as a CSV
Additional Comments: Countries totals as proportion of GDP were averaged into a single data series to represent all high income countries.

- Cancer Death Data Set:
Source: National Centre for Health Statistics (https://www.cdc.gov/nchs/data-visualization/mortality-trends/)
Date of Data: 1900-2018
Data Set Name: Leading Causes of Death: Age Adjusted Death Rate
Export Method: Downloaded CSV

------
