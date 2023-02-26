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
