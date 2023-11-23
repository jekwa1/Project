Open data on COVID-19 in Malaysia
The scope and granularity of data in this repo will evolve over time.

Documentation and data descriptions contained within subfolders.
Submit pull requests to share your work for the community or request more data.
All data is correct as of 2359 of date, unless stated otherwise.

Cases and Testing
cases_malaysia.csv: Daily recorded COVID-19 cases at country level.
cases_state.csv: Daily recorded COVID-19 cases at state level.
clusters.csv: Exhaustive list of announced clusters with relevant epidemiological datapoints.
tests_malaysia.csv: Daily tests (note: not necessarily unique individuals) by type at country level.
tests_state.csv: Daily tests (note: not necessarily unique individuals) by type at state level.
Healthcare
pkrc.csv: Flow of patients to/out of Covid-19 Quarantine and Treatment Centres (PKRC), with capacity and utilisation.
hospital.csv: Flow of patients to/out of hospitals, with capacity and utilisation.
icu.csv: Capacity and utilisation of intensive care unit (ICU) beds.
Deaths
deaths_malaysia.csv: Daily deaths due to COVID-19 at country level.
deaths_state.csv: Daily deaths due to COVID-19 at state level.
Vaccinations
vax_malaysia.csv: Vaccinations (daily and cumulative, by dose type and brand) at country level.
vax_state.csv: Vaccinations (daily and cumulative, by dose type and brand) at state level.
vax_district.csv: Vaccinations (daily and cumulative, by dose type and brand) at district level.
vax_school.csv: Vaccination coverage for public schools.
vax_demog_age.csv': Vaccinations by age group, at district level.
vax_demog_age_children.csv': Vaccinations by age group with single-year granularity for individuals < 18yo, at district level.
vax_demog_sex.csv': Vaccinations by sex, at district level.
vax_demog_ethnicity.csv': Vaccinations by ethnicity, at district level.
vax_demog_nationality.csv': Vaccinations by nationality, at district level.
vax_demog_highrisk.csv': Vaccinations for special categories (healthcare workers, OKU, individuals with comorbidities) at district level.
Mobility and Contact Tracing
checkin_malaysia.csv: Daily checkins on MySejahtera at country level.
checkin_state.csv: Daily checkins on MySejahtera at state level.
checkin_malaysia_time.csv: Time distribution of daily checkins on MySejahtera at country level.
trace_malaysia.csv: Daily casual contacts traced and hotspots identified by HIDE, at country level.
Static data
population.csv (last updated from DOSM 2020 census, as published in 2022):
idxs: integer coding for states (employed in cases linelist, cluster file, and school vax file)
pop: total population (all other columns are subset of pop)
pop_18: population aged 18+
pop_60: population aged 60+, also a subset of pop_18
pop_12: population aged 12-17
pop_5: population aged 5-11
Static data will remain unchanged unless there is an update from the source, e.g. if DOSM makes an update to population estimates. We provide this data here not to supersede the source, but rather to be transparent about the data we use to compute key statistics e.g. the % of the population that is vaccinated. We also hope this ensures synchronisation (across various independent analysts) of key statistics.
