# NYC-Restaurant-Grades-
McNulty - Project #3 at Metis | Spring 2018

This is the repository of my project on predicting NYC Health Inspection grades. This was completed in May 2018 as part of my Metis spring semester.

**Data** - my data was taken from [NYCOpenData](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/xx67-kt59) and the US Census. NYC Restaurant data ranged from 2014-May 2018. US Census data was joined in on the zip code level to help analyze the effects of neighborhood wealth on restaurant grades  

Note that this data was analyzed in a PostgreSQL database, so users may not be able to directly run all notebooks. I have also included a few pickle files in the Jupyter folder to help run the later notebooks

The above files are broken down in the following way

* **Jupyter** - contains the notebooks used to clean, parse and ultimately model the data. There are also a few pickles here as the data was originally in a PostgreSQL database on an AWS server
* **images** - images used during on my presentation
* **inspections2018_heatmap** - here I worked on creating a heatmap of restaurant grade success (as a percentage) by zip code across New York City. I've included a notebook as well as pickeled data so this can be run on its own. This was done with the Python library Folium.

Finally, I've also included my Google Slides presentation and speaker notes as PDF files here.
