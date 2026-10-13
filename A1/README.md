#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St
**Source:** https://data.seattle.gov/Transportation/.../2z5v-ecg8 (pulled YYYY-MM-DD)
**License / terms of use:** Listed as Public Domain on the dataset's page. Published by the
Seattle Department of Transportation (attribution: City of Seattle).
The data is updated monthly, so a re-run may differ slightly if the records change.

## Questions I asked
- Q1: When is the trail busiest and quietest (average combined bike + pedestrian count per hour of day)?
- Q2: Do cyclists and pedestrians use the trail at different times of day?
- Q3: Is there evidence of commuting? (weekday vs. weekend hourly patterns)
- Q4: Do morning and evening flows go in opposite directions (north vs. south)?

## How to re-run
Open `A1.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).
The notebook pulls 2019 data directly from the Seattle open-data API.