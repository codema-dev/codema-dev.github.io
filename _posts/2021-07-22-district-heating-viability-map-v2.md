---
title: "District Heating Viability v2"
date: 2021-07-22
categories:
  - map
tags:
  - Bokeh
  - Buildings
  - Heat
layout: splash
read_time: false
---
These maps were created using SEAI's small-level BER data (`05/2021`) & the Valuation Office's floor areas (`2021`).  The code used to generate them is open-source and available [here](https://github.com/codema-dev/projects), however, as the data is closed-access they are not reproducible without access to the underlying data.

[dublin_small_area_demand_tj_per_km2.geojson](/assets/data/2021-07-22-district-heating-viability-map-v2/dublin_small_area_demand_tj_per_km2.geojson)

## Dublin City

{% include 2021-07-22-district-heating-viability-map-v2/tables/Dublin-City.html %}

[tables/Dublin-City.png](/assets/images/2021-07-22-district-heating-viability-map-v2/tables/Dublin-City.png)

{% include 2021-07-22-district-heating-viability-map-v2/maps/Dublin-City.html %}

[maps/Dublin-City.png](/assets/images/2021-07-22-district-heating-viability-map-v2/maps/Dublin-City.png)

## Dún Laoghaire-Rathdown

{% include 2021-07-22-district-heating-viability-map-v2/tables/Dun-Laoghaire-Rathdown.html %}

[tables/Dun-Laoghaire-Rathdown.png](/assets/images/2021-07-22-district-heating-viability-map-v2/tables/Dun-Laoghaire-Rathdown.png)

{% include 2021-07-22-district-heating-viability-map-v2/maps/Dun-Laoghaire-Rathdown.html %}

[maps/Dun-Laoghaire-Rathdown.png](/assets/images/2021-07-22-district-heating-viability-map-v2/maps/Dun-Laoghaire-Rathdown.png)

## Fingal

{% include 2021-07-22-district-heating-viability-map-v2/tables/Fingal.html %}

[tables/Fingal.png](/assets/images/2021-07-22-district-heating-viability-map-v2/tables/Fingal.png)

{% include 2021-07-22-district-heating-viability-map-v2/maps/Fingal.html %}

[maps/Fingal.png](/assets/images/2021-07-22-district-heating-viability-map-v2/maps/Fingal.png)

## South Dublin

{% include 2021-07-22-district-heating-viability-map-v2/tables/South-Dublin.html %}

[tables/South-Dublin.png](/assets/images/2021-07-22-district-heating-viability-map-v2/tables/South-Dublin.png)

{% include 2021-07-22-district-heating-viability-map-v2/maps/South-Dublin.html %}

[maps/South-Dublin.png](/assets/images/2021-07-22-district-heating-viability-map-v2/maps/South-Dublin.png)

## Caveats

- Public Sector Building demand isn't included as it currently isn't possible to locate all buildings within Small Areas as the data is at postcode level

## Assumptions

```
Commercial heat demand
= fossil fuel energy benchmark [kWh/year.m^2]
* assumed boiler efficiency of 90%
* floor area [m^2]
+ industrial space heat energy benchmark [kWh/year.m^2]
* assumed boiler efficiency of 90%
* floor area [m^2]
```
- Buildings with 0 fossil fuel demand are assumed to have no heat demand.
- `CIBSE TM46` & `CIBSE Guide F` floor area energy benchmarks are reflective of current Dublin commercial building demands


```
Residential heat demand = SUM(Main & Supplementary Space & Hot Water Demand [kWh/year])
```
- SEAI's DEAP model is representative of actual heat demands.  In reality, DEAP tends to overestimate demands in older buildings it  and underestimate it in newer.
- Unknown buildings are well represented by archetypes. These archetypes were created by filling unknown buildings iteratively with a sample of nearby, known buildings with a sample size of greater than 30.  So if there is enough buildings of the same `Small Area` and `Period Built` this average is used, otherwise `Electoral District`, then `Postcode`, and finally `Period Built`.
    
    
