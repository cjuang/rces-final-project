# rces-final-project
My final project repository for RCES, Fall 2020

**Caroline Juang** (csj2116)

c.juang@columbia.edu

Research Computing for the Earth Sciences, Columbia University

## Run Project in Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cjuang/rces-final-project/main)

## Description

Fire activity in the western United States (US) presents [a clear danger to human life and infrastructure](https://earthobservatory.nasa.gov/images/147443/record-setting-fires-in-colorado-and-california), establishing a need to study the variables that may influence fire.  In this notebook, I will explore both the fuel availability (forest vs. non-forest burned area) and the climate (vapor pressure deficit) and look at patterns across western United States ecoregions.

## Data sources

**Fire burned area data** are by Caroline Juang and Park Williams, modified from the [Monitoring Trends in Burn Severity (MTBS)](https://www.mtbs.gov/) program (fires 1984-2018), the [National Wildfire Coordinating Group (NWCG)](https://fam.nwcg.gov/fam-web/weatherfirecd/index.htm) (fires 1984-2017), and the [National Fire and Aviation Management (FAM)](https://fam.nwcg.gov/fam-web/) (fires 1984-2018).

**Forest type data** are by Bonnie Ruefenacht of the [United States Forest Service](https://www.sciencebase.gov/catalog/item/52000df9e4b0ad2d97189c77) and modified into a fractional gridded data product.

**Level II Ecoregion boundaries** are by the [Environmental Protection Agency (EPA)](https://www.epa.gov/eco-research/ecoregions-north-america) and modified into a fractional gridded data product.

**Vapor pressure** was calculated from dew point data. Gridded records of monthly mean dew point come from [PRISM](http://prism.oregonstate.edu) ([Daly et al., 2004](https://prism.oregonstate.edu/documents/pubs/2004appclim_monthlyMaps_daly.pdf))

**Saturation vapor pressure** was calculated from mean maximum daily temperature (Tmax) and mean minimum daily temperature (Tmin). Monthly gridded records of Tmax and Tmin were calculated from the [National Oceanic and Atmospheric Administration (NOAA) Climgrid dataset](ftp://ftp.ncdc.noaa.gov/pub/data/climgrid) ([Vose et al., 2014](https://doi.org/10.1175/JAMC-D-13-0248.1))