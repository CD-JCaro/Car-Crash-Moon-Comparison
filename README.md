# Project1
Project 1... Group: Jonathan Caro, Mark McPherson, Brian Henley
Project Proposal
Caro-Henley-McPherson

This project seeks to illustrate the effect of California’s "shelter in place" order had on air quality in specific regions of the state's South Coast Air Quality Management District.  Los Angeles County, California, has been sheltering in place since March 21, 2020, and the order is expected to end no sooner than May 1, 2020.  By utilizing data from the AQI for the days during the lockdown and comparing those numbers with the previous year's data, this project seeks to quantify the effect of sheltering in place versus not sheltering in place on air quality.  The project considers wildfires and other smog-producing events that would affect the air quality and accounts for these factors so that the analysis isn’t influenced by an event outside the scope of this project.

           The project utilizes line graphs, scatter plots, bar graphs and heat maps to illustrate what is happening with southern California's air quality.  The data is obtained from the EPA, and the South Coast AQMD.  The project begins by exporting the AQMD's data into an Excel spreadsheet and then converting those files in the CSV's. This project uses Pandas, Python, and Google  API's to organize and illustrate the data so that our inquiry can be answered.

Introduction

The Air Quality Index (AQI) tells us how clean or polluted the air is, and the effect on your health.  The EPA has standards for air quality in place to protect the public’s health.  There are 5 pollutants tracked in the AQI:

1.	Ground-level Ozone (03)
2.	Particle Pollution, known as particulate matter (PM10 and PM2.5)
3.	Carbon Monoxide (CO)
4.	Sulfur Dioxide (S02) and 
5.	Nitrogen Dioxide (N02)

Ground-level ozone and airborne particles are the two pollutants that pose the greatest threat to human health in this country.  It should be noted that the State of California has instituted standards that are more stringent that the federal standards for Ozone (O3) and Nitrogen Dioxide (NO2).

Understanding the AQI range

The purpose of the AQI is to show how local air quality means affects different types of people’s health. The AQI is divided into six categories. Each category corresponds to a different level of health concern. There are six levels. 
Good :  The AQI value for your community is between 0 and 50. Air quality is considered satisfactory, and air pollution poses little or no risk.
Moderate:  The AQI for your community is between 51 and 100. Air quality is acceptable; however, for some pollutants there may be a moderate health concern for a very small number of people. For example, people who are unusually sensitive to ozone may experience respiratory symptoms.
Unhealthy for Sensitive Groups: When AQI values are between 101 and 150, members of sensitive groups may experience health effects. This means they are likely to be affected at lower levels than the general public. For example, people with lung disease are at greater risk from exposure to ozone, while people with either lung disease or heart disease are at greater risk from exposure to particle pollution. The general public is not likely to be affected when the AQI is in this range.
Unhealthy:  Everyone may begin to experience health effects when AQI values are between 151 and 200. Members of sensitive groups may experience more serious health effects.
Very Unhealthy:  Values between 201 and 300 trigger a health alert, meaning everyone may experience serious health effects.
Hazardous:  Values over 300 trigger health warnings of emergency conditions. The entire population is more likely to be affected.


