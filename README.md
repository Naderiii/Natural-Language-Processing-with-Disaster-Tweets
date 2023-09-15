# Natural-Language-Processing-with-Disaster-Tweets

In this project, I'm challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.
You’ll have access to a dataset of 10,000 tweets that were hand classified.

This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website here: "https://www.figure-eight.com/data-for-everyone/"
Tweet source: https://twitter.com/AnyOtherAnnaK/status/629195955506708480

What am I predicting?
You are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.

Columns
* id - a unique identifier for each tweet
* text - the text of the tweet
* location - the location the tweet was sent from (may be blank)
* keyword - a particular keyword from the tweet (may be blank)
* target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)
