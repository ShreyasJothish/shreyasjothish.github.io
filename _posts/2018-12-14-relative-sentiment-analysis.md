---
layout: post
title: Relative Sentiment Analysis
subtitle: Check impact of individual tweet sentiment to overall sentiment of responses. 
---

## Tools
python

plot.ly

TextBlob API

Tweepy API

## Project Overview

It is often seen the post on social media is responded back with similar tone. For example a social media post with positive sentiment gets as overall positive response and similarly a social media post with negative sentiment gets an overall negative response.

Here I have tried to use tweets from prominent personalities and analyse the impact of these tweets on overall sentiment of the responses received. 

## Project Description

* Identify few prominent personalities and get their twitter handle like *@realDonaldTrump* (Donald Trump), *@narendramodi* (Narendra Modi), *@TheEllenShow* (Ellen DeGeneres) or others.

* Web scrap through their recent tweets and fetch related tweets to know the user engagement.
Up to **150** related tweets (Retweets and Quoted tweets) on **10** recent tweets is being used for analysis.

* Based on above analysis, it was found Donald Trump’s tweets gets more critique and are also very polarized. So I wanted to find out to what extent the sentiment of the people’s response is influenced by original tweet from the Mr. Trump.

* Next designed my experiment to fetch the recent **200** tweets with twitter handle @realDonaldTrump and up to **100** related tweets from others for each Trump tweet and sentiment analysis was done to determine tweet’s polarity.

* Initial Observation by plotting Trump’s tweet polarity and average of corresponding responses from people revealed overlap. However, Trump’s tweet polarity has wider spread. Also Positively polarized Trump tweet gets more positively polarized responses from others as compared to negatively polarized responses.

* Tweet timeline analysis was done to determine this new found pattern of people’s responses following Trump’s tweet sentiment is recurrent.

* The transition of average polarity of people responses does seem to follow abrupt polarity switching of Trump’s tweet. Sometimes within minutes. For better visualization, I aggregated sum of tweet polarity by day.

## Conclusion

From the analysis it does appear the people’s response to Trump tweets follows the tone of original tweet to great extent.

## Reference List

### API:

> [Twitter API Documentation](https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/tweet-object)

> [Tweepy API Reference](https://tweepy.readthedocs.io/en/3.7.0/api.html)

> [TextBlob API Reference](https://textblob.readthedocs.io/en/dev/api_reference.html#module-textblob.base)

> [Plotly](https://plot.ly)

### Blogs:

> [Twitter API Blog](http://adilmoujahid.com/posts/2014/07/twitter-analytics/)

> [Twitter Sentiment Analysis Blog](https://github.com/llSourcell/twitter_sentiment_challenge/blob/master/demo.py)
