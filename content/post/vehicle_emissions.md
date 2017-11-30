+++
date = "2017-11-30T12:01:00"
draft = false
tags = []
title = "Vehicle emissions prototype"
math = true
summary = """
Prototype map of personal vehicle emissions in SE Pennsylvania.
"""

+++

The map below simulates household-level use of personal vehicles, including annual miles driven and fuel efficiency, to reveal neighborhood-scale patterns in associated greenhouse gas emissions. Hover your mouse over individual neighborhoods for details.

The prototype's data inputs include the [American Community Survey](https://www.census.gov/programs-surveys/acs/), a restricted-use version of the [National Household Travel Survey](http://nhts.ornl.gov/), and the [EPA's Smart Location Database](https://www.epa.gov/smartgrowth/smart-location-mapping#SLD), among others. The underlying machine learning model uses a range of demographic and socio-spatial variables (e.g. the ["walkabilty" of a household's surroundings](/img/neighborhood_walkability.png)) to predict personal vehicle usage patterns.

<iframe src="/leaflet/Vehicle_emissions_prototype.html" width="100%" height="700"></iframe>
