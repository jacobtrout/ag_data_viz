## Jacob Trout

## Project Description
This project will explore the agricultural production in the united states across time and region. The first component of the project will be descriptive. Using county-level crop data, I will examine how domestic food stuffs production has changed between the 1960s and the present. This will be done by examining changes in total production, composition in crop type, the productivity of land, etc.  

After performing these exploratory investigations, I will layer in additional data sources on potential drivers of the identified changes. I will want to compare climate data over time, pricing information, and potentially other sources. I hope to be able to highlight some potential causal mechanisms. 

## Sources

1)	NASS Quick Stats Data
The NASS has annual data from the agricultural survey on production of all major food stuffs broken out by county, state, and region, dating back deep into the 20th century. There is also census data on variety of other agriculture-related topics on land usage, expenses, income, energy usage. 

https://catalog.data.gov/dataset/quick-stats-agricultural-database

There are over 50 million rows and 17 columns. When I filter to solely data in the Field Crops, Fruit & Tree Nuts, and Vegetable Groups available at the county level, there are about 7.5 million observations.

2)	National Centers for Environmental Information

Supposedly, there is data on climate data (rain fall, temperatures, disasters) but the website says it is currently down due to the flooding in Asheville, NC. So I’ve been able to fully examine it but I will try to acquire data like this if it is not available soon. 

https://www.ncei.noaa.gov/node/6696

## Questions

Based on the format of all this data and the size, I am figuring that I might need to compile it in a SQLite database (or something like that). Does that seem like a good approach or do you have a better idea? 