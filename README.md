# MBTA Stations Dataset
*Finnley Autumn Rogers* | 2024-07-26

While working with a dataset of Boston BlueBikes station location data I realized there is no easily available dataset of MBTA rapid transit station locations. The MBTA makes a lot of data available publicly at their [Open Data Portal](https://mbta-massdot.opendata.arcgis.com/), but the majority of that is designed for GIS systems, and it does not seem to offer a basic dataset of geocoded station locations. 

"Needing" this data (and needing a refresher on web scraping), I've assembled this dataset by scraping [this](https://www.mbta.com/stops/subway) page from the MBTA's website listing all station stops and linking to each stops info page.

You can download the final data set in the data folder

The code is available in the jupyter notebook ```mbta_scraper.ipynb``` right now, I'm working on a full command line function at the moment to make grabbing this data faster in the future. 

