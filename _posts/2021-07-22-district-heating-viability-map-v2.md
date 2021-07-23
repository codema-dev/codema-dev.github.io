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
These maps were created using SEAI's small-level BER data (`05/2021`) & the Valuation Office's floor areas (`2021`)

# Dublin City

<style type="text/css">
#T_30cfa_row0_col0, #T_30cfa_row0_col1, #T_30cfa_row0_col2, #T_30cfa_row0_col3, #T_30cfa_row0_col4 {
  background: rgba(255,255,178,0.75);
  axis: 1;
}
#T_30cfa_row1_col0, #T_30cfa_row1_col1, #T_30cfa_row1_col2, #T_30cfa_row1_col3, #T_30cfa_row1_col4 {
  background: rgba(254,204,92,0.75);
  axis: 1;
}
#T_30cfa_row2_col0, #T_30cfa_row2_col1, #T_30cfa_row2_col2, #T_30cfa_row2_col3, #T_30cfa_row2_col4 {
  background: rgba(253,141,60,0.75);
  axis: 1;
}
#T_30cfa_row3_col0, #T_30cfa_row3_col1, #T_30cfa_row3_col2, #T_30cfa_row3_col3, #T_30cfa_row3_col4 {
  background: rgba(240,59,32,0.75);
  axis: 1;
}
#T_30cfa_row4_col0, #T_30cfa_row4_col1, #T_30cfa_row4_col2, #T_30cfa_row4_col3, #T_30cfa_row4_col4 {
  background: rgba(189,0,38,0.75);
  axis: 1;
}
</style>
<table id="T_30cfa_">
  <thead>
    <tr>
      <th class="blank level0" >&nbsp;</th>
      <th class="col_heading level0 col0" >Residential [TJ/km²year]</th>
      <th class="col_heading level0 col1" >Non-Residential [TJ/km²year]</th>
      <th class="col_heading level0 col2" >Total [TJ/km²year]</th>
      <th class="col_heading level0 col3" >Band [TJ/km²year]</th>
      <th class="col_heading level0 col4" >% Share</th>
    </tr>
    <tr>
      <th class="index_name level0" >Feasibility</th>
      <th class="blank col0" >&nbsp;</th>
      <th class="blank col1" >&nbsp;</th>
      <th class="blank col2" >&nbsp;</th>
      <th class="blank col3" >&nbsp;</th>
      <th class="blank col4" >&nbsp;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th id="T_30cfa_level0_row0" class="row_heading level0 row0" >Not Feasible</th>
      <td id="T_30cfa_row0_col0" class="data row0 col0" >182</td>
      <td id="T_30cfa_row0_col1" class="data row0 col1" >40</td>
      <td id="T_30cfa_row0_col2" class="data row0 col2" >222</td>
      <td id="T_30cfa_row0_col3" class="data row0 col3" ><20</td>
      <td id="T_30cfa_row0_col4" class="data row0 col4" >0</td>
    </tr>
    <tr>
      <th id="T_30cfa_level0_row1" class="row_heading level0 row1" >Future Potential</th>
      <td id="T_30cfa_row1_col0" class="data row1 col0" >1551</td>
      <td id="T_30cfa_row1_col1" class="data row1 col1" >191</td>
      <td id="T_30cfa_row1_col2" class="data row1 col2" >1742</td>
      <td id="T_30cfa_row1_col3" class="data row1 col3" >20-50</td>
      <td id="T_30cfa_row1_col4" class="data row1 col4" >0</td>
    </tr>
    <tr>
      <th id="T_30cfa_level0_row2" class="row_heading level0 row2" >Feasible with Supporting Regulation</th>
      <td id="T_30cfa_row2_col0" class="data row2 col0" >19771</td>
      <td id="T_30cfa_row2_col1" class="data row2 col1" >2188</td>
      <td id="T_30cfa_row2_col2" class="data row2 col2" >21960</td>
      <td id="T_30cfa_row2_col3" class="data row2 col3" >50-120</td>
      <td id="T_30cfa_row2_col4" class="data row2 col4" >3</td>
    </tr>
    <tr>
      <th id="T_30cfa_level0_row3" class="row_heading level0 row3" >Feasible</th>
      <td id="T_30cfa_row3_col0" class="data row3 col0" >221306</td>
      <td id="T_30cfa_row3_col1" class="data row3 col1" >18368</td>
      <td id="T_30cfa_row3_col2" class="data row3 col2" >239674</td>
      <td id="T_30cfa_row3_col3" class="data row3 col3" >120-300</td>
      <td id="T_30cfa_row3_col4" class="data row3 col4" >33</td>
    </tr>
    <tr>
      <th id="T_30cfa_level0_row4" class="row_heading level0 row4" >Very Feasible</th>
      <td id="T_30cfa_row4_col0" class="data row4 col0" >308636</td>
      <td id="T_30cfa_row4_col1" class="data row4 col1" >143372</td>
      <td id="T_30cfa_row4_col2" class="data row4 col2" >452008</td>
      <td id="T_30cfa_row4_col3" class="data row4 col3" >>300</td>
      <td id="T_30cfa_row4_col4" class="data row4 col4" >63</td>
    </tr>
  </tbody>
</table>


<div style="height: 1000px; width: 100%;">
  <iframe
    type="text/html"
    src="{{ site.baseurl }}/assets/html/2021-07-22-district-heating-viability-map-v2/Dublin City.html"
    style="height: 100%; width: 100%; border: 0;">
  </iframe>
</div>

# Dún Laoghaire-Rathdown

<style type="text/css">
#T_0e690_row0_col0, #T_0e690_row0_col1, #T_0e690_row0_col2, #T_0e690_row0_col3, #T_0e690_row0_col4 {
  background: rgba(255,255,178,0.75);
  axis: 1;
}
#T_0e690_row1_col0, #T_0e690_row1_col1, #T_0e690_row1_col2, #T_0e690_row1_col3, #T_0e690_row1_col4 {
  background: rgba(254,204,92,0.75);
  axis: 1;
}
#T_0e690_row2_col0, #T_0e690_row2_col1, #T_0e690_row2_col2, #T_0e690_row2_col3, #T_0e690_row2_col4 {
  background: rgba(253,141,60,0.75);
  axis: 1;
}
#T_0e690_row3_col0, #T_0e690_row3_col1, #T_0e690_row3_col2, #T_0e690_row3_col3, #T_0e690_row3_col4 {
  background: rgba(240,59,32,0.75);
  axis: 1;
}
#T_0e690_row4_col0, #T_0e690_row4_col1, #T_0e690_row4_col2, #T_0e690_row4_col3, #T_0e690_row4_col4 {
  background: rgba(189,0,38,0.75);
  axis: 1;
}
</style>
<table id="T_0e690_">
  <thead>
    <tr>
      <th class="blank level0" >&nbsp;</th>
      <th class="col_heading level0 col0" >Residential [TJ/km²year]</th>
      <th class="col_heading level0 col1" >Non-Residential [TJ/km²year]</th>
      <th class="col_heading level0 col2" >Total [TJ/km²year]</th>
      <th class="col_heading level0 col3" >Band [TJ/km²year]</th>
      <th class="col_heading level0 col4" >% Share</th>
    </tr>
    <tr>
      <th class="index_name level0" >Feasibility</th>
      <th class="blank col0" >&nbsp;</th>
      <th class="blank col1" >&nbsp;</th>
      <th class="blank col2" >&nbsp;</th>
      <th class="blank col3" >&nbsp;</th>
      <th class="blank col4" >&nbsp;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th id="T_0e690_level0_row0" class="row_heading level0 row0" >Not Feasible</th>
      <td id="T_0e690_row0_col0" class="data row0 col0" >242</td>
      <td id="T_0e690_row0_col1" class="data row0 col1" >30</td>
      <td id="T_0e690_row0_col2" class="data row0 col2" >272</td>
      <td id="T_0e690_row0_col3" class="data row0 col3" ><20</td>
      <td id="T_0e690_row0_col4" class="data row0 col4" >0</td>
    </tr>
    <tr>
      <th id="T_0e690_level0_row1" class="row_heading level0 row1" >Future Potential</th>
      <td id="T_0e690_row1_col0" class="data row1 col0" >1670</td>
      <td id="T_0e690_row1_col1" class="data row1 col1" >136</td>
      <td id="T_0e690_row1_col2" class="data row1 col2" >1806</td>
      <td id="T_0e690_row1_col3" class="data row1 col3" >20-50</td>
      <td id="T_0e690_row1_col4" class="data row1 col4" >1</td>
    </tr>
    <tr>
      <th id="T_0e690_level0_row2" class="row_heading level0 row2" >Feasible with Supporting Regulation</th>
      <td id="T_0e690_row2_col0" class="data row2 col0" >22677</td>
      <td id="T_0e690_row2_col1" class="data row2 col1" >1349</td>
      <td id="T_0e690_row2_col2" class="data row2 col2" >24025</td>
      <td id="T_0e690_row2_col3" class="data row2 col3" >50-120</td>
      <td id="T_0e690_row2_col4" class="data row2 col4" >22</td>
    </tr>
    <tr>
      <th id="T_0e690_level0_row3" class="row_heading level0 row3" >Feasible</th>
      <td id="T_0e690_row3_col0" class="data row3 col0" >60180</td>
      <td id="T_0e690_row3_col1" class="data row3 col1" >5943</td>
      <td id="T_0e690_row3_col2" class="data row3 col2" >66122</td>
      <td id="T_0e690_row3_col3" class="data row3 col3" >120-300</td>
      <td id="T_0e690_row3_col4" class="data row3 col4" >60</td>
    </tr>
    <tr>
      <th id="T_0e690_level0_row4" class="row_heading level0 row4" >Very Feasible</th>
      <td id="T_0e690_row4_col0" class="data row4 col0" >10782</td>
      <td id="T_0e690_row4_col1" class="data row4 col1" >6416</td>
      <td id="T_0e690_row4_col2" class="data row4 col2" >17198</td>
      <td id="T_0e690_row4_col3" class="data row4 col3" >>300</td>
      <td id="T_0e690_row4_col4" class="data row4 col4" >15</td>
    </tr>
  </tbody>
</table>

<div style="height: 1000px; width: 100%;">
  <iframe
    type="text/html"
    src="{{ site.baseurl }}/assets/html/2021-07-22-district-heating-viability-map-v2/Dún Laoghaire-Rathdown.html"
    style="height: 100%; width: 100%; border: 0;">
  </iframe>
</div>


# Fingal

<style type="text/css">
#T_078ca_row0_col0, #T_078ca_row0_col1, #T_078ca_row0_col2, #T_078ca_row0_col3, #T_078ca_row0_col4 {
  background: rgba(255,255,178,0.75);
  axis: 1;
}
#T_078ca_row1_col0, #T_078ca_row1_col1, #T_078ca_row1_col2, #T_078ca_row1_col3, #T_078ca_row1_col4 {
  background: rgba(254,204,92,0.75);
  axis: 1;
}
#T_078ca_row2_col0, #T_078ca_row2_col1, #T_078ca_row2_col2, #T_078ca_row2_col3, #T_078ca_row2_col4 {
  background: rgba(253,141,60,0.75);
  axis: 1;
}
#T_078ca_row3_col0, #T_078ca_row3_col1, #T_078ca_row3_col2, #T_078ca_row3_col3, #T_078ca_row3_col4 {
  background: rgba(240,59,32,0.75);
  axis: 1;
}
#T_078ca_row4_col0, #T_078ca_row4_col1, #T_078ca_row4_col2, #T_078ca_row4_col3, #T_078ca_row4_col4 {
  background: rgba(189,0,38,0.75);
  axis: 1;
}
</style>
<table id="T_078ca_">
  <thead>
    <tr>
      <th class="blank level0" >&nbsp;</th>
      <th class="col_heading level0 col0" >Residential [TJ/km²year]</th>
      <th class="col_heading level0 col1" >Non-Residential [TJ/km²year]</th>
      <th class="col_heading level0 col2" >Total [TJ/km²year]</th>
      <th class="col_heading level0 col3" >Band [TJ/km²year]</th>
      <th class="col_heading level0 col4" >% Share</th>
    </tr>
    <tr>
      <th class="index_name level0" >Feasibility</th>
      <th class="blank col0" >&nbsp;</th>
      <th class="blank col1" >&nbsp;</th>
      <th class="blank col2" >&nbsp;</th>
      <th class="blank col3" >&nbsp;</th>
      <th class="blank col4" >&nbsp;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th id="T_078ca_level0_row0" class="row_heading level0 row0" >Not Feasible</th>
      <td id="T_078ca_row0_col0" class="data row0 col0" >507</td>
      <td id="T_078ca_row0_col1" class="data row0 col1" >171</td>
      <td id="T_078ca_row0_col2" class="data row0 col2" >679</td>
      <td id="T_078ca_row0_col3" class="data row0 col3" ><20</td>
      <td id="T_078ca_row0_col4" class="data row0 col4" >0</td>
    </tr>
    <tr>
      <th id="T_078ca_level0_row1" class="row_heading level0 row1" >Future Potential</th>
      <td id="T_078ca_row1_col0" class="data row1 col0" >2556</td>
      <td id="T_078ca_row1_col1" class="data row1 col1" >417</td>
      <td id="T_078ca_row1_col2" class="data row1 col2" >2973</td>
      <td id="T_078ca_row1_col3" class="data row1 col3" >20-50</td>
      <td id="T_078ca_row1_col4" class="data row1 col4" >2</td>
    </tr>
    <tr>
      <th id="T_078ca_level0_row2" class="row_heading level0 row2" >Feasible with Supporting Regulation</th>
      <td id="T_078ca_row2_col0" class="data row2 col0" >29235</td>
      <td id="T_078ca_row2_col1" class="data row2 col1" >1875</td>
      <td id="T_078ca_row2_col2" class="data row2 col2" >31110</td>
      <td id="T_078ca_row2_col3" class="data row2 col3" >50-120</td>
      <td id="T_078ca_row2_col4" class="data row2 col4" >29</td>
    </tr>
    <tr>
      <th id="T_078ca_level0_row3" class="row_heading level0 row3" >Feasible</th>
      <td id="T_078ca_row3_col0" class="data row3 col0" >63675</td>
      <td id="T_078ca_row3_col1" class="data row3 col1" >2574</td>
      <td id="T_078ca_row3_col2" class="data row3 col2" >66248</td>
      <td id="T_078ca_row3_col3" class="data row3 col3" >120-300</td>
      <td id="T_078ca_row3_col4" class="data row3 col4" >62</td>
    </tr>
    <tr>
      <th id="T_078ca_level0_row4" class="row_heading level0 row4" >Very Feasible</th>
      <td id="T_078ca_row4_col0" class="data row4 col0" >3497</td>
      <td id="T_078ca_row4_col1" class="data row4 col1" >1808</td>
      <td id="T_078ca_row4_col2" class="data row4 col2" >5305</td>
      <td id="T_078ca_row4_col3" class="data row4 col3" >>300</td>
      <td id="T_078ca_row4_col4" class="data row4 col4" >5</td>
    </tr>
  </tbody>
</table>

<div style="height: 1000px; width: 100%;">
  <iframe
    type="text/html"
    src="{{ site.baseurl }}/assets/html/2021-07-22-district-heating-viability-map-v2/Fingal.html"
    style="height: 100%; width: 100%; border: 0;">
  </iframe>
</div>

# South Dublin

<style type="text/css">
#T_40a17_row0_col0, #T_40a17_row0_col1, #T_40a17_row0_col2, #T_40a17_row0_col3, #T_40a17_row0_col4 {
  background: rgba(255,255,178,0.75);
  axis: 1;
}
#T_40a17_row1_col0, #T_40a17_row1_col1, #T_40a17_row1_col2, #T_40a17_row1_col3, #T_40a17_row1_col4 {
  background: rgba(254,204,92,0.75);
  axis: 1;
}
#T_40a17_row2_col0, #T_40a17_row2_col1, #T_40a17_row2_col2, #T_40a17_row2_col3, #T_40a17_row2_col4 {
  background: rgba(253,141,60,0.75);
  axis: 1;
}
#T_40a17_row3_col0, #T_40a17_row3_col1, #T_40a17_row3_col2, #T_40a17_row3_col3, #T_40a17_row3_col4 {
  background: rgba(240,59,32,0.75);
  axis: 1;
}
#T_40a17_row4_col0, #T_40a17_row4_col1, #T_40a17_row4_col2, #T_40a17_row4_col3, #T_40a17_row4_col4 {
  background: rgba(189,0,38,0.75);
  axis: 1;
}
</style>
<table id="T_40a17_">
  <thead>
    <tr>
      <th class="blank level0" >&nbsp;</th>
      <th class="col_heading level0 col0" >Residential [TJ/km²year]</th>
      <th class="col_heading level0 col1" >Non-Residential [TJ/km²year]</th>
      <th class="col_heading level0 col2" >Total [TJ/km²year]</th>
      <th class="col_heading level0 col3" >Band [TJ/km²year]</th>
      <th class="col_heading level0 col4" >% Share</th>
    </tr>
    <tr>
      <th class="index_name level0" >Feasibility</th>
      <th class="blank col0" >&nbsp;</th>
      <th class="blank col1" >&nbsp;</th>
      <th class="blank col2" >&nbsp;</th>
      <th class="blank col3" >&nbsp;</th>
      <th class="blank col4" >&nbsp;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th id="T_40a17_level0_row0" class="row_heading level0 row0" >Not Feasible</th>
      <td id="T_40a17_row0_col0" class="data row0 col0" >239</td>
      <td id="T_40a17_row0_col1" class="data row0 col1" >87</td>
      <td id="T_40a17_row0_col2" class="data row0 col2" >326</td>
      <td id="T_40a17_row0_col3" class="data row0 col3" ><20</td>
      <td id="T_40a17_row0_col4" class="data row0 col4" >0</td>
    </tr>
    <tr>
      <th id="T_40a17_level0_row1" class="row_heading level0 row1" >Future Potential</th>
      <td id="T_40a17_row1_col0" class="data row1 col0" >1899</td>
      <td id="T_40a17_row1_col1" class="data row1 col1" >215</td>
      <td id="T_40a17_row1_col2" class="data row1 col2" >2113</td>
      <td id="T_40a17_row1_col3" class="data row1 col3" >20-50</td>
      <td id="T_40a17_row1_col4" class="data row1 col4" >1</td>
    </tr>
    <tr>
      <th id="T_40a17_level0_row2" class="row_heading level0 row2" >Feasible with Supporting Regulation</th>
      <td id="T_40a17_row2_col0" class="data row2 col0" >24914</td>
      <td id="T_40a17_row2_col1" class="data row2 col1" >1694</td>
      <td id="T_40a17_row2_col2" class="data row2 col2" >26609</td>
      <td id="T_40a17_row2_col3" class="data row2 col3" >50-120</td>
      <td id="T_40a17_row2_col4" class="data row2 col4" >21</td>
    </tr>
    <tr>
      <th id="T_40a17_level0_row3" class="row_heading level0 row3" >Feasible</th>
      <td id="T_40a17_row3_col0" class="data row3 col0" >79475</td>
      <td id="T_40a17_row3_col1" class="data row3 col1" >3954</td>
      <td id="T_40a17_row3_col2" class="data row3 col2" >83429</td>
      <td id="T_40a17_row3_col3" class="data row3 col3" >120-300</td>
      <td id="T_40a17_row3_col4" class="data row3 col4" >68</td>
    </tr>
    <tr>
      <th id="T_40a17_level0_row4" class="row_heading level0 row4" >Very Feasible</th>
      <td id="T_40a17_row4_col0" class="data row4 col0" >5635</td>
      <td id="T_40a17_row4_col1" class="data row4 col1" >4047</td>
      <td id="T_40a17_row4_col2" class="data row4 col2" >9682</td>
      <td id="T_40a17_row4_col3" class="data row4 col3" >>300</td>
      <td id="T_40a17_row4_col4" class="data row4 col4" >7</td>
    </tr>
  </tbody>
</table>

<div style="height: 1000px; width: 100%;">
  <iframe
    type="text/html"
    src="{{ site.baseurl }}/assets/html/2021-07-22-district-heating-viability-map-v2/South Dublin.html"
    style="height: 100%; width: 100%; border: 0;">
  </iframe>
</div>