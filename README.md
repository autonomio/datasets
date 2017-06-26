# datasets
Various unique "real-world" datasets specifically for deep learning purpose. The files are provided in .msgpack format and can be also used separately from Autonomio for example with Pandas:

    import pandas as pd
    pd.read_msgpack('https://github.com/autonomio/datasets/raw/master/autonomio-datasets/election_in_twitter')

### 'election_in_twitter'
Dataset consisting of 10 minute samples of 80 million tweets.

### 'tweet_sentiment'
Dataset with tweet text classified for sentiment using NLTK Vader.

### 'sites_category_and_vec'
4,000 sites with word vectors and 5 categories.

### 'programmatic_ad_fraud'
Data from both buy and sell side and over 10 other sources.

### 'parties_and_employment'
9 years of monthly poll and unemployment numbers.

### 'random_tweets'        
20,000 tweets main intended for.
