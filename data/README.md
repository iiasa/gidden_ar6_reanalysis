# Overview

To properly run the notebooks and code in this repository, the following files need to be placed in this directory:

From [https://data.ece.iiasa.ac.at/genie-internal/#/downloads](https://data.ece.iiasa.ac.at/genie-internal/#/downloads):

- `10.5281_zenodo.10158920_gidden_et_al_2023_ar6_reanalysis_data.xlsx`

and then manually save the two sheets as

- sheet "data": `10.5281_zenodo.10158920_gidden_et_al_2023_ar6_reanalysis_data.csv`
- sheet "meta": `10.5281_zenodo.10158920_gidden_et_al_2023_ar6_reanalysis_meta.csv`

(trust me, this saves a lot of read/load time)

From [https://data.ene.iiasa.ac.at/ar6/#/downloads](https://data.ene.iiasa.ac.at/ar6/#/downloads):

- `AR6_Scenarios_Database_World_v1.0.csv` for Figure notebooks
- `AR6_Scenarios_Database_R5_regions_v1.0.csv` for SI notebooks
- `AR6_Scenarios_Database_R10_regions_v1.0.csv` for SI notebooks

Additionally, the notebooks should be run which generate the following datasets:

- `make_additional_data.ipynb`: `additional_analysis_data.csv`
- `make_additional_metadata.ipynb`: `additional_analysis_metadata.csv`

## Known Issues

The meta column `column name="Literature Reference (if applicable)"` in the
provided metadata appears to have some extra spaces compared with the `v1.0`
version of the AR6 data. Use `ignore_meta_conflict=True` if you run into this
issue.