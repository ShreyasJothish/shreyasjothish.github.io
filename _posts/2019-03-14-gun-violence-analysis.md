---
layout: post
title: Gun Violence Analysis
subtitle: Data analysis and visualization on all recorded gun violence incidents in the US between January 2013 and March 2018.
image: /img/gunviolence/gunviolence_img_4.PNG
gh-repo: ShreyasJothish/gunviolencedata
gh-badge: [star, fork, follow]
tags: [data analysis, data visualization]
---

James Ko, has curated detailed data on gun violence based on [Gun Violence Archive's](https://www.gunviolencearchive.org) website which has more than 260K records of gun violence incidents, with detailed information about each incident, available in CSV format. 

## Project Description

* Gun violence analysis was carried out as part of Lambda School’s build week and I was responsible for data analysis and visualization.

* The original data set needed data wrangling get the summary. Some of the important steps carried out are listed below.

> Many location information with respect to individual shooting incidents were missing. So using geocoder API the latitude and longitude were retrieved and merged.

> Information across participant features listed needed to be consolidated together for clear understanding of data.

> Few of the incidents like 2017 Las Vegas Mandalay Bay shooting needed to be handled manually.

* Choropleth map across gun violence across different states is as shown below.

![](/img/gunviolence/gunviolence_img_1.PNG)

* Scatter plot of top 10 states with respect to mass shooting incidents across years is as shown below.

![](/img/gunviolence/gunviolence_img_2.PNG)

* Heat map of mass shooting incidents was plotted across entire country.

![](/img/gunviolence/gunviolence_img_3.PNG)

* Heat map was built using Mapbox. This gave the ability to zoom into individual shooting incident and get the specific information on the same as displayed below. For example 2017 Las Vegas Mandalay Bay shooting incident details are listed below.

![](/img/gunviolence/gunviolence_img_4.PNG)

## Tools
python, geocoder (LocationIQ API), dash, dask, Mapbox API

## Reference List

### API:

> [geocoder (LocationIQ API) Reference](https://geocoder.readthedocs.io/providers/LocationIQ.html)

> [Mapbox API](https://www.mapbox.com/)

### Data Source:

> [Gun Violence Data](https://www.kaggle.com/jameslko/gun-violence-data)

> [Gun Violence Archive](https://www.gunviolencearchive.org/)
