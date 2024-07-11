# Air-Quality-Data-Processing

This repository is dedicated to processing of meteorological data, namelly, atmospheric pollution. 
Currently it contains two Jupiter Notebook scripts.

In this work, data from the Copernicus Atmosphere Monitoring Service (CAMS) were used https://ads.atmosphere.copernicus.eu/cdsapp#!/dataset/cams-europe-air-quality-forecasts?tab=form.

The first script downloadgrib.ipynb retrieves and downloads air quality data for a specified date range and geographic area from the Copernicus Atmosphere Monitoring Service (CAMS) using provided API credentials.

- describe the choice of pollutants, area, level, date
- describe these API credentials

The second script gribtocsv.ipynb processes all GRIB and GRIB2 files in a specified directory by extracting meteorological air quality data, organizing this data into tables using astropy, and saving these tables as CSV files. This allows the data to be easily analyzed and utilized in various applications.

