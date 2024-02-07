# list-of-WPRDC-relevant-tools-and-analyses
A collection of WPRDC-relevant tools and data analyses.

## Tools
- [WPRDC Property Dashboard](http://tools.wprdc.org/property-dashboard/) - The Regional Data Center's Property Dashboard integrates data from multiple data sources and provides it all in one place. We're happy to announce that the beta version of the tool is now live, and we built it in-house.
- [WPRDC's Parcels n'at](http://tools.wprdc.org/parcels-n-at/) - Parcels n'at allows you to pull a variety of data by neighborhood, municipality, or even for a user-defined area using some of the embedded drawing tools.

## Data analyses by dataset

### [311 Data](https://data.wprdc.org/dataset/311-data)
- [conorotompkins/pittsburgh_311](https://github.com/conorotompkins/pittsburgh_311) - Conor Tompkins' R-based analaysis of [Pittsburgh's 311 data](https://data.wprdc.org/dataset/311-data).
- [The Use of 311 Requests as a Measure of Neighborhood Conditions in the City of Pittsburgh](https://ucsur.pitt.edu/files/peq/peq_2017-03.pdf) - An article reporting on the analysis of [Pittsburgh's 311 data](https://data.wprdc.org/dataset/311-data), by UCSUR's own Don Musa, published in UCSUR's PEQ (Pittsburgh Economic Quarterly).
### [Air-Quality Data](https://data.wprdc.org/dataset/allegheny-county-air-quality)
- [WPRDC/Jupyter-notebooks-by-dataset/air-quality-exploration](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/air-quality-exploration.ipynb) - A demonstration of how to dig into [the Allegheny County air-quality data](https://data.wprdc.org/dataset/allegheny-county-air-quality) to pull out and plot particular measurements.
### [Carnegie Library Wi-Fi Use Data](https://data.wprdc.org/dataset/clp-public-wifi)
- [eleanortutt/codeforpgh-20180613](https://github.com/eleanortutt/codeforpgh-20180613) - Eleanor Tutt's demonstration of how to load data into Pandas dataframes and how to make choloropleth maps.
### [Crash Data](https://data.wprdc.org/dataset/allegheny-county-crash-data)
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb) - WPRDC data analysis of [Allegheny County crash data](https://data.wprdc.org/dataset/allegheny-county-crash-data), demonstrating a few methods for loading data from CKAN and manipulating data.
- [conorotompkins/allegheny_crashes](https://github.com/conorotompkins/allegheny_crashes) - Conor Tompkins' R-based analysis of [Allegheny County crash data](https://data.wprdc.org/dataset/allegheny-county-crash-data) and the accompanying [blog post](https://ctompkins.netlify.app/post/car-crashes-in-allegheny-county/), showing some interesting visualizations.
### [Crime Data](https://data.wprdc.org/dataset?q=crime&sort=views_recent+desc)
- [conorotompkins/pgh-crime](https://github.com/conorotompkins/pgh-crime) - Conor Tompkins' R-based analysis of [Pittsburgh crime data](https://data.wprdc.org/dataset?q=crime&sort=views_recent+desc).
- [ZacharyGoldstein/pgh-juvenile-arrests](https://github.com/ZacharyGoldstein/pgh-juvenile-arrests) - Zach Goldstein's analysis of [Pittsburgh arrests data](https://data.wprdc.org/dataset/arrest-data) for a [WESA article on juvenile arrests](http://www.wesa.fm/post/pittsburgh-s-trend-juvenile-arrests-explained-4-charts-and-maps). You can also view the [Jupyter notebook with plots](https://nbviewer.jupyter.org/github/ZacharyGoldstein/pgh-juvenile-arrests/blob/master/Arrest%20Data%20EDA.ipynb).
### [Dog-License Data](https://data.wprdc.org/dataset/allegheny-county-dog-licenses)
- [nrfulton/pittdoggos](https://github.com/nrfulton/pittdoggos) - Nathan Fulton's Python scripts for analyzing county (but not city) dog-license data and a simple Web page for searching dogs by name.
### [Fatal Accidental Overdoses Data](https://data.wprdc.org/dataset/allegheny-county-fatal-accidental-overdoses)
- [conorotompkins/allegheny_overdoses](https://github.com/conorotompkins/allegheny_overdoses) - Conor Tompkins' R-based analaysis of the [County Fatal Accidental Overdoses data](https://data.wprdc.org/dataset/allegheny-county-fatal-accidental-overdoses).
### [Healthy Ride Data](https://data.wprdc.org/dataset?organization=healthy-ride)
- [conorotompkins/healthy_ride](https://github.com/conorotompkins/healthy_ride) - Conor Tompkins' R-based analysis of [Healthy Ride data](https://data.wprdc.org/dataset?organization=healthy-ride), now updated to include [time-series forecasting](https://ctompkins.netlify.app/post/forecasting-healthy-ride-ridership-with-prophet/).
### [Pittsburgh Steps Data](https://data.wprdc.org/dataset/city-steps)
- [sdl60660/pittsburgh-steps](https://github.com/sdl60660/pittsburgh-steps) - [Sam Learner](https://www.samlearner.com/) made this series of visualizations of the [Pittsburgh Steps dataset](https://data.wprdc.org/dataset/city-steps), that you can scroll through to learn about the many public staircases in Pittsburgh. Made with D3, Svelte, and Mapbox.
### [Property Assessments Data](https://data.wprdc.org/dataset/property-assessments) + [Property Sales Data](https://data.wprdc.org/dataset/real-estate-sales)
- [Fair Housing Project](https://github.com/aminrahimian/data-for-good/blob/main/project/PreviousProjects/HousingProject/housing-project.ipynb) - A class project by Tara Schroth, Stephen Vandrak, Gloria Givler, and Annie Goodwin for Professor Amin Rahimian's Data for Social Good course at the University of Pittsburgh. Demonstrates joining tables, cleaning, and analyzing using Pandas dataframes. Also demonstrates geocoding (using [geopy](https://geopy.readthedocs.io/en/stable/)) and mapping, and uses the [Community Assets dataset](https://data.wprdc.org/dataset/allegheny-county-assets) for Allegheny County.
### [Toxics Release Inventory](https://data.wprdc.org/dataset/toxic-release-inventory)
- The following is not an analysis specifically of the WPRDC dataset, but it's based partially on the source of that dataset (the EPA's [Toxics Release Inventory](https://www.epa.gov/toxics-release-inventory-tri-program)). From [the "Data is Plural" newsletter](https://www.data-is-plural.com/archive/2021-11-10-edition/): 
     > ProPublica published what it’s calling "[the most detailed map of cancer-causing industrial air pollution in the U.S.](https://projects.propublica.org/toxmap/)," along with an [investigation](https://www.propublica.org/article/toxmap-poison-in-the-air) based on the map's revelations. In a [methodology article](https://www.propublica.org/article/how-we-created-the-most-detailed-map-ever-of-cancer-causing-industrial-air-pollution), reporters explain how they analyzed billions of rows of data from the Environmental Protection Agency's [Risk-Screening Environmental Indicators model](https://www.epa.gov/rsei), which "takes a variety of inputs, including emissions data, weather modeling, and facility specific information, and puts out estimated concentrations of toxic chemicals in the air around industrial facilities." The EPA [publishes the model's output](https://www.epa.gov/rsei/ways-get-rsei-results) as bulk downloads, in an online dashboard, and in other formats.

## Examples demonstrating different skills

### Python
#### Learning Python/Jupyter notebooks/data analysis
- [WPRDC/urban-informatics-and-visualization](https://github.com/WPRDC/urban-informatics-and-visualization) - A WPRDC fork of Paul Waddell's course materials for Urban Informatics and Visualization. These Jupyter notebooks cover Python/Jupyter fundamentals, cleaning/manipulating/analyzing/visualizing/mapping data, and using Web APIs for getting and posting data.
#### Making bar charts
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb)
#### Making SQL queries on WPRDC data
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb)
#### Mapping
- [eleanortutt/codeforpgh-20180613](https://github.com/eleanortutt/codeforpgh-20180613)
- [thoo/EMS-Dispatches-Pittsburgh/plotly_map_plot.ipynb](https://github.com/thoo/EMS-Dispatches-Pittsburgh/blob/master/plotly_map_plot.ipynb)
#### Pandas dataframes
- [eleanortutt/codeforpgh-20180613](https://github.com/eleanortutt/codeforpgh-20180613)
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb)
- [thoo/EMS-Dispatches-Pittsburgh](https://github.com/thoo/EMS-Dispatches-Pittsburgh)
#### Pulling WPRDC data through the CKAN API
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb)
#### Transforming from a long-format data table to a wide-format data table
- [WPRDC/Jupyter-notebooks-by-dataset/air-quality-exploration](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/air-quality-exploration.ipynb)

### R
#### Learning R
- [Tutorial on using R to analyze pothole data](https://ctompkins.netlify.app/post/r-311-pothole-workshop-code-for-pittsburgh/) - Material from a workshop run by Conor Tompkins, using Pittsburgh's 311 data on potholes to teach the basics of using R (including manipulating data and making charts and maps).
#### Principal component analysis in R
- [Principal Component Analysis in R](https://ctompkins.netlify.app/post/exploring-311-data-with-pca/) - A blog post explaining the application of prinicpal component analysis to Pittsburgh's 311 data.
#### Time-series forecasting in R
- [Forecasting Healthy Ride ridership](https://ctompkins.netlify.app/post/forecasting-healthy-ride-ridership-with-prophet/) - A blog post describing the use of the `prophet` package to extract seasonality features and predict the variation in Healthy Ride bike-ride counts.
#### CKAN API usage under R + debugging a broken SQL query
- [Using the CKAN API wrapper + converting string fields to integers in SQL queries](https://gist.github.com/drw/3fa37a32dcb49d42820347b8b735bec3) - Addressing a common pitfall when running SQL queries, this R script shows how to convert a string field to an integer and then use it in the WHERE clause of a SQL query. This also gives a simple example of using the ckanr wrapper package to more easily use the CKAN API.
#### Handling Census data + network analysis in R
- [Analyzing commuter patterns in Allegheny County](https://ctompkins.netlify.app/post/analyzing-commuter-patterns-in-allegheny-county/) - Conor Tompkins describes how to use R to manipulate Census data about commuting to study and map the most common starting and ending points for travelling between work and home, revealing that a huge number of people commute to downtown Pittsburgh with sizable numbers travelling to work in Oakland, Findlay Township, Moon Township, and Robinson Township.

## Useful tools and code libraries
### General tools for working with data
- [saulpw/visidata](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for discovering and arranging data. (It's basically a Swiss Army chainsaw for manipulating tabular data.)

### WPRDC-specific tools
- [Downstream](https://tools.wprdc.org/downstream) - An online tool for downloading any tabular data on the WPRDC data portal (even very large tables) as a CSV or TSV file. Small- to medium-sized tables may also be downloaded as Excel files.

### Code for dealing with Census data
- [ljwolf/cenpy](https://github.com/ljwolf/cenpy) - A Python library for exploring and querying the US Census API and returning Pandas DataFrames.
- [datamade/census](https://github.com/datamade/census) - A Python wrapper for the U.S. Census API.
- [datadesk/census-error-analyzer](https://github.com/datadesk/census-error-analyzer) - Given two Census values and the corresponding margins of error, this Python library can do an analysis to determine whether there is a statistically significant difference between them.

### Code for geospatial manipulation
- [mggg/maup](https://github.com/mggg/maup) - "The geospatial toolkit for redistricting data", a Python package designed to facilitate conversion between spatial regions used for elections (e.g., precincts) and spatial regions used by the Census to collect demographic information (e.g., blocks).

### Code/service for calculating routes between locations
- [Jupyter notebook examples](https://github.com/GIScience/openrouteservice-examples/) of how to use [the API](https://openrouteservice.org/) of the [OpenRouteService routing calculator](https://maps.openrouteservice.org/), which currently has a generous free tier, providing not just routing/directions, but maps, geocoding, isochrones, and elevation information.

## Other relevant data
- See our [Other Useful Datasets GitHub repo](https://github.com/WPRDC/other-useful-datasets/tree/main) for links to non-WPRDC datasets that could be helpful when working with WPRDC datasets.

## Contribute

Please contribute things that could be useful to others using [WPRDC ](https://www.wprdc.org)[data](https://data.wprdc.org), including scripts for data cleaning or analyzing data, Jupyter notebooks for particular datasets, and tools for manipulating and visualizing the data.
