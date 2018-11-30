---
layout: post
title: Political link
subtitle: Project Overview and Plan
---

## Project Overview

Identity political inclination of twitter user's as **_For, Neutral and Against_** based on sentiment analysis done on quoted tweets to tweet from prominent political entity.

## Project Plan

1. Identify the political party or person of interest on twitter (referred to as entity) like Narendra Modi, BJP, Congress or Shashi Tharoor.

2. Get entity's twitter handle. *@narendramodi*, *@BJP4India*, *@INCIndia* or *@realDonaldTrump*.

3. Web scrap through their recent tweets and identify the people who are replying back or re-tweeting with comments.

4. Identify the sentiment of the comments as either positive, neutral or negative. Here the percentage of the inclination towards or against is determined based on word assertions used.

5. Make 3 lists For, Neutral and Against for a particular entity. Recursively build this list.

## Reference List

### API:

> [Twitter API Documentation](https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/tweet-object)

> [Tweepy API Reference](https://tweepy.readthedocs.io/en/3.7.0/api.html)

> [TextBlob API Reference](https://textblob.readthedocs.io/en/dev/api_reference.html#module-textblob.base)

### Blogs:

> [Twitter API Blog](http://adilmoujahid.com/posts/2014/07/twitter-analytics/)

> [Twitter Sentiment Analysis Blog](https://github.com/llSourcell/twitter_sentiment_challenge/blob/master/demo.py)
