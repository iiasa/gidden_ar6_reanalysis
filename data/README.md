# Overview

To properly run the notebooks and code in this repository, the following files need to be placed in this directory:

From [https://data.ece.iiasa.ac.at/genie-internal/#/downloads](https://data.ece.iiasa.ac.at/genie-internal/#/downloads):

- `gidden_et_al_2022_ar6_reanalysis_data.csv`
- `gidden_et_al_2022_ar6_reanalysis_meta.csv`

From [https://data.ene.iiasa.ac.at/ar6/#/downloads](https://data.ene.iiasa.ac.at/ar6/#/downloads):

- `AR6_Scenarios_Database_World_v1.0.csv` for Figure notebooks
- `AR6_Scenarios_Database_R5_regions_v1.0.csv` for SI notebooks
- `AR6_Scenarios_Database_R10_regions_v1.0.csv` for SI notebooks

Additionally, the notebooks should be run which generate the following datasets:

- `make_additional_data.ipynb`: `additional_analysis_data.csv`
- `make_additional_metadata.ipynb`: `additional_analysis_metadata.csv`