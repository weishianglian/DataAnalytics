# Data Description from Kaggle

## Context
The UK government amassed traffic data from 2000 and 2016, recording over 1.6 million accidents in the process and making this one of the most comprehensive traffic data sets out there. It's a huge picture of a country undergoing change.  

Note that all the contained accident data comes from police reports, so this data does not include minor incidents.  

## Content
`ukTrafficAADF.csv` tracks how much traffic there was on all major roads in the given time period (2000 through 2016). AADT, the core statistic included in this file, stands for "Average Annual Daily Flow", and is a measure of how activity a road segment based on how many vehicle trips traverse it. The [AADT page on Wikipedia](https://en.wikipedia.org/wiki/Annual_average_daily_traffic) is a good reference on the subject.  

Accidents data is split across three CSV files: `accidents_2005_to_2007.csv`, `accidents_2009_to_2011.csv`, and `accidents_2012_to_2014.csv`. These three files together constitute 1.6 million traffic accidents. The total time period is 2005 through 2014, but 2008 is missing.

A data dictionary for the raw dataset at large is available from the UK Department of Transport website [here](http://data.dft.gov.uk/gb-traffic-matrix/all-traffic-data-metadata.pdf). For descriptions of individual columns, see the [column metadata](https://www.kaggle.com/daveianhickey/2000-16-traffic-flow-england-scotland-wales/data).

## Acknowledgements
The license for this dataset is the Open Givernment Licence used by all data on data.gov.uk ([here](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)). The raw datasets are available from the UK Department of Transport website [here](https://www.dft.gov.uk/traffic-counts/download.php).

## Inspiration
* How has changing traffic flow impacted accidents?
* Can we predict accident rates over time? What might improve accident rates?
* Plot interactive maps of changing trends, e.g. How has London has changed for cyclists? Busiest roads in the nation?
* Which areas never change and why? Identify infrastructure needs, failings and successes.
* How have Rural and Urban areas differed (see `RoadCategory`)? How about the differences between England, Scotland, and Wales?
* The UK government also like to look at miles driven. You can do this by multiplying the AADF by the corresponding length of road (link length) and by the number of days in the years. What does this tell you about UK roads?