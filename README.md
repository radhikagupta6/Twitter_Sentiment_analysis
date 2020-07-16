# Twitter Sentiment analysis
- Uses textblob and tweepy for taking in tweets from twitter and analyzing them according to their sentiment value.
- Tweets are classified into positive, negative, neutral sentiments. 
- v1.02 has further more categorization of the tweets.
## Objective:
- To classify tweets into positive, strongly positive, weekly positive, neutral, strongly negative,
negative, weekly negative.
## Challenges:
- Tweets are often sarcastic. 
- Tweets generally include abbreviations, informal language, text-speak, other languages written
in english.
## Dataset:
Taken with the help of Twitter API. Consumer API keys, Access token & access token secret are
necessary for extracting the tweets for a particular topic.
## Approach / Methodology:
- Establish a connection with the twitter app.
- Enter the topic for which the sentiments have to be analysed.
- Enter the number of tweets.
- Plot the result using Matplotlib.
## Preprocessing:
- Cleaning up of tweets is done using re.
- The tweets are tokenized. Only the alphabetical tokens are stored. Tokens with punctuation
marks, special characters are ignored. Frequency count of each token per message is stored as Bag
of Words.
## Classification:
- TextBlob is used for calculating the polarity and classifying the tweets.
