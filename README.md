# w209_final project

<p align="center"><img src="website/COVID19/covid_usa.png" width="600"></p> 

## License
MIT License, refer to the license.md file.

## Introduction

This repository contains all the resources we have used to create MIDS W209 final project website. The repository structure is as follows

- "Website" folder: This folder includes html and css file used to design our landing page.
[COVID-19: Mobillity Report](http://people.ischool.berkeley.edu/~hyunchul78/COVID19/index.html) 


- "data" folder : It contains original mobility data & preprocessed mobility data. The mobility data used for our visualization is from Google Mobillity data (https://www.google.com/covid19/mobility/). All the detailed data description can be found in the provided link.
         All three members fulfil EDA based on this data set. According to the EDA, most of the mobility data comes from USA and included many NaNs. 
         Thus team decided to focus on US mobility data and applied linear interpolation to fill out NaN in time series mobility dataset.
         
         - Data source in the Git (w209_final/peter/Global_Mobility_Report_preprocess.csv) 
         
         - Preprocessed US data set after EDA (w209_final/peter/US_Mobility_Report_preprocess.csv)
         
         - Jupyter Notebook link for EDA (w209_final/peter/ellie_eda_v2.ipynb) 
         
         

- "peter/ernesto/ellie" folder : Each folder includes Tableau workbook used for our visualization

         - Ellie's Tableau workbook file : Covid_timeline.twb, categories.twb
         
         - Peter's Tableau workbook file : Coronavirus (COVID-19) Cases.twb
                  
         - Ernesto's Tableau workbook file : Mobility_final_w209_ernesto.twb

<p align="center"><img src="tableau.png" width="800"></p> 







