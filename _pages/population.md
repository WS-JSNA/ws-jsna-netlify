---
layout: single
title: "Population estimates and projections - an introduction"
toc: true
permalink: /population-new/
head_styles:
  - https://unpkg.com/leaflet@1.5.1/dist/leaflet.css
  - https://fonts.googleapis.com/css?family=Open+Sans&display=swap
  - /assets/js/population/population_styles.css
after_footer_scripts:
  - https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js
  - https://unpkg.com/leaflet@1.0.3/dist/leaflet.js
  - https://cdnjs.cloudflare.com/ajax/libs/d3/4.2.2/d3.min.js
  - https://unpkg.com/shpjs@latest/dist/shp.js
  - https://d3js.org/d3-format.v1.min.js
  - https://d3js.org/d3-scale-chromatic.v1.min.js
  - /assets/js/population/population_change.js
  - /assets/js/population/population_maps.js
  - /assets/js/population/oadr.js
---

Annual estimates of the population living in West Sussex are provided by the Office for National Statistics. The most accurate estimates are drawn from the census, which takes place every 10 years in the UK. Population estimates are then updated every year, mostly using information on births, deaths, and migration, until the next census to produce mid-year population estimates (MYEs). National and local authority estimates are usually updated in June each year by the Office for National Statistics for the previous year (e.g. mid-2018 estimates were released in June 2019), with small area population estimates released later in the year, usually in November.

In addition to understanding the number of people living in the county, it is also important to consider the number of people using health services such as GPs, as these are important populations for public health interventions such as NHS Health Checks, NHS Stop Smoking Services in primary care, and for health protection interventions such as flu vaccines. People do not always go to a GP practice close to where they live and may instead use services closer to where they work. Fortunately, GP practices regularly publish the number of patients by age and sex who are registered to a particular practice.

Trends from recent mid year estimates are also used to project what the population could look like in the next 30 years if those trends continued. It is, of course, likely that unexpected events or policies will have an impact on future population changes and projections cannot take these into account. One uncertainty will be the impact of the UK's withdrawal from the European Union which will influence migration of populations.

This analysis looks at the mid 2018 population estimates, as well as GP registrations, and population projections, to consider the demographics of West Sussex, and what the population of West Sussex may look like in the future.

The population estimates refer to the usual residence of a population, it is not a count of how many people are expected to be in an area at a given time (e.g. it does not estimate the number of people who come into an area for work or for tourism). For most people, defining where they usually live is quite straightforward although specific rules are applied to estimate numbers of people in the armed forces, and also the number of students, prisoners, and international migrants.
{: .notice--info}

Higher education students and schoolchildren studying away from home are counted as residents at their term-time address, members of the armed forces are usually resident at the address where they spend most of their time and prisoners are usually resident in the prison estate if they have a sentence of six months or more. International migrants are usually resident if they intend to stay in England and Wales for more than 12 months.
{: .notice--info}

As the mid year residents figures are estimates rather than counts, there is an expected level of uncertainty and the Office for National Statistics recommends rounding mid year estimates to at least the nearest 100 population in any publication. Whilst we report rounded estimates in the text of this briefing, in some instances, unrounded estimates are used for further calculations such as percentages, ratios, and changes over time. Figures are also based on unrounded estimates.
{: .notice--warning}

## West Sussex in 2018
<p id = 'wsx_intro_string_1'></p>
<p id = 'wsx_intro_string_2'></p>
<p id = 'wsx_gp_2018_string'></p>

The 2018 mid year estimates and comparable GP registrations by age and sex are given in the table below.

### West Sussex mid 2018 population estimates and GP registrations; by age and sex;

<div id = 'population_18_table'></div>

Whilst the total population estimates and population change values in this table are rounded, percentages and ratios are calculated from unrounded values.
{: .notice--danger}

The figure below is a population pyramid. This visualises the age and sex structure of a population's estimated resident population and the number of people registered to GP practices operating in the area. You can interact with it and change the area to see differences across West Sussex.

The shape of the pyramid gives an indication of the age structure of a population, if the shape is wider at the top, this is indicative of an ageing population and a pyramid which is wider at the bottom indicates a relatively younger population overall.

### We could have a population pyramid here that is only 2018, but you can switch between areas and have a reference area of lines. This could be bars = resident and lines = gp registered
Which age groups have more registrations than residents?

### What causes the changes in population?

The table below shows the 2018 'components of change' figures for our county and its lower tier local authorities (sometimes called districts and boroughs). A components of change table shows how the population is affected by births, deaths, and migration.

To make comparing population changes across areas easier (because some of our districts have almost three times as many residents than others), the values are presented per 1,000 population with the raw value given in brackets.

### West Sussex districts 2018 population changes

<div id = 'population_coc_18_table'></div>

Whilst the total population estimates and population change values in this table are rounded, percentages and ratios are calculated from unrounded values.
{: .notice--primary}

There were roughly 10 births for every 1,000 people in West Sussex in 2018.

Migration flows between local authority districts are explored in more detail later in this briefing.

{% capture notice-aging %}
Total population estimates are rounded to the nearest 100 although figures for births, deaths and migrations are unrounded.

To enable comparison between GP registrations and estimates of residents, we have compared the snapshot of GP registrations as close to the time of the estimates as possible (July 2018). There are more recent snapshots available (GP practice lists are updated monthly) and some practices will have closed since July 2018.
{% endcapture %}

<div class="notice--info">{{notice-aging | markdownify}}</div>

### Ageing population

In West Sussex, the median age in 2018 was 45.1 years, up from 44 years in 2013 and 42.8 years a decade ago in 2008.

The table below shows the median age for each West Sussex district and borough every five years since 2003.

<div id = 'population_median_age_table'></div>

For most districts, the median age has increased by at least three years over the last 15 years although there have been much smaller increases in the north of the county. Moreover, Crawley has consistently maintained a lower median age for its population compared to the rest of the county. In 2018, the median age for residents in Crawley was 37.2 years compared to Arun which had a median age of 49.4 years (a difference of over 12 years).

The median age provides a useful summary measure of the age structure of the population as it shows that exactly half the population is below and the other half is above the median age.
{: .notice--info}

## Where do people live within West Sussex?

In West Sussex, in 2018, there was estimated to be 431 people per square kilometre. There is a lot of variation across the county, starting at district level with Chichester having as few as 154 residents per square kilometre and Worthing having more than twenty times this at 3,383 residents per square kilometre. The population density of West Sussex districts has been fairly stable over the last 15 years.

There is even more variation across the neighbourhoods of West Sussex. At LSOA level, the population density ranges from 20 people per square kilometre in a neighbourhood (Chichester 007B) in Funtington ward in Chichester to more than 13,000 people per square kilometre in Worthing 011D (in Heene ward, Worthing). More than a third of the neighbourhoods in West Sussex have a population density of less than 2,000 per square kilometre (the yellow colour on the map).

<div id = "map_density" style = "height: 550px"></div>

Where are most older people living?

<div id = "map_mye" style = "height: 550px"></div>

Where do GP practice populations reside?

{% capture notice %}
The mid year population estimates show us how many people live per square kilometre, as a measure of population density (how many people share a unit of space).

Lower-layer super output areas (LSOAs) are small area geographies designed to improve the reporting of local area data. There are 32,844 LSOAs in England, and boundaries are coterminous with local authority boundaries and clinical commissioning groups.

LSOAs are defined from census data (e.g. the latest update is 2011) so that each LSOA has an average of 1,500 residents or 650 households. The consistency in population size helps with reporting of area based statistics whereas other small area boundaries such as wards or parishes tend to change frequently and do not always hold a consistent population size. LSOAs are not coterminous with wards and parish boundaries.

There are 505 LSOAs in West Sussex and each LSOA has a code and name which reflects the district or authority it is in (e.g. Arun 002A). These names are not particularly helpful for locating an area on a map. As such, whilst LSOAs are not coterminous with ward boundaries, if you click on an area the name of the closest ward is given for reference.
{% endcapture %}

<div class = "notice--info">{{notice | markdownify}}</div>

## Migration
The chart below shows the net internal migration flow for West Sussex in the year ending June 2016 by age group. It shows that over the 12 months leading to June 2016, more people settled in the county than left for nearly all age groups apart from 15-19 and 20-24 year olds. These young people may be those who leave the family home for the first time to go to university.

The pattern of net internal migration is varied among the districts of West Sussex (shown below), with Crawley showing the inverse of the pattern seen at county level, with 20-24 year olds being the only age group to have a net increase in population.

<!-- # Other change- Includes estimated net effect of changes to special populations during the twelve months to mid-year. Special populations comprise prisoner, armed forces and their overseas based dependent populations. It also includes estimated population change not attributed to a specific cause in the twelve months to mid-year and small adjustments necessary to account for issues such as minor LA boundary changes and large postcode areas that overlap LA boundaries.

# Deaths
# Death occurrences in a small minority of cells show a negative count. These are as a result of previously provisional data being updated in subsequent periods to account for late death registrations and reallocated counts.

# We define an internal migrant as someone who moves home from one geographical area to another. This may be between local authorities, regions or countries within the UK. Unlike with international migration, there is no internationally agreed definition.

# Figure 3 shows a comparatively high likelihood of moving for very young children. Part of this may be simply because their parents are at an age where moving is still common. The addition of children to a family may also lead to a move, however, once children are at school moves are much less common, potentially because of the disruption it would cause the children as well as the parents who may be at an age where they’re settled into their career.
#
# It is in early adulthood where most moves occur, with the peak age for moves being 19, the main age at which people leave home for study. There is another smaller peak at age 22; in many cases this will reflect graduates moving for employment, further study, returning to their home address or moving in with a partner.
#
# Levels of movement remain comparatively high through those aged in their 20s and 30s but gradually decline with age. This may reflect people becoming more settled in their employment, in an area or in relationships, as well as because they have school-age children.
#
# However, from those aged in their late 70s onwards, the proportion of people moving rises slightly. There are many reasons why people of this age may wish to move, including being closer to their family, downsizing, or to access support and care.
#
# Figure 4 shows how the latest data have changed in percentage terms compared with the previous 12-month period. The largest increase is at age 68 (an increase of 28% (3,000 moves), due partly because of the large increase in the total number of 68 year-olds in the UK (up 178,000 from the previous 12-month period) as people born in the baby boom following the Second World War reach that age.

# International migration
# Estimates for international in/out/net are adjusted for visitor switcher, migrant switcher, asylum seeker and refugee flows.
#
# Special change
# Net special change figures include the effect of change in the estimated special populations from one year to the next that are reflected in the general population of England and Wales - those joining and leaving the special population will create a resulting inflow and outflow between the general population.

# There were 242 local authorities with more people moving in than out, of which 43 had a net inflow of over 10 people per 1,000. These were predominantly in the South East, South West and East of England.
#
# In the year to mid-2018, there were 140 local authorities with more people moving out than in, of which 30 had a net outflow of more than 10 people per 1,000. Of these 31, there were 19 in London, with the rest predominantly in the south and east.
#
# For the year to mid-2018, London as a whole had an overall net outflow of 11.7 per 1,000 people to other areas of England and Wales (Figure 8). As described in the 2017 mid-year estimates release, there is a distinctive age structure to these moves, with children (aged under 18 years) most likely to leave, followed by adults aged over 25 years. However, there was a net inflow among the 18 to 25 years population. Broadly this corresponds to families with children tending to leave London while young adults aged in their 20s tend to move to London.

# Many of the fastest-growing authorities have high net international migration
#
# Figure 6 shows a cluster of central London boroughs having the highest levels of net international migration in the year to mid-2018. It also shows a scattering of urban centres across England, Wales and Scotland with high international migration. These tend to have large student populations, such as Coventry, Newcastle-upon-Tyne and Oxford (these areas have high numbers of population aged 18 to 24 years and can be seen in Figure 7). However, the notable pattern from the map is that most of the UK has relatively similar levels of net international migration, as was the case in mid-2017.
#
# Internal migration for London continues to be negative
#
# There were 242 local authorities with more people moving in than out, of which 43 had a net inflow of over 10 people per 1,000. These were predominantly in the South East, South West and East of England.
#
# In the year to mid-2018, there were 140 local authorities with more people moving out than in, of which 30 had a net outflow of more than 10 people per 1,000. Of these 31, there were 19 in London, with the rest predominantly in the south and east.
#
# For the year to mid-2018, London as a whole had an overall net outflow of 11.7 per 1,000 people to other areas of England and Wales (Figure 8). As described in the 2017 mid-year estimates release, there is a distinctive age structure to these moves, with children (aged under 18 years) most likely to leave, followed by adults aged over 25 years. However, there was a net inflow among the 18 to 25 years population. Broadly this corresponds to families with children tending to leave London while young adults aged in their 20s tend to move to London.

# Flows are expressed per 1,000 to allow comparison where population sizes differ.

# In every region outside London, there was a net inflow of children and of adults aged 25 to 64 years. This was also true for the 65 years and over age group, except for very small net losses in the West Midlands and the North West. -->


An internal migrant is defined as someone who moves home from one geographical area to another. This may be between local authorities, regions or countries within the UK. Unlike with international migration, there is no internationally agreed definition.
{: .notice--info}

## Population change in the future
Should we have a table of pop 2018, 2028, 2038 (rows = wsx and districts)

<div id = 'population_18_28_38_table'></div>

Whilst the total population estimates and population change values in this table are rounded, percentages and ratios are calculated from unrounded values.
{: .notice--warning}

The latest population estimates for West Sussex indicate the county is home to more than 858,800 residents. Projections based on recent trends indicate that by 2028, the population in West Sussex will increase to more than 925,900 and by 2038, the resident population of West Sussex is expected to reach 976,900.

The figure below is a population pyramid. This visualises the same information that is in the West Sussex population by age and sex table above, but you can interact with it and change the area and change the year of estimate from 2001 to 2041.

The shape of the pyramid gives an indication of the
<h3 id = 'selected_p1_title'></h3>
<span class="mr-1">Area:</span>
<select id='selectAreasP1Button'></select>
<span class="mr-1">Year:</span>
<select id='selectYearsP1Button'></select>
<div id = 'pyramid_1_datavis'></div>

### What does this mean for ageing in the future?
In 2018, just over one in five residents (22%) in West Sussex was aged 65 years and over. Over the next decade, this is expected to increase to one in four (26%) and by 2038, 30% (almost one in three) residents will be aged 65 and over. This is much higher than national estimates (18% in 2018, 21% in 2028 and 24% in 2038).

### Test infographic image
<div id = 'info_graphi'></div>
</div>

{% capture notice-2 %}
Estimates for the future are primarily based on trends from the recent past.

Population projections are uncertain and become increasingly uncertain the further they are carried forward in time. They do not attempt to predict the impact that future government policies, changing economic circumstances or other factors might have on demographic behaviour.
{% endcapture %}

<div class="notice--info">{{notice-2 | markdownify}}</div>

  <!-- https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/ageing/articles/livinglongerandoldagedependencywhatdoesthefuturehold/2019-06-24 -->

An increase in the older population has implications for the economy in terms of providing services and state pensions; however, this economic impact will be affected by people living healthier lives for longer and increases in economic activity at older ages.

### The old age dependency ratio...
The old age dependency ratio measures the number of people of state pension age (SPA) and over for every 1,000 people of working age (16 to SPA).

Women's state pension age increased to 65 between April 2016 and November 2018. From December 2018 the SPA for both men and women will increase to reach 66 by October 2020 (Pensions Act 2011). Between 2026 and 2027 SPA will increase to 67 years for both sexes (Pensions Act 2014), SPA will increase to 68 years for both men and women between 2044 and 2046 (Pensions Act 2007).

To calculate the population estimated to be of state pension age by year in this analysis, population estimates are applied to the state pension age matrix available from the Office for National Statistics (<a href = 'https://www.ons.gov.uk/file?uri=%2fpeoplepopulationandcommunity%2fpopulationandmigration%2fpopulationprojections%2fdatasets%2ftableofstatepensionagefactorspensionsact%2f2016based/pensionmatrixfor2016npp.xls'>available here</a>).

<span class="mr-1">Area:</span>
<select id='select_oadr_area_button'></select>
<div id = 'oadr_ts_viz'></div>

In England, there were...

In West Sussex...

Remember, this is not an ideal estimate of old age dependency as it assumes that all those above SPA are dependent and that all those of working age are economically active and not infact dependent themselves.

Technologies may change in the future such that people are able to stay healthier and independent for longer and the OADR measure may become less useful as more people work up to and beyond SPA; alternative measures that include economic activity may provide a more meaningful picture of economic dependency.

It should be noted that the old age dependency ratio estimates shown here have been calculated from the ONS mid year estimates and 2016 based population projections combined with the state pension age matrix. There may be slight differences in the old age dependency ratio estimates published by ONS for 2016-2014 (<a href = 'https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationprojections/datasets/populationofstatepensionageandworkingageandoldagedependencyratiosforlocalauthoritiesandregionsinengland'>available here</a>).
{: .notice--info}













