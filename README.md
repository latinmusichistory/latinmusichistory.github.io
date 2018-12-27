# Website : [https://latinmusichistory.github.io/index.html](https://latinmusichistory.github.io/index.html)
# About

by Michael R, 11/21/2018

This project was made in a few days put together using only "Rstudio". You'll want to download that from [here](https://www.rstudio.com/products/rstudio/#Desktop).
To make a similair project / edit this one, first, use "[Github for Desktop](https://desktop.github.com/)" to download all the files to your computer. 
Then, get familiar with the "R" language and use the following files with Rstudio:

"1-example.rmd" : Used to get data from spotify datasets. Redirects to another repository of mine for the actual data. Some editing is needed to make it gather more than a week of data. The file is rather messy, so take your time to understand what different parts of it do. Also get familiar with the libraries it includes to get the spotify data. The numbers made by it are then put back into the "map.geojson" it refers to, which is a map of latin america. Data is split up by country like that.

For an idea of what data you can use, refer to [this](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/) page under "Audio Features Object". Genres can also be used by getting the artist and finding associated genres, like I did, so also keep that in mind.

"map.geojson" : The map file used to display things and store some data by region. You can edit the file directly, but it's preferably edited through the .rmd files. To view it on its own you can use [this](http://geojson.io/) site.

"index.rmd", "tempo.rmd", "loudness.rmd", etc. : These are the R files that make the html files used on people's browsers. In other words, displaying the data is done through these. Edit them then press "knit" at the top of Rstudio to make updated html files / pages.

"(underscore)site.yml" : This makes all the html pages redirect to one another through the menu. Note the formatting. Edit this when removing / adding pages.

Questions can be directed to mriadzaky@fordham.edu.
