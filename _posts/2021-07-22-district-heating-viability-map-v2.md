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

[dublin_small_area_demand_tj_per_km2.geojson](https://codema-dev.s3.eu-west-1.amazonaws.com/dublin_small_area_demand_tj_per_km2.geojson)

## Dublin City

{% include 2021-07-22-district-heating-viability-map-v2/tables/Dublin-City.html %}


{% include 2021-07-22-district-heating-viability-map-v2/maps/Dublin-City.html %}

[Dublin-City.jpg](/assets/images/2021-07-22-district-heating-viability-map-v2/Dublin-City.jpg)

## Dún Laoghaire-Rathdown

{% include 2021-07-22-district-heating-viability-map-v2/tables/Dun-Laoghaire-Rathdown.html %}

{% include 2021-07-22-district-heating-viability-map-v2/maps/Dun-Laoghaire-Rathdown.html %}

[Dun-Laoghaire-Rathdown.jpg](/assets/images/2021-07-22-district-heating-viability-map-v2/Dun-Laoghaire-Rathdown.jpg)

## Fingal

{% include 2021-07-22-district-heating-viability-map-v2/tables/Fingal.html %}

{% include 2021-07-22-district-heating-viability-map-v2/maps/Fingal.html %}

[Fingal.jpg](/assets/images/2021-07-22-district-heating-viability-map-v2/Fingal.jpg)

## South Dublin

{% include 2021-07-22-district-heating-viability-map-v2/tables/South-Dublin.html %}

{% include 2021-07-22-district-heating-viability-map-v2/maps/South-Dublin.html %}

[South-Dublin.jpg](/assets/images/2021-07-22-district-heating-viability-map-v2/South-Dublin.jpg)

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
    
    
