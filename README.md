# It is recommended to see the notebook's ipynb file [here](https://nbviewer.jupyter.org/github/arkebi24/Covid-19-Insights-and-analysis/blob/4cb55e050716fab4eb51b6f7f2789c46fc1378b2/covid-19analysis.ipynb) with nbviewer

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

pandas  
numpy  
seaborn 
matplotlib  
plotly,  
You can install using from your command promt as pip install pip or get it from [here](https://plotly.com/python/getting-started/)

## Project Motivation<a name="motivation"></a>

As the covid-19 outbreak impacted the world in so many ways, I decided to do an analysis on COVID-19 transmission rate around the globe.
I chose the corona-virus-report dataset [link](https://www.kaggle.com/imdevskp/corona-virus-report/download/2UVx3oPVlnwZT6B0waRH%2Fversions%2FZNvkS4Tonp32fXDmH4sL%2Ffiles%2Fcovid_19_clean_complete.csv?datasetVersionNumber=101) and GlobalLandTemperaturesByCountry dataset [link](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data/download/eM0xChhsTAba4VhLeD2K%2Fversions%2FfgruQrMFEPB6Vq19bCe2%2Ffiles%2FGlobalLandTemperaturesByCountry.csv?datasetVersionNumber=2). 


I will answer the three question of interest mentioned below::

1. What is the trend of confirmed and recovered cases of COVID-19？
2. How land temperature affected the transmission and progression of spread of COVID-19?
3. How many confirmed cases in different countries based on the average temperature? 

## File Descriptions <a name="files"></a>

Datasets folder contains both the datasets:

1. corona-virus-report.csv
2. GlobalLandTemperaturesByCountry.csv

There is also a notebook available here to showcsae all my work related to my three questions.



## Results<a name="results"></a>

The main findings of the code can be found at the medium [post](https://medium.com/@riteshbehera123/covid-19-some-insights-analysis-on-its-transmission-rate-160cf43970fc) available



## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity courses for some of code ideas, and to kagglers for so many ideas and data. Feel free to use the code here as you would like!

## NOTE:
filling missing values with zeroes
 ### REASON: 
  Missing values are filled with zeroes because Province/State is a categorical feature and also
  We are not feeding this data to any Machine Learning Model so this won't create any bias in the analysis

