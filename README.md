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
This is a project developed at the CRI Université de Paris in the second semester of the Master of Digital Science, within the Challenge Hub program. the project is the sentiment analysis of 16 speeches by activist greta thunberg, who has given speeches in different settings, with different audiences and on two continents.
In addition, the analysis of each of the speeches will be made to see if they are based on opinions or facts. the speeches include the years 2018, 2019 and 2020, it is clarified that they are not all the speeches made by the activist in those years.

## Datasets
The data sets are from the open data of [Jonhs Hopkins University](https://github.com/CSSEGISandData/COVID-19)
* Speeches.csv

Columns in the datasets:

- `Title`: Title of the speech.
- `Event`: identifies the event of the speech.
- `Location`: the city on the Earth's surface.
- `Date`: the geographic coordinates that specifies the east – west position of a point on the Earth's surface.
- `Link Video`: identifies the link video of the speech on the platform "www.youtube.com".
- `Trascript from`: it is the link to the webside of the trascription of each speech. 
- `Script`: it is the trascription of each speech. 


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
