This repository contains data and code related to a project on zone entries in the NHL.

## Code

`data` folder contains:
- proprietary tracking data originating from Stathletes
- points dataset containing goal rates from Evolving-Hockey
- RAPM dataset containing RAPM metrics from Evolving-Hockey

## Data

`code` folder contains:
- `data_prep.R` script that readies dataset for analysis
- `analysis.R` script that contains exploratory data analysis and estimates causal effects due to different zone entries using propensity score matching and BART
- `nhl-rink.R` script that contains code to generate the spatial plot included in script above
- `Summary.Rmd` script that generates a short summary of the project

## Manuscripts

This folder contains important causal inference and NHL literature.

## Figs

This folder contains important figures and results.

## Presentation

This folder contains the poster presented at the 2019 New England Symposium on Statistics in Sports, Boston, MA.