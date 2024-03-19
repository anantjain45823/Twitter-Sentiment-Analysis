# Twitter-Sentiment-Analysis
This Project is about building a sentiment analysis tool with short text as input.
We have data of about 1.6 Million tweets with tags for Protive Negative Or Neutral.

This project addresses the problem of sentiment analysis in Twitter; that is classifying
tweets according to the sentiment expressed in them: positive or negative. Twitter is
an online micro-blogging and social networking platform which allows users to write
short status updates of a maximum length of 140 characters. It is a rapidly expanding
service with over 200 million registered users out of which 100 million are active
users and half of them log on Twitter daily – generating nearly 250 million
tweets per day. Due to this large amount of usage, we hope to achieve a reflection of
public sentiment by analysing the sentiments expressed in the tweets. Analysing 
public sentiment is important for many applications such as firms trying to find out
the response of their products in the market, predicting political elections and
predicting socioeconomic phenomena like stock exchange. This project aims
to develop a functional classifier for accurate and automatic sentiment classification
of an unknown tweet stream.

# Data
The dataset being used is the Sentiment 140 dataset. It contains 1,600,000 tweets extracted using  Twitter API.
The tweets have been annotated (0 =  Negative, 4= Positive) and they can be used to detect sentiment.  
It contains the following 6 fields:  
**sentiment**: the polarity of the tweet (0 = negative, 4 = positive)  
**ids**: The id of the tweet (2087)  
**date**: the date of the tweet (Sat May 16 23:58:44 UTC 2009)  
**flag**: The query (lyx). If there is no query, then this value is NO_QUERY.  
**user**: the user that tweeted (robotickilldozr)  
**text**: the text of the tweet (Lyx is cool)  

# Methodology
**Data Cleaning**: We require only the sentiment and text fields, so we discard the rest and  we're changing the sentiment field so that it has new values to reflect  the sentiment. (0 = Negative, 1 = Positive) .
**EDA**: We see that there are equal amounts of Positive and Negative Tweets (800KEach).
**Preprocessing Data**: Replacing URL, emojis and special characters and lower casing the text, removing stopwords and do Lemmatizing
**Model Used**: Logistic Regression  
**Confusion Matrix**: Find confusionMatrix file in the root folder.

# Conclusion
We can clearly see that the Logistic Regression Model performs great. It achieves nearly** 82% accuracy** while classifying the  sentiment of a tweet.  

