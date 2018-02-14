+++
date = "2017-11-30T12:00:00"
draft = false
tags = []
title = "Environmental policy prototype"
math = true
summary = """
Prototype map of support for environmental policies in SE Pennsylvania.
"""

+++

The map below simulates person-level support for environmental policies along an integer index ranging from 0 to 4. Hover your mouse over individual neighborhoods to see the estimated portion of the population at each level of support.

The prototype demonstrates our ability to simulate categorical/discrete survey responses at the level of individuals. See the [vehicle emissions prototype](/post/vehicle_emissions) for an alternative example simulating numerical/continuous phenomena at the household level.

The environmental policy index is based on binary support/oppose reponses to four survey questions in Harvard University's [Cooperative Congressional Election Study](https://cces.gov.harvard.edu/). The underlying machine learning model uses a range of demographic and socio-spatial variables (e.g. an individual's [proximity to a Whole Foods grocery](/img/wholefoods_proximity.png)) to predict support levels.

<iframe seamless src="/leaflet/Environmental_policy_prototype.html" width="100%" height="700"></iframe>
