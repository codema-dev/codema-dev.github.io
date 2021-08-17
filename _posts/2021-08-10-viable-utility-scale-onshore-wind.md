---
title: "Viable Utility Scale Onshore Wind"
date: 2021-08-10
categories:
  - map
tags:
  - Bokeh
  - Viability
layout: splash
read_time: false
---
Displays areas suitable for utility scale wind under the specified constraints.  Created using data provided by `data.gov`:

- [mean-offshore-wind-speed-2003-height-75m-above-mean-sea-level](https://data.gov.ie/dataset/mean-offshore-wind-speed-2003-height-75m-above-mean-sea-level?package_type=dataset)

{% include 2021-08-10-viable-utility-scale-onshore-wind.html %}

## Constraints

- Not within 5km of a large town or city - Dublin City Council administrative boundary taken as the city boundary, large town defined as town centres from the County Development Plan 2016 zoning maps
- Not within 2km of the perimeter of a small town - continuous and discontinuous urban fabric layers of high density were used to define the boundary of small town equivalent
- Not located in an environmentally sensitive area (e.g. SAC, SPA, NHA)
- Not located within woodland areas or within 200m of woodland areas
- Located in areas with optimal wind speeds (greater than 8m/s assuming a 75m hub height)
- Not within 500m of any residential area or within a minimum distance of four times the turbine height from any home - locations of individual homes were not known at the time of writing this report but potential to use the Council’s geodirectory data could be used to model this more accurately, if available.
