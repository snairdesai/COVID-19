The data folder contains all the raw, temporary, and final data files used for analysis (as well as files which have been pulled, but not yet integrated into the analysis). For a more detailed explanation of the data and its usage, see the "Data" and "Empirical Specification" sections of the [NBER Working Paper](https://www.nber.org/papers/w27185).

**Raw Data**

1. The [spatial_data](http://www.cepii.fr/cepii/en/bdd_modele/bdd.asp) folder contains distance and locational data on the sample. Note this data is not incorporated in the first round of analysis.
2. [Country_Coordinates.csv](https://developers.google.com/public-data/docs/canonical/countries_csv) contains centroid coordinates for each nation in the sample.
3. [GNI.csv](https://data.worldbank.org/indicator/NY.GNP.PCAP.CD?view=chart) controls for GNI per capita (calculated using the Atlas Method).
4. [Government_Responses.csv](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker) contains policy data pulled from Oxford. A more detailed README file is available in the relevant folder.
5. [ICD_Deaths_Final.csv](https://www.who.int/classifications/icd/icdonlineversions/en/) pulls information on prior deaths from diseases (endocrine, high blood pressure, and respiratory) aggregated across 2015-2018.
6. [UN_Population_Data](https://population.un.org/wpp/Download/Standard/Population/) contains the country population data used to construct mortality rates.
7. [applemobilitytrends-2020-04-27.csv](https://www.apple.com/covid19/mobility) details mobility data provided by Apple, which captures changes in walking, driving, and transit levels across nations.
8. [arrivals.csv](https://data.worldbank.org/indicator/ST.INT.ARVL) controls for international tourist arrivals in the l.y.a. (2018).
9. [cellular.csv](https://data.worldbank.org/indicator/IT.CEL.SETS.P2?start=1960) controls for the number of cellular subscriptions by nation.
10. The countryContinent.csv is not used in our analysis, but may be used to generate subplots in the visualizations (i.e. by continent or sub-region, rather than by nation).
11. The democracy.csv file aggregates democracy data from [Freedom House](https://freedomhouse.org/countries/freedom-world/scores) and the [Economist Intelligence Unit](https://www.eiu.com/topic/democracy-index?&zid=democracyindex2019&utm_source=blog&utm_medium=blog&utm_name=democracyindex2019&utm_term=democracyindex2019&utm_content=top_link).
12. [departures.csv](https://data.worldbank.org/indicator/ST.INT.DPRT) controls for international tourist departures in the l.y.a. (2018).
13. Both global_preferences_survey_country.dta and global_preferences_survey_individual.dta were pulled from the [Global Preferences Survey](https://www.briq-institute.org/global-preferences/downloads). In our cross-sectional analysis, these datasets (very roughly) attempt to control for differing levels of patience; trust; and altriusm across nations.
14. [govt.csv](https://info.worldbank.org/governance/wgi/Home/Documents) reports indicators related to nations' political stability, government effectiveness and accountability, rule of law, etc.
15. [health_pc.csv](https://data.worldbank.org/indicator/SH.XPD.CHEX.PC.CD?view=chart) accounts for previous health expenditures in the l.y.a. (2017).
16. [military.csv](https://correlatesofwar.org/data-sets/national-material-capabilities) captures measures of state capacity and force, including military personnel, military expenditures, iron and steel production, and an index of national capabilities. Note, the l.y.a. for this data is 2012.
17. 

**Temporary Data**


**Final Data**
