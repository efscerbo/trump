# trump
EDA of 2 1/2 years of Trump's tweets

Note: In order to upload the data I downloaded, I needed
to split the file 'trump_tweets.json' into two separate
files: 'trump_tweets_1.json' and 'trump_tweets_2.json'.
(This is because the whole dataset was > 25MB.) If you
wish to run the code, you should load each of these files
separately and then combine them:

trump_tweets_1 = load_tweets('trump_tweets_1.json')
trump_tweets_2 = load_tweets('trump_tweets_2.json')
trump_tweets = trump_tweets_1 + trump_tweets_2
