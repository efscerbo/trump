# trump
EDA of 2 1/2 years of Trump's tweets

Note: The dataset of Trump's tweets which I downloaded
was too big to upload on GitHub (> 25 MB), so I split
it into two separate files: 'trump_tweets_1.json' and 
'trump_tweets_2.json'. If you wish to run the code, you 
should load each of these files separately and then combine 
them, as in the following:

trump_tweets_1 = load_tweets('trump_tweets_1.json')

trump_tweets_2 = load_tweets('trump_tweets_2.json')

trump_tweets = trump_tweets_1 + trump_tweets_2
