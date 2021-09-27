---
title: District Heating Viability v2
date: 2021-09-07 00:00:00 Z
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

## Dublin City

<div class="holds-the-iframe">
    <iframe width="100%" height="250px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Glossary-Dublin-City.html" frameborder="0" allowfullscreen></iframe>
    <iframe width="100%" height="1000px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Map-Dublin-City.html" frameborder="0" allowfullscreen></iframe>
</div>

## Dún Laoghaire-Rathdown

<div class="holds-the-iframe">
    <iframe width="100%" height="250px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Glossary-Dun-Laoghaire-Rathdown.html" frameborder="0" allowfullscreen></iframe>
    <iframe width="100%" height="1000px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Map-Dun-Laoghaire-Rathdown.html" frameborder="0" allowfullscreen></iframe>
</div>

## Fingal

<div class="holds-the-iframe">
    <iframe width="100%" height="250px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Glossary-Fingal.html" frameborder="0" allowfullscreen></iframe>
    <iframe width="100%" height="1000px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Map-Fingal.html" frameborder="0" allowfullscreen></iframe>
</div>

## South Dublin

<div class="holds-the-iframe">
    <iframe width="100%" height="250px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Glossary-South-Dublin.html" frameborder="0" allowfullscreen></iframe>
    <iframe width="100%" height="1000px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Map-South-Dublin.html" frameborder="0" allowfullscreen></iframe>
</div>

## Overview by Building Type 

### Non-Residential

<div class="holds-the-iframe">
    <iframe width="100%" height="500px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Piechart-Non-Residential-MWh.html" frameborder="0" allowfullscreen></iframe>
</div>

### Residential

| period_built |  description  | 
| -------------|---------------|
|     PRE19    |  Before 1919  |
|     19_45    |  1919 - 19_45 |
|     ...      |      ...      |
|     11L      | 2011 or Later |

<div class="holds-the-iframe">
    <iframe width="100%" height="500px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_v2/Piechart-Residential-MWh.html" frameborder="0" allowfullscreen></iframe>
</div>

## Caveats

- Public Sector Building demand isn't included as it currently isn't possible to locate all buildings within Small Areas as the data is at postcode level.
- Buildings with floor areas much larger than expected for the use type were removed.
- Process heat >100°C is not included in these maps. We can have a seperate map showing the process heat hot spots.

## Assumptions

```
Commercial heat demand
= fossil fuel energy benchmark [kWh/year.m^2]
* assumed boiler efficiency of 85%
* floor area [m^2]
+ industrial space heat energy benchmark [kWh/year.m^2]
* assumed boiler efficiency of 85%
* floor area [m^2]
```
- Buildings with 0 fossil fuel demand are assumed to have no heat demand.
- `CIBSE TM46` & `CIBSE Guide F` floor area energy benchmarks are reflective of current Dublin commercial building demands
- All buildings within each energy benchmark category are well represented by this category.


```
Residential heat demand = SUM(Main & Supplementary Space & Hot Water Demand [kWh/year])
```
- SEAI's DEAP model is representative of actual heat demands.  In reality, DEAP tends to overestimate demands in older buildings it  and underestimate it in newer.
- Unknown buildings are well represented by archetypes. These archetypes were created by filling unknown buildings iteratively with a sample of nearby, known buildings with a sample size of greater than 30.  So if there is enough buildings of the same `Small Area` and `Period Built` this average is used, otherwise `Electoral District`, then `Postcode`, and finally `Period Built`.

## Download Data

- [dublin_small_area_heat_demand.zip](https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_data.zip) - small area demand data 
- [district-heating-viability-map-v2.zip](https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_07_district_heating_viability_map_images.zip) - images of maps & tables 
- [benchmarks.csv](https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_24_commercial_floor_area_energy_benchmarks.csv) - commercial building floor area energy benchmarks
- [benchmarks.zip](https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_09_24_commercial_floor_area_energy_benchmarks_linked_to_valuation_office_uses.zip) - commercial building energy benchmark categories linked to valuation office uses 