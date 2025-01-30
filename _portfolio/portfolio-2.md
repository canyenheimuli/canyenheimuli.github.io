---
title: "Forecasting and Visualizing Bird Sightings in US National Parks"
excerpt: "From a school project on forecasting the likelihood of bird sightings in popular US National Parks"
collection: portfolio
---

In this project, some of my masters program cohort students and I collected and merged data on bird sightings and US National Parks to show where hikers are more likely to see birds. 

We first gathered geospatial data on both selected US National Parks (certain popular parks in the US West) and on historical bird sightings from the eBird website from Cornell University. We then grouped bird sightings to their closest hiking trails in the park where they were sighted. We then trained multiple time series models on individual trails and used those models to forecast the likelihood of seeing birds on a given hiking trail. We lastly created an RShiny app that shows bird sightings overlaid on park boundary and hiking trail lines so users can see on which hiking trails they are most likely to see birds. Users are also able to filter to month of planned visit within the chosen national park(s).

See the web application [here](https://calewilliams.shinyapps.io/biRds/).
