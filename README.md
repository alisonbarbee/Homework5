Homework #5
Alison Barbee
Nov. 30th, 2022


For the README.md file, you can create a text file in RStudio and save it as “README.md.” You can then write this file using Markdown syntax (like RMarkdown, but without any code chunks).

As you work on your homework, make sure you commit regularly (with helpful commit messages). 
You should have at least 15 commit messages in your history for the repo by the time you turn in the homework.


Select one of the following two figures to create for the homework:

Choice 1: Los Angeles
  Pick one city in the data. 
  Create a map showing the locations of the homicides in that city, using the sf framework discussed in class. 
  Use tigris to download boundaries for some sub-city geography (e.g., tracts, block groups, county subdivisions)   to show as a layer underneath the points showing homicides. 

  Use different facets for solved versus unsolved homicides and 
  different colors to show the three race groups with the highest number of homicides for that city 
    (you may find the fct_lump function from forcats useful for this).


Choice 2: Baltimore
Recreate the graph shown below. 
It shows monthly homicides in Baltimore, with a reference added for the date of the arrest of Freddie Gray and color used to show colder months (November through April) versus warmer months (May through October). There is a smooth line added to help show seasonal and long-term trends in this data.