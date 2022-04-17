## Project 3: 

### Problem Statement

Utilizing reddit api to scrape posts automatically from 2 subreddits, and create and compare different classification models. Using the model to perform sentiment analysis on post contents from one subreddit and predict sentiment values for another.


### Data Collection

The posts are scraped from the following 2 subreddits below
https://www.reddit.com/r/tennis/
https://www.reddit.com/r/Pickleball/

### Datasets

* [`pickleball.csv`](./data/pickleball.csv)
* [`pickleball_cleaned.csv`](./data/pickleball_cleaned.csvc)
* [`pickleball_prediction.csv`](./data/pickleball_prediction.csv)
* [`tennis.csv`](./data/tennis.csv)
* [`tennis_cleaned.csv`](./data/tennis_cleaned.csv)

### Executive Summary

#### For Community Review
In recent years we have seen tennis players transition into playing pickleball. A lot of tennis players in the community are considering transitioning into pickleball, especially those are getting older or those with limited mobility. However, before taking up pickleball the tennis community as a whole wants to compare our tennis community with the pickleball community, specifically looking into sentiments within the community.

I am tasked to develop a machine learning model which classifies tennis subreddit posts with a high accuracy of 85%, and conducted sentiment analysis to predict sentimental values within the pickleball subreddit community.

The objective is to gather insights from posts and evaluate their sentiment, whether they are positive or not positive and give the community an idea how the pickleball community is evolving.


### Conclusion and Recommendation

Our best predicting model is Logistic Regression with CountVectorizer, using post title within tennis subreddit scoring accuracy of 85%. Analysis of our tennis subreddit sentiment predicted pickleball subreddit community and predicted the pickleball subreddit community as a whole with 25.42% positive comments and 74.58% non-positive comments compared to 38.78 positive comments and 61.22% non-positive comments within the tennis subreddit comments.

It is very odd that both data shows under 40% of positive comments. Considering what’s happening in the world right now and within the tennis community. Data may be skewed, more data is needed.

With tournaments being postponed and cancelled and players complaining about vaccine mandates and long mandatory quarantine. This leads to a lot of negative comments. Also, currently within the tennis community, everyone has been talking about the missing WTA player, Peng Shuai, who made sexual assault allegations against a top Chinese government official on social media, and has since disappeared. All her social media posts and accounts were deleted. There’s an outcry, demanding the Chinese government to investigate and release Peng Shuai.



