# gidden_ar6_reanalysis

This is the repository for all analysis used in Gidden et al. (2022).

# Requirements

Running the notebooks in this repository require a version of [`pyam`](https://pyam-iamc.readthedocs.io/en/stable/) at least version `1.6` or later.

## Data

TODO: list how to get which data sets are needed and where to put them
TODO: migrate derivative data generation here

To run the SI notebooks, place the following files from the [AR6 Scenario Explorer](https://data.ene.iiasa.ac.at/ar6/#/downloads) into a top-level `data` directory:

- `AR6_Scenarios_Database_World_v1.0.csv`
- `AR6_Scenarios_Database_R5_regions_v1.0.csv`
- `AR6_Scenarios_Database_R10_regions_v1.0.csv`
- `AR6_Scenarios_Database_metadata_indicators_v1.0.xlsx`


# Figures

All figures in the main text can be regenerated using the notebooks

- `figures/figure_1.ipynb`
- `figures/figure_2.ipynb`

# SI

The SI files depend on each other and should be run in order

- `si/00_setup.ipynb` - generates labels for scenarios based on variable availability and other metrics
- `si/01_scenario_representation.ipynb` - computes statistical tests for representativeness of scenarios and creates diagnostic plots