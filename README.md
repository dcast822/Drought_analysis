# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 5: Drought Analysis
### By: Julio Cesar Hernandez-Krol, Son Nguyen and David Castillo

## Executive Summary

### Problem statement

Climate change has brought on numerous problems, for the scope of this project we will tackle on drought.  Drought can impact our food resources, impact citizens in certain areas, our agricultural industries and needs to be addressed by policy makers.  We are looking to work on a datetime series neural networks model, where we use historical drought data in order to predict future droughts from occurring.  

### Background Research

**Climate Change**

A collection of more than 200 leading health and medical journals declared a rise in global temperatures as the greatest threat to global public health(Choi-Schagrin, 2021). Rising global temperatures are just one of the many effects to be weary of with regard to climate change.  Climate change is often only spoken of as it regards to predictions made by computer models and also have a broader scientific basis in which models are just one part of the foundation(Rosen, 2021).

We have also seen other effects such as; ice sheets and glaciers shrinking while sea levels are rising, artic sea ice is disappearing, snow melts sooner, plants flower earlier.  Also, droughts, floods and wildfires have all become more extreme.(Rosen, 2021).

Climate can vary and some years are hotter/colder than others, some decades can bring about more hurricanes, and  long droughts have spanned during prior centuries.  However researchers have access to records that can give them data from over 1000 years.  Researchers have access to geologic records like tree rings, ice cores, corals and sediments that preserve information about prehistoric climates from long ago(Rosen, 2021). Global temperatures have been flat for centuries, but has taken a sharp turn upwards in the last 150 years(Rosen, 2021). There is also the increase in frequency and severity of phenomena like heat waves, floods and droughts.

**Droughts**

A drought can be generally understood as "a period of abnormally dry weather that goes on for long enough to have an impact on water supplies, farming, livestock operations, energy production and other activities"(Fountain, 2021). Droughts begin with less than normal precipitation which varies depending on the region. At the root of droughts are warmer temperatures and changing precipitation patterns, which are linked to emissions of carbon dioxide and other greenhouse gases into the atmosphere, where they trap the sun's heat(Fountain,2021). Excessive heat from climate change leads to winter snowpack melting faster affecting the availability of water throughout the year(Fountain,2021).

With respect to droughts, climate change has worsened them through the increasing evaporation, which has also lead to increased crop failures and risk of severe wildfires(Fountain,2021). According to the analysis of soil moisture content, "the drought that afflicted the American Southwest from 2000 to 2018 was almost 50 percent more severe because of climate change"(Fountain, 2020).  It was the worst drought in the region in over 1000 years(Rosen, 2021). Conditions are also of historic proportions in California, into the Pacific Northwest, much of the Intermountain West, and even the Northern Plains(Fountain, 2021).

While it is true that the southwest and parts of southern California are desert, this makes them more sensitive to changes in precipitation patterns. What would have been moderate droughts are now made severe due to the aforementioned increase in temperatures and shifts in precipitation.  

**United States Drought Monitor(USDM)**

The USDM is a collaboration of several federal agencies and the University of Nebraska-Lincoln(Fountain,2021).  They assess the severity of drought in a given area, ranking it from moderate to exceptional. They take into account, precipitation totals, snowpack, stream flows and soil moisture measurements, and use images from satellites to assess the health of vegetation(Lincoln, 2021).

The USDM website itself explains that its map identifies areas of drought and labels them by intensity. D1 is the least intense level and D4 the most intense. D0 areas are not in drought, but are experiencing abnormally dry conditions that indicate a possible turn into drought or recently recovering from a drought but not quite back to normal.  
The USDM includes Standardized Precipitation Index(SPI), Palmer Drought Severity Index(PDSI), USGS Weekly Streamflow(percentiles), CPC Soil Moisture Models(percentiles) and Objective Drought indicator blends(percentiles).  The USDM relies on experts to synthesize this data and work with local observers to interpret the information.  The USDM makes clear that it is not a forecast, it looks backward which is why we thought it would be good to add a predictive component to this tool via a Date Time Series model.

**References**
