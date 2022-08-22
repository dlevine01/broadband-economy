# Mapping connections between broadband expansion and equitable economic prosperity
## About the project
###### Abstract 

Access to broadband internet is vital for economic development, however no comprehensive research has connected measures of broadband availability and performance and economic success. This study detects correlation between past broadband expansion and subsequent economic growth across locales with certain base levels of economic performance. We identify the demographic and economic factors which correspond to lower broadband scores and also find the measures common in places which saw a boost in prosperity following broadband expansion. We found that there is a delayed correlation between an increase in broadband access and an increase in economic development. We combine broadband, economic, and equity considerations to locate the places that may achieve the most equitable and absolute gains from broadband expansion and present a prioritized list of counties. This project presents a new, nationwide, Census Tract-level composite dataset of broadband performance and an interactive map for exploration and use in further research.

This project was developed by Dan Levine, Max Magid, Kaiwen Zhang, and Zuda Yan as for [US Ignite](https://www.us-ignite.org) as a capstone project for the M.S. in Applied Urban Science at the [NYU Center for Urban Science + Progress](https://cusp.nyu.edu)

#### Read project details
Read the full technical report or final presentation slides in the ‘Project Materials’ [folder](/Project%20Materials)

#### Explore the data
This project developed nationwide, Tract-level data on economic performance and broadband access. The data can be explored through an [interactive map](https://usignite.carto.com/u/usignite-intern/builder/a7627f0d-a64d-44a3-892a-820b14c0dfab/embed).

## How to use this repo

This analysis is fully reproducible from the code included in this repo. 

The data sources we used are all open or public online. The notebooks in [1_get raw data](/1_get%20raw%20data) will download the data from the sources. (A few sources _are_ available online, but are glitchy when accessed through the code, so those data are already included in the raw data folder.)

Notebooks in the [2_process data](2_process%20data) folder clean, combine, and rescale the data.

Finally, notebooks in [3_analyze data](3_analyze%20data) analyze economic and broadband performance, look at equity of broadband availability, and measure the correlation between broadband improvement and subsequent economic growth.

This entire repo can be cloned to run locally or each notebook can be run in Google Colab. If you run the code yourself, run the notebooks in order as some the later stages depend on data processed at earlier stages. 

