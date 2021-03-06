---
title: Viable Utility Scale Solar PV Sites
date: 2021-08-10 00:00:00 Z
categories:
- map
tags:
- Bokeh
- Viability
layout: splash
read_time: false
---

Displays areas suitable for utility scale solar under the specified constraints.  Created using data provided by `europa` and `data.gov`:

- [urban-atlas](https://data.europa.eu/data/datasets/data_urban-atlas?locale=en) 
- [digital-elevation-model-of-ireland-from-nasas-shuttle-radar-topography-mission-srtm](https://data.gov.ie/dataset/digital-elevation-model-of-ireland-from-nasas-shuttle-radar-topography-mission-srtm)

<div class="holds-the-iframe">
    <iframe width="100%" height="1100px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_08_10_viable_utility_scale_solar_pv_map.html" frameborder="0" allowfullscreen></iframe>
</div>

## Constraints

The selection of suitable sites, as seen in this map, are based upon a number of coniditions;
- Areas within 1km of grid infrastructure - shorter cable runs to this electrical infrastructure will reduce any extra cost or environmental impact associated with this connection
- Location where topography and visual screening could be used to mitigate the potential visual impact of the array - visual screening is highly site-specific and can be remedied with sensitive landscaping practices, therefore no site was deemed unsuitable due to poor screening or topography at this stage - (https://data.europa.eu/data/datasets/data_urban-atlas?locale=en) 
- Areas with low biodiversity value - Codema has taken this to mean any areas which do not have a high biodiversity value (e.g. SPAs, SACs, NHAs and proposed NHAs as discussed in the Council’s Biodiversity Plan)
- Open spaces with minimal shading
- Areas that do not have a northward slope (slope with aspect within 45° of due north) of greater than 10° to the horizontal - Codema generated slope and aspect maps using a digital elevation model (DEM) - (https://data.gov.ie/dataset/digital-elevation-model-of-ireland-from-nasas-shuttle-radar-topography-mission-srtm)
- Area not within 30m of woodland to avoid issues with shading and falling leaves or within 30m of road or rail to avoid dust and debris - this is a general assumption that can be adjusted for specific sites as part of a more detailed feasibility study.
- The typical minimum size for a viable industrial-scale PV farm is 5 MW. A farm of this size would require a land area of approximately 10 hectares - Codema removed any land parcel smaller than 10ha that are not directly adjacent to any other sites (which together would sum to 10ha)
- Areas not within 100m of existing roads or rail lines to avoid potential glint and glare concerns. 
