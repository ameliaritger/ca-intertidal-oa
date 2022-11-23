# California intertidal ocean acidification project 

*This repository contains the data and analysis related to Amelia Ritger's research on ocean acidification in California intertidal systems.*

These data were collected using Durafet-based pH sensors and HOBO temperature loggers with support from Dr. Francis Chan (OSU). Sensors were deployed in the rocky intertidal zone at three sites - Bodega Bay, Lompoc Landing, and Alegria - from May 2021 until November 2021. Sensors collected temperature and pH measurements every 15 minutes. Sites were selected because they 1) had been studied before, which would allow us to build upon historical datasets, 2) capture variation in oceanographic conditions attributed to California's two upwelling regimes, and 3) limit public access, which protects the valuable sensor equipment. 

![Map of study sites in California](/media/site-map.png?raw=true)

This repo is maintained by Hofmann Lab graduate student Amelia Ritger (GitHub: [@ameliaritger](https://github.com/ameliaritger)) at the University of California, Santa Barbara in the Department of Ecology, Evolution, & Marine Biology. In 2021, a group of UCSB undergraduate students worked with Amelia to create a Shiny app using these data to teach local high school students about ocean acidification. The Shiny app can be found [here](https://ameliaritger.shinyapps.io/intertidal-oa-module/). 

# Code

file name | analysis overview | description 
---|---|-----------
filter-for-vis.Rmd | Smoothing pH and temperature data for easier visualization | Description
lol-analysis.Rmd | Lompoc Landing sensor data wrangling without detiding the data | Description
sensor-analysis.Rmd | All sites sensor data wrangling for comparative analysis  | Description

# Data 
*/data/hobo_alg.csv*  raw data

*/data/hobo_bml.csv*  raw data

*/data/hobo_lol.csv*  raw data

*/data/lol_all.csv*  raw data

*/data/sensor-data_all.csv*  raw data

*/data/sensor-data_detided.csv*  raw data

*/data/wave-july2021.csv*  raw data

# Photos of the sensors deployed in the field
At Alegria
![Alt text](/media/alg-horizon.jpg?raw=true)

At Lompoc Landing
![Alt text](/media/lol-horizon.jpg?raw=true) 

At Bodega Bay
![Alt text](/media/bodega-sun.jpg?raw=true)