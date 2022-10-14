# gidden_ar6_reanalysis

This is the repository for all analysis used in Gidden & Gasser et al. (2022).

# Requirements

Running the notebooks in this repository require a version of [`pyam`](https://pyam-iamc.readthedocs.io/en/stable/) at least version `1.6` or later.

## Data

See the [Readme in the data folder](data/README.md) for how to acquire the data for running these notebooks. 

# Figures

All figures in the main text can be regenerated using the notebooks

- `figures/figure_1.ipynb`
- `figures/figure_2.ipynb`

# SI

The SI files depend on each other and should be run in order

- `si/00_setup.ipynb` - generates labels for scenarios based on variable availability and other metrics
- `si/01_scenario_representation.ipynb` - computes statistical tests for representativeness of scenarios and creates diagnostic plots
- `si/02_adjustment_characteristics.ipynb` - computes median NGHGI adjustment value
- `si/03_mitigation_outcomes_table.ipynb` - computes key mitigation benchmarks and statistics
