# Final Project Ironhack 
![pic](https://github.com/marimor62/energy-project/blob/main/images/header.png)

### Table of contents:

* [Objetive](#section1)
* [Processes](#section2)
* [Conclusions](#section3)

<a id='section1'></a>
### Objective

The objective is to carry out a detailed analysis of the carbon dioxide emissions and energy consumption per country, analyzing trends, commonalities, and the influence of different features. 
The idea came up as a result of the increasing concern about climate change and the Paris Agreement targets, which almost all the countries signed in 2016 to tackle climate change. The main goal of this agreement is to reduce the global greenhouse gas emissions and limit the temperature to below 2 degrees. Regarding these targets, some questions were presented:
* Are the European countries leading the CO2 emissions reduction in the last 20 years?
* Are global economic powers more efficient in CO2 emissions reduction?
* Is the share of renewable energy within the energy mix increasing in the last years?



<a id='section2'></a>
### Processes

In order to answer these questions, two datasets were analyzed: [data 1](https://github.com/marimor62/energy-project/blob/main/datasets/owid-co2-data.xlsx) one related to the CO2 emissions, GDP and population per country and a second one about the energy consumption per country and energy source [data 2](https://github.com/marimor62/energy-project/blob/main/datasets/energy-consumption-by-source-and-region.csv.xlsx). Both datasets were extracted from the web [Our World in Data](https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions)
The datasets contain historical data of emissions and energy consumption for each country. The columns of each dataset are explained in more detail in each [Notebook](https://github.com/marimor62/energy-project/tree/main/python).

The datasets were analyzed with Python using the libraries: Pandas, Matplotlib and Seaborn. A k-Means model was applied to cluster the countries regarding some parameters directly related to the CO2 emissions, using the Scikit Learn library. A further analysis and visualization was done using Tableau. The processes completed are collected in the scheme below:
![flow](https://github.com/marimor62/energy-project/blob/main/images/flow.png)
                                
                                
<a id='section3'></a>
### Conclusions





