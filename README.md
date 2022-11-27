Take the following steps to set up your GitHub repository for the homework (we will work on this as an in-course exercise):

Set up a local (i.e., on your computer) R project with subdirectories for the data, writing (this is where you’ll put your Rmarkdown file and the output file), and figures.

Download the Washington Post data and save it in an appropriate place in this R project directory.

Initialize git for the R project and make your initial commit.

Create an RMarkdown file for your homework answers in the appropriate subdirectory and save it. 

Commit this change with an appropriate commit message. (At this stage, you can look at your “History” in the git commit window to see the changes you’ve made so far.)

Login to your GitHub account and create a new, blank repo with the same name as your R project. (If you have not already set up an SSH key to make it easier to push back and forth between your computer and GitHub, do so now.)

On your computer, specify your GitHub repository as the remote for your project and do an initial push to send all the files to the GitHub repo. Look at your repository on GitHub to make sure it worked.
Add a README.md file to the top level of your R project (on your local computer) using Markdown syntax and then commit the change locally and push to your GitHub repository.
For the README.md file, you can create a text file in RStudio and save it as “README.md.” You can then write this file using Markdown syntax (like RMarkdown, but without any code chunks).

As you work on your homework, make sure you commit regularly (with helpful commit messages). You should have at least 15 commit messages in your history for the repo by the time you turn in the homework.

Select one of the following two figures to create for the homework:

Choice 1: Pick one city in the data. Create a map showing the locations of the homicides in that city, using the sf framework discussed in class. Use tigris to download boundaries for some sub-city geography (e.g., tracts, block groups, county subdivisions) to show as a layer underneath the points showing homicides. Use different facets for solved versus unsolved homicides and different colors to show the three race groups with the highest number of homicides for that city (you may find the fct_lump function from forcats useful for this).
Choice 2: Recreate the graph shown below. It shows monthly homicides in Baltimore, with a reference added for the date of the arrest of Freddie Gray and color used to show colder months (November through April) versus warmer months (May through October). There is a smooth line added to help show seasonal and long-term trends in this data.