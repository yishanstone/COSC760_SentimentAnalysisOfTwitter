# COSC760_SentimentAnalysisOfTwitter
It is the modified version of Jefferson-Henrique's "GetOldTweets-python" for the use of our group project
The original codes are borrowed from https://github.com/Jefferson-Henrique/GetOldTweets-python

1. The added lines are denoted by comments of #add. 
Changes are made in three files: Exporter.py, TweetCriteria.py and TweetManager.py

2. To specify language of tweets, add "--lang en" (en = English) to the command
Example: python Exporter.py --querysearch "Pepsi" --since 2018-09-10 --until 2018-09-15 --maxtweets 1000 --lang en
