This dataset has been forked from covid19-public, in particular from  MoH-Malaysia/covid19-public. 
It is open data on COVID-19 cases in Malaysia.

## File naming convention

| Filename | Naming convention | Update frequency |
| :--- | :---: | :---: |
| cases_malaysia.csv | Static name | Daily by 2359 (for T-0) |
| deaths_malaysia.csv | Static name | Daily by 2359 (for T-0) |
| icu.csv | Static name |  Daily by 2359 (for T-0) |
| seven_days_mean_variant.csv | Static name | 7 day average |
| my_covid_variant.csv | Static name | Daily 

## Files extracted 
cases_malaysia.csv: Daily recorded COVID-19 cases at country level.

icu.csv: Capacity and utilisation of intensive care unit (ICU) beds.

deaths_malaysia.csv: Daily deaths due to COVID-19 at country level.

## Metadata for Variables
## my_covid_variant.csv
1) `date`: yyyy-mm-dd format; data correct as of 1200hrs on that date

2) `cases_new`: cases reported in the 24h since the last report

3) 'cases_x_y' : average number of cases reported between the ages of x and y; eg 0 and 4

4)  `deaths_new`: deaths due to COVID-19 based on **date reported to public**

5)  `icu_x`: total number of individuals in category `x` under intensive care, where `x` can be  suspected/probable, COVID-19 positive, or non-COVID; this is a stock variable

6)  'prominent_variant':  Types of prominent COVID-19 variant in Malaysia
## seven_days_mean_variant.csv

1) 'date' : yyyy-mm-dd format; intervals of 7 days
   
2) 'cases_new' : average number of cases reported in that particular week
   
3) 'cases_x_y' : average number of cases reported between the ages of x and y; eg 0 and 4
   
4) deaths_new: average number of deaths reported in that particular week
   
5) icu_covid': average number of individuals under intensive care that are Covid-19 positive

6) 'prominent_variant':  Types of prominent COVID-19 variant in Malaysia

