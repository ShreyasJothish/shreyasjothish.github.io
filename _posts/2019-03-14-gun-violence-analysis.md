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

> Few of the incidents like 2017 Las Vegas Mandalay Bay shooting needed to be handled manually.

> Information across participant features listed needed to be consolidated together for clear understanding of data.

> Many location information with respect to individual shooting incidents were missing. So using geocoder API the latitude and longitude were retrieved and merged.

* Choropleth map across gun violence across different states is as shown below.
![](/img/gunviolence/gunviolence_img_1.PNG)

* Scatter plot of top 10 states with respect to mass shooting incidents across years is as shown below.
![](/img/gunviolence/gunviolence_img_2.PNG)

* Heat map of mass shooting incidents was plotted across entire country. Heat map was built using Mapbox.
![](/img/gunviolence/gunviolence_img_3.PNG)

* This gave the ability to zoom into individual shooting incident and get the specific information on the same as displayed below.
For example 2017 Las Vegas Mandalay Bay shooting incident details are listed below.
![](/img/gunviolence/gunviolence_img_4.PNG)

## Conclusion

From the analysis it does appear the people’s response to Trump tweets follows the tone of original tweet to great extent.

## Tools
python, plot.ly, TextBlob API, Tweepy API

## Reference List

### API:

> [Twitter API Documentation](https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/tweet-object)

> [Tweepy API Reference](https://tweepy.readthedocs.io/en/3.7.0/api.html)

> [TextBlob API Reference](https://textblob.readthedocs.io/en/dev/api_reference.html#module-textblob.base)

> [Plotly](https://plot.ly)

### Blogs:

> [Twitter API Blog](http://adilmoujahid.com/posts/2014/07/twitter-analytics/)

> [Twitter Sentiment Analysis Blog](https://github.com/llSourcell/twitter_sentiment_challenge/blob/master/demo.py)
