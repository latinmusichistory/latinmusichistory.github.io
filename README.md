# Website : [https://latinmusichistory.github.io/index.html](https://latinmusichistory.github.io/index.html)
# About

by Michael R, 11/21/2018

This project was made in a few days put together using only "Rstudio".
To make something similair, get familiar with the "R" language then use the following files with Rstudio:

"1-example.rmd" : Used to get data from spotify datasets. Redirects to another repository of mine for the actual data. Some editing is needed to make it gather more than a week of data. The file is rather messy, so take your time to understand what different parts of it do. Also get familiar with the libraries it includes to get the spotify data. The numbers made by it are then put back into the "map.geojson" it refers to, which is a map of latin america. Data is split up by country like that.

"map.geojson" : The map file used to display things and store some data by region. You can edit the file directly, but it's preferably edited through the .rmd files.

"index.rmd", "tempo.rmd", "loudness.rmd", etc. : These are the R files that make the html files used on people's browsers. In other words, displaying the data is done through these. Edit them then press "knit" at the top of Rstudio to make updated html files / pages.

"(underscore)site.yml" : This makes all the html pages redirect to one another through the menu. Note the formatting. Edit this when removing / adding pages.

Questions can be directed to mriadzaky@fordham.edu.
