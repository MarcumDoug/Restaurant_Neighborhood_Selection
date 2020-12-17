# Restaurant Neighborhood Selection
Capstone Project for IBM Data Science Professional Certificate via Coursera (First True Data Science Project)

## Introduction/Business Problem
The basis of this study is to help a small group of investors planning to open their first U.S. based brewery / restaurant expansion in Toronto. Being that Toronto is the most populated city in Canada, and continually ranks as an important global city based on a high quality of living, the choice to expand into the neighbor of the north market was an easy selection for the investing group. However, with limited knowledge of the Toronto market, the group of investors have selected us to assist in the selection of which areas of Toronto will facilitate a launch of their brewery / restaurant expansion.  

They are interested in building in an area that meets the following criteria:
•	A neighborhood with an average to above average median total population
•	Above average populations of 25-40-year-old male and female professionals
•	A high concentration of the population having secondary education
•	Average to above average median net household incomes

With these criteria given by the investing group, based on previous success in other markets, the objective is to locate and recommend to the investors, the target audience, which neighborhood(s) of Toronto will be the best choice to start their international growth plan. The information gained will assist in choosing the right location by providing data about the population of each neighborhood, in addition to other established venues present in these areas.

Additionally, this information could be of interest to other potential investors looking to open a new restaurant or entertainment venue in Toronto.

## Data
The necessary information needed by the investing group will come from the following sources:

•	[City of Toronto Neighborhood Profiles](https://www.toronto.ca/city-government/data-research-maps/neighbourhoods-communities/neighbourhood-profiles/) for providing an overview of the neighborhoods in Toronto

•	[City of Toronto Open Data Catalogue:](https://open.toronto.ca/#8c732154-5012-9afe-d0cd-ba3ffc813d5a) The Census of Population is held across Canada every five years (the last being in 2016), and collects data about age and sex, families and households, language, immigration and internal migration, ethnocultural diversity, Aboriginal peoples, housing, education, income, and labor. City of Toronto Neighborhood Profiles use this Census data to provide a portrait of the demographic, social and economic characteristics of the people and households in each City of Toronto neighborhood. The profiles present selected highlights from the data, but these accompanying data files provide the full data set assembled for each neighborhood.

In these profiles of the City of Toronto's 140 social planning neighborhoods. These social planning neighborhoods were developed by the City of Toronto to help government and community organizations with local planning by providing socio-economic data at a meaningful geographic area. The boundaries of these social planning neighborhoods are consistent over time, allowing for comparison between Census years. Neighborhood level data from a variety of other sources are also available through the City's Wellbeing Toronto mapping application and here on the Open Data portal.

Each data point in this file is presented for the City's 140 neighborhoods, as well as for the City of Toronto as a whole. The data is sourced from several Census tables released by Statistics Canada. The general Census Profile is the main source table for this data, but other Census tables have also been used to provide additional information. CSV File
 
•	City of Toronto Neighborhood Shapes for mapping: GeoJSON File
 
•	[Wikipedia for Toronto Neighborhood Borough Designation:](https://en.wikipedia.org/wiki/List_of_city-designated_neighbourhoods_in_Toronto) Each of the 140 social planning neighborhoods of Toronto reside within a defined borough. While the City of Toronto is a singular municipality, the 140 neighborhoods are still grouped into six distinct boroughs.
 
•	[Foursquare API](https://developer.foursquare.com/developer/) to collect information on other venues/competitors in the neighborhoods of Toronto
