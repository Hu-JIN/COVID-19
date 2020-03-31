COVID-19 analysis

# Data

Forked from https://github.com/CSSEGISandData/COVID-19:
./csse_covid_19_data, ./archived_data, ./who_covid_19_situation_reports

Collected from various sources:
./data
See ./data/20200330_data_source.xlsx for data sources.

# Analysis

Data for number of COVID-19 tests performed by different countries is limited. We therefore first did an analysis not including number of tests performed. For this analysis, see:
./analysis/20200331

Manually curated data for number of COVID-19 tests is available at https://ourworldindata.org/coronavirus-testing-source-data. It is outdated and includes only some countries. We incorporated this data and did the analysis again. For this analysis, see:
./analysis/20200330
Note that in this analysis, the covariate DaysSince100 (days since confirmed cases >= 100) is not included in the analysis.
