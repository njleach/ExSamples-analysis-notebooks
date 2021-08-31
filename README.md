# ExSamples-analysis-notebooks

This repo contains jupyter notebooks used for analysis of the ExSamples ensembles presented in a study currently in preparation.

## Notebook list

The notebooks are intended to be run on JASMIN, and have references to directories that will break if run locally (unless changed to local data copies). The order notebooks contains in this repo are as given below. The italic lists of graphical elements indicates which notebooks are used to create which elements.

| order | /path/to/notebook  | description |
| ----- | ------------- | ------------- |
| 1 | /notebooks/manuscript-mslp-analogs.ipynb  | Generates the analog subsample lists. If wishing to reproduce analysis from start to end, must be run first. *FIGS 3*  |
| 2 | /notebooks/manuscript-UKCP-lineplot.ipynb  | Creates the lineplot used to select the UKCP extreme study winters. *FIG 1*   |
| 3 | /notebooks/manuscript-UKCP-SST-maps.ipynb  | Creates the maps illustrating the synoptic situation during the three study winters. *FIG 2*  |
| 4 | /notebooks/manuscript-distribution-tasmax.ipynb  | Creates the figures showing statistics for the temperature variables + calculates various statistics used to compare the ensembles. *FIG 3,4; FIGS 4,7-9; TAB2*  |
| 5 | /notebooks/manuscript-distribution-pr.ipynb  | Creates the figures showing statistics for the precipitation variables + calculates various statistics used to compare the ensembles. *FIG 5; FIGS 5,6,10-12; TAB2* |
| 6 | /notebooks/manuscript-SI-dynamical-eof-analysis.ipynb  | Performs the large-scale flow analysis described inthe supplemenentary information. *FIGS 1,2*  |
| 7 | /notebooks/manuscript-storylines-of-8960966.ipynb  | A deeper look into the "record-shattering" extreme ExSamples member. No analysis used in study, but interesting nonetheless.  |

## Data sources and availability

We use data from two sources: the ExSamples ensembles and the UKCP18 PPE.

- the UKCP18 PPE is available from [CEDA](http://data.ceda.ac.uk/badc/ukcp18/data/land-gcm/global/60km/rcp85).

- the ExSamples data used is currently available from [MASS](https://help.jasmin.ac.uk/category/227-mass). The specific directory is `/adhoc/projects/qump_hadgem3/ExSamples/netcdf/product/20210622`.