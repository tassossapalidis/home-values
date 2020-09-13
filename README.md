# Objective
The purpose of this project is to create an animated choropleth map displaying the relative affordability Bay Area cities. Specifically, median 3-bedroom home values for each zip code are compared to the median 3-bedroom home value in the Bay Area. The result is the following GIF.

![alt text](https://github.com/tassossapalidis/home-values/blob/master/SF_Prices.gif)

# Files
- [**Notebook.ipynb**](Notebook.ipynb) contains all code and documentation.
- [**Zillow_ZHVI_3Bed.csv**](Zillow_ZHVI_3Bed.csv) contains the Zillow Home Value Index (ZHVI) values used in this analysis. This can be downloaded direclty from the [Zillow Research](https://www.zillow.com/research/data/ "Zillow Research") site.
- [**SF_Bay_Zip_Prefixes.csv**](SF_Bay_Zip_Prefixes.csv) specifies the zip codes located in the SF Bay Area and is derived from [Wikipedia's list of ZIP Code Prefixes](https://en.wikipedia.org/wiki/List_of_ZIP_Code_prefixes, "Wikipedia")
- [**SF_Bay_Area.geojson**](SF_Bay_Area.geojson) is used to map zip codes to a map location. This can be found on [data.sfgov.org](https://data.sfgov.org/Geographic-Locations-and-Boundaries/Bay-Area-ZIP-Codes/u5j3-svi6).

*Note that a ChromeDriver is needed to run the code in the Jupyter Lab file. This can be downloaded [here](https://chromedriver.chromium.org/).*
