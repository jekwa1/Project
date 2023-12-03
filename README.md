This dataset has been forked from covid19-public, in particular from  MoH-Malaysia/covid19-public. 
It is open data on COVID-19 cases in Malaysia.

## File naming convention

| Filename | Naming convention | Update frequency |
| :--- | :---: | :---: |
| cases_malaysia.csv | Static name | Daily by 2359 (for T-0) |
| deaths_malaysia.csv | Static name | Daily by 2359 (for T-0) |
| icu.csv | Static name |  Daily by 2359 (for T-0) |

## Files extracted 
cases_malaysia.csv: Daily recorded COVID-19 cases at country level.

icu.csv: Capacity and utilisation of intensive care unit (ICU) beds.

deaths_malaysia.csv: Daily deaths due to COVID-19 at country level.

## Metadata for Variables
## Cases and Testing

1) `date`: yyyy-mm-dd format; data correct as of 1200hrs on that date
2) `cases_new`: cases reported in the 24h since the last report
3)  `deaths_new`: deaths due to COVID-19 based on **date reported to public**
4)  `icu_x`: total number of individuals in category `x` under intensive care, where `x` can be  suspected/probable, COVID-19 positive, or non-COVID; this is a stock variable


