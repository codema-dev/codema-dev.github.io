---
title: Substation Capacity Map
date: 2021-04-07 00:00:00 Z
categories:
- map
tags:
- Bokeh
- Electricity
layout: splash
read_time: false
---

A map of Medium Voltage (MV) substation clusters.  It was created by grouping similarly located MV substations using data from the ESB Substation Capacity
map [here](https://www.esbnetworks.ie/new-connections/generator-connections-group/availability-capacity-map) or [here](https://www.esbnetworks.ie/network-capacity-map)

> **Caveat:** the ESB substation capacities **do not include** contracted or bid capacity and so overestimate availability. If included, all zones other than Dun Laoghaire Rathdown would likely be close to zero.

**Notes**:
- `SLR` stands for [Special Load Reading](https://www.esbnetworks.ie/publications) which  are a coincident set of measurements of simultaneous load for all distribution substations taken each year on a single day by the ESB in both summer and winter.
- In most zones `Demand Available + SLR Load` is not equal to `Installed Capacity`, on average this sum is around 60% of installed capacity for each substation.

<div class="holds-the-iframe">
    <iframe width="100%" height="1000px" src="https://codema-dev.s3.eu-west-1.amazonaws.com/views/2021_04_07_medium_voltage_electricity_substation_capacity_map.html" frameborder="0" allowfullscreen></iframe>
</div>