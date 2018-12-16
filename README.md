# Natural Language Processing: Twitter Sentiment Analysis

.
###### Dec 15 2018
.

Twitter is an online social network with over 330 million active monthly users as of Dec 2018. Users on twitter create short messages called tweets to be shared with other twitter users who interact by sharing (retweeting) and / or responding. Twitter employs a message size restriction of 280 characters or less which forces the users to stay focused on the message they wish to disseminate. This very characteristic makes messages from twitter a good candidate for Natural Language Processing (NLP) machine learning tasks like sentiment analysis.


#### Rafale Deal Verdict in India!

While sentiment analysis on twitter data has been [performed many times,](https://scholar.google.com/scholar?q=arxiv+twitter+sentiment+analysis&hl=en&as_sdt=0&as_vis=1&oi=scholart&sa=X&ved=0ahUKEwiZqKbR7avaAhVEKKwKHYZCDlYQgQMIJjAA) building experience and tackling bigger challenges always builds on a form of prevoius work from others. In this project, I attempt to use a Naive Bayes Classifier to extract sentiment analysis from tweets captured on twitter on Dec 14th of 2018 for the Hashtag ["#ModiWinsOnRafale"](https://en.wikipedia.org/wiki/Rafale_deal_controversy). The tweets are from the day after ***Supreme Court’s Rafale Verdict*** in ***India***. This topic is especially interesting because of the current polarized state in the national political arena.

As expected, the country took to twitter to voice their opinions as twitter users usually do and I thought it would be a prime moment to explore the general sentiment of the country towards this political announcement.

.   image credit: [Wikimedia Commons](https://cdn2.i-scmp.com/sites/default/files/styles/980x551/public/2015/06/22/spratly-fighterj11.jpg?itok=k2Hau0T6)
![Wiki  Commons Media](https://cdn2.i-scmp.com/sites/default/files/styles/980x551/public/2015/06/22/spratly-fighterj11.jpg?itok=k2Hau0T6) 

.

I downloaded the data using twitter's api. Full documentaion and terms of the API are avilable at [developer.twitter.com/en/docs](https://developer.twitter.com/en/docs)

I used a Naive Bayes Classifier (NB) to learn the correct labels from the training data. I used training dataset from [Kaggle](https://www.kaggle.com/c/twitter-sentiment-analysis/data) at kaggle.com. The dataset comes with prelabeled columns containing one of two binary targets. Zero(0) for Negative sentiment and One(1) for Positive sentiment. The data is made up of about 1 lakhs random tweets with corresponding sentiment labels.

### This notebook is broken down into different Steps as follows:

You can click on the section description to skip to that section directly.
#### Step 1: Training Dataset Exploration
#### Step 2: Crawl Tweets Against Hash Tags
#### Step 3: Build a working dataframe and visualize data and do some data cleaning
#### Step 4: Text Pre-Processing for Sentiment Analysis
#### Step 5: Model Training and Evaluation
#### Step 6: Geoplots, Final Thoughts and Conclusions

