Table of Content
================
* [Climate_Speeches](#Climate_Speeches)
  * [Description](#description)
  * [Datasets](#datasets)
  * [Installation Requirements](#installation-requirements)
  * [Licensing](#licensing)
  * [Author](#Authors)

# Interactive-Covid-19-Dashboard


## Description
A collaborative work of building an interactive Covid-19 dashboard to provide insights about COVID globally by students from the Digital Sciences Track of Center for Research and Interdiscplinarity. 

## Datasets
The data sets are from the open data of [Jonhs Hopkins University](https://github.com/CSSEGISandData/COVID-19)
* Dataset_COVID_Death_complete.csv
* Dataset_COVID_confiremed_complete.csv
* Dataset_COVID_recovered_complete.csv

Columns in the datasets:

- `Country / region`: identifies the name of the country
- `Province / state`: identifies the name of the states
- `Latitude`: the geographic coordinates that specifies the north – south position of a point on the Earth's surface.
- `Longitude`: the geographic coordinates that specifies the east – west position of a point on the Earth's surface.
- `Date`: identifies the cumulative cases per day in each of the countries.

To calulcate the normalization we acquire to get the population of the each country https://www.kaggle.com/tanuprabhu/population-by-country-2020 and we only used `Country and Population`. 


## Installation Requirements
- Download Zip
```
Code - Download ZIP
```

- Clone this repository with this command
```
git clone https://github.com/soledadli/interactive-Covid-19-dashboard.git
```
- Install the project dependencies run pip install -r requirements.txt
```
pip install -r requirements.txt
```
- Requirements includes:
```
pandas == 1.2.4
streamlit==0.82.0
plotly==4.14.3
```
To run the streamlit code
```
streamlit run app.py
```
## Licensing
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Author:

* **Eliseo Baquero** [@Eli-2020](https://github.com/Eli-2020)
