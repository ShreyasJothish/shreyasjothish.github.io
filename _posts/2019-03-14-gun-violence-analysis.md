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

* Gun violence analysis was done as part of Lambda School’s build week and I was responsible for data analysis and visualization.

* Web scrap through their recent tweets and fetch related tweets to know the user engagement.
Up to **150** related tweets (Retweets and Quoted tweets) on **10** recent tweets is being used for analysis.

* Based on above analysis, it was found Donald Trump’s tweets gets more critique and are also very polarized. So I wanted to find out to what extent the sentiment of the people’s response is influenced by original tweet from the Mr. Trump.

* Next designed my experiment to fetch the recent **200** tweets with twitter handle @realDonaldTrump and up to **100** related tweets from others for each Trump tweet and sentiment analysis was done to determine tweet’s polarity.

* Initial Observation by plotting Trump’s tweet polarity and average of corresponding responses from people revealed overlap. However, Trump’s tweet polarity has wider spread. Also Positively polarized Trump tweet gets more positively polarized responses from others as compared to negatively polarized responses.

![](/img/blog/blog_2_img_1.png)

* Tweet timeline analysis was done to determine this new found pattern of people’s responses following Trump’s tweet sentiment is recurrent.

* The transition of average polarity of people responses does seem to follow abrupt polarity switching of Trump’s tweet. Sometimes within minutes. For better visualization, I aggregated sum of tweet polarity by day.

![](/img/blog/blog_2_img_2.png)

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
