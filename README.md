# power-plant
Data visualization for global power plan data

## Description 
The project employs [plotly](https://plot.ly) to provide data visualization based on global power plan information. 

## Data 
The data file is available at [World Resources Institute](http://datasets.wri.org/dataset/globalpowerplantdatabase). 

1. Columns 
```
	- `country` (text): 3 character country code corresponding to the ISO 3166-1 alpha-3 specification [4]
	- `country_long` (text): longer form of the country designation
	- `name` (text): name or title of the power plant, generally in Romanized form
	- `gppd_idnr` (text): 10 or 12 character identifier for the power plant
	- `capacity_mw` (number): electrical generating capacity in megawatts
	- `latitude` (number): geolocation in decimal degrees; WGS84 (EPSG:4326)
	- `longitude` (number): geolocation in decimal degrees; WGS84 (EPSG:4326)
	- `fuel1` (text): energy source used in electricity generation or export
	- `fuel2` (text): energy source used in electricity generation or export
	- `fuel3` (text): energy source used in electricity generation or export
	- `fuel4` (text): energy source used in electricity generation or export
	- `commissioning_year` (number): year of plant operation, weighted by unit-capacity when data is available
	- `owner` (text): majority shareholder of the power plant, generally in Romanized form
	- `source` (text): entity reporting the data; could be an organization, report, or document, generally in Romanized form
	- `url` (text): web document corresponding to the `source` field
	- `geolocation_source` (text): attribution for geolocation information
	- `year_of_capacity_data` (number): year the capacity information was reported
	- `generation_gwh_2013` (number): electricity generation in gigawatt-hours reported for the year 2013 
	- `generation_gwh_2014` (number): electricity generation in gigawatt-hours reported for the year 2014
	- `generation_gwh_2015` (number): electricity generation in gigawatt-hours reported for the year 2015 
	- `generation_gwh_2016` (number): electricity generation in gigawatt-hours reported for the year 2016
	- `estimated_generation_gwh` (number): estimated annual electricity generation in gigawatt-hours for the year 2014 (see [0])

```
2. Citation
Global Energy Observatory, Google, KTH Royal Institute of Technology in Stockholm, Enipedia, World Resources Institute. 2018. Global Power Plant Database. Published on Resource Watch and Google Earth Engine; http://resourcewatch.org/ https://earthengine.google.com/. 









