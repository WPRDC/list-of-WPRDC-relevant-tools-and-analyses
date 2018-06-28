# list-of-WPRDC-relevant-tools-and-analyses
List of WPRDC-relevant tools and data analyses. 

## Tools
- [WPRDC Property Dashboard](http://tools.wprdc.org/property-dashboard/) - The Regional Data Center's Property Dashboard integrates data from multiple data sources and provides it all in one place. We're happy to announce that the beta version of the tool is now live, and we built it in-house. 
- [WPRDC's Parcels n'at](http://tools.wprdc.org/parcels-n-at/) - Parcels n'at allows you to pull a variety of data by neighborhood, municipality, or even for a user-defined area using some of the embedded drawing tools. 

## Data analyses by dataset

### 311 Data
- [conorotompkins/pittsburgh_311](https://github.com/conorotompkins/pittsburgh_311) - Conor Tompkins' R-based analaysis of [Pittsburgh's 311 data](https://data.wprdc.org/dataset/311-data).
- [The Use of 311 Requests as a Measure of Neighborhood Conditions in the City of Pittsburgh](https://ucsur.pitt.edu/files/peq/peq_2017-03.pdf) - An article reporting on the analysis of [Pittsburgh's 311 data](https://data.wprdc.org/dataset/311-data), by UCSUR's own Don Musa, published in UCSUR's PEQ (Pittsburgh Economic Quarterly).
### Carnegie Library Wi-Fi Use Data
- [eleanortutt/codeforpgh-20180613](https://github.com/eleanortutt/codeforpgh-20180613) - Eleanor Tutt's demonstration of how to load data into Pandas dataframes and how to make choloropleth maps.
### [Crash Data](https://data.wprdc.org/dataset/allegheny-county-crash-data)
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb) - WPRDC data analysis of [Allegheny County crash data](https://data.wprdc.org/dataset/allegheny-county-crash-data), demonstrating a few methods for loading data from CKAN and manipulating data.
- [conorotompkins/allegheny_crashes](https://github.com/conorotompkins/allegheny_crashes) - Conor Tompkins' R-based analysis of [Allegheny County crash data](https://data.wprdc.org/dataset/allegheny-county-crash-data) and the accompanying [blog post](https://ctompkins.netlify.com/2018/06/27/car-crashes-in-allegheny-county/), showing some interesting visualizations.
### Crime Data
- [conorotompkins/pgh-crime](https://github.com/conorotompkins/pgh-crime) - Conor Tompkins' R-based analysis of [Pittsburgh crime data](https://data.wprdc.org/dataset?q=crime&sort=views_recent+desc).
### Dog License Data
- [nrfulton/pittdoggos](https://github.com/nrfulton/pittdoggos) - Nathan Fulton's Python scripts for analyzing county dog-license data and a simple Web page for searching dogs by name.
### Fatal Accidental Overdoses Data
- [conorotompkins/allegheny_overdoses](https://github.com/conorotompkins/allegheny_overdoses) - Conor Tompkins' R-based analaysis of the [County Fatal Accidental Overdoses data](https://data.wprdc.org/dataset/allegheny-county-fatal-accidental-overdoses).
### Healthy Ride Data
- [conorotompkins/healthy_ride](https://github.com/conorotompkins/healthy_ride) - Conor Tompkins' R-based analysis of Healthy Ride data.

## Examples demonstrating different skills

### Making bar charts
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb)
### Making SQL queries on WPRDC data
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb)
### Mapping
- [eleanortutt/codeforpgh-20180613](https://github.com/eleanortutt/codeforpgh-20180613)
### Pandas dataframes
- [eleanortutt/codeforpgh-20180613](https://github.com/eleanortutt/codeforpgh-20180613)
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb)
### Pulling WPRDC data through the CKAN API
- [WPRDC/Jupyter-notebooks-by-dataset/Crash-Data-Analysis](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/Crash-Data-Analysis.ipynb)
### Transforming from a long-format data table to a wide-format data table
- [WPRDC/Jupyter-notebooks-by-dataset/air-quality-exploration](https://github.com/WPRDC/Jupyter-notebooks-by-dataset/blob/master/air-quality-exploration.ipynb)

## Other data sources

### Tools
- [ljwolf/cenpy](https://github.com/ljwolf/cenpy) - A Python library for exploring and querying the US Census API and returning Pandas DataFrames.

## General tools for working with data
- [saulpw/visidata](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for discovering and arranging data. (It's basically a Swiss Army chainsaw for manipulating tabular data.)

## Contribute

Please contribute things that could be useful to others using [WPRDC ](https://www.wprdc.org)[data](https://data.wprdc.org), including scripts for data cleaning or analyzing data, Jupyter notebooks for particular datasets, and tools for manipulating and visualizing the data.
