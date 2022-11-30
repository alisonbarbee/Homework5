##Homework #5
Alison Barbee
R Programming Course - CSU
Nov. 30th, 2022

#The Data

This data was pulled from a Washington Post study that collected data on more than 52,000 criminal homicides over the past decade throughout some of America's largest cities. This data includes not only the location of the homicide but also includes the status of the case (whether an arrest was made), and some basic demographic information on the victim. The Washinton Post has mapped out each homicide, and identifed the arrest rates by the geography within each city. They shared the data analysis with local police department prior to their publication.

#Los Angeles Map

I chose to look through the Los Angeles, CA homicide data to create a map that shows the locations of homicides throughout the city. The layer underneath the data points shows the boundaries of LA county where Los Angeles is located. 

Create a map showing the locations of the homicides in that city, using the sf framework discussed in class. 

Use tigris to download boundaries for some sub-city geography (e.g., tracts, block groups, county subdivisions) to show as a layer underneath the points showing homicides. 

Use different facets for solved versus unsolved homicides

Use different colors to show the three race groups with the highest number of homicides for that city 
(you may find the fct_lump function from forcats useful for this).

#Links

Read the original article on the collected data: https://www.washingtonpost.com/graphics/2018/investigations/where-murders-go-unsolved/ 
The original GitHub repository: https://github.com/washingtonpost/data-homicides

