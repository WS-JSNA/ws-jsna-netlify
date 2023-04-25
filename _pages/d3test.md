---
layout: single
title: "West Sussex Primary Care Networks"
permalink: "/matthewdorey/"
head_styles:
  - https://unpkg.com/leaflet@1.5.1/dist/leaflet.css
after_footer_scripts:
  - https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js
  - https://unpkg.com/leaflet@1.0.3/dist/leaflet.js
  - https://cdnjs.cloudflare.com/ajax/libs/d3/4.2.2/d3.min.js
  - https://unpkg.com/shpjs@latest/dist/shp.js
  - https://d3js.org/d3-format.v1.min.js
  - https://d3js.org/d3-scale-chromatic.v1.min.js
  - /assets/js/map.js
---

There are 19 Primary Care Networks (PCNs) across the three Clinical Commisionning Groups in West Sussex. Regis PCN and Arun PCN are further divided into sub neighbourhoods.

Each PCN is made up a group of a number of GP practices forming a network that covers approximately 30,000 to 50,000 patients. According to the [NHS Long Term Plan](https://www.england.nhs.uk/long-term-plan/ "NHS Long Term Plan") PCNs will form an essential building block working in Integrated Care Systems.

## Primary Care Networks overview of practices and population as at December 2019

<div id= 'pcn_overview_table'></div>

The map below shows the PCN boundaries (including sub-neighbourhoods) across West Sussex.

Each PCN boundary is made by aggregating Lower-layer Super Output Areas (LSOAs) together. However, it should be noted that GP practices do not have geographical boundaries and more than one GP practice can operate in the same local area.

Whilst the map is useful to understand roughly the local areas that each PCN may cover, for planning purposes, in reality these boundaries are not mutually exclusive (e.g. there is some crossover as patients may use GP services outside of their local areas).

We have assigned every LSOA in West Sussex to one PCN based on data from the number of residents in the LSOA registered to each GP practice and some GP practices operate in areas assigned to other PCNs (e.g. Horsham Collaborative practices in Horsham Central areas). PCN boundaries can transcend district and borough boundaries and some even cross into neighbouring counties.

 <div id="mapid" style="height:480px"></div>
 <div id="map_pcn_key"></div>

Click on an area or a dot on the map to find out more about a practice or PCN.