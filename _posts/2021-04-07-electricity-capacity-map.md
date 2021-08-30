---
title: "Substation Capacity Map"
date: 2021-04-07
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

> **Caveat:** the ESB substation capacities **do not include** contracted or bid capacity and so underestimate availability. If included, all zones other than Dun Laoghaire Rathdown would likely be close to zero.

{% include 2021-04-07-electricity-capacity-map.html %}
