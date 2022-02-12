# Tales from the Crypto

![Stock Sentiment](Images/sentimental.jpeg)

## Background
---
There's a lot of hype in the news about cryptocurrency, so we want to take stock of the latest news descriptions regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this assignment, I have applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I have also applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

# Summary

# Sentiment Analysis

Overall, sentiment towards Bitcoin and Ethereum are mixed. Bitcoin's mean compound score is -0.3 indicating a mixed negative sentiment. Ethereum's mean compound score is 0.1 indicating a mixed positive sentiment. As can be seen in the top 10 n-grams frequency analysis below, it is evident why Bitcoin sentiment is worse than Ethereum given Bitcoin's bigrams listed from 7-10. Ethereum doesn't have such negative associations in its top 10 bigrams list.

---
# N-Grams Frequency Analysis

## Bitcoin - Top 10 frequent bigrams
1. bitcoin, mining, 7
2. international, monetary, 6
3. el, salvador, 6
4. legal, tender, 4
5. mining, system, 4
6. jack, dorsey, 4
7. heather, morgan, 4
8. six, fears, 4
9. fears, russian, 4
10. russian, attack, 4

## Ethereum - Top 10 frequent bigrams
1. nft, marketplace, 6
2. york, city, 4
3. ethereum, blockchain, 4
4. sequoia, capital , 4
5. capital, india, 4
6. nonfungible, token, 4
7. million, ethereum, 3
8. bitcoin, ethereum, 3
9. led, sequoia, 3
10. blockchain, bridge, 3
---
# Wordclouds
Wordclouds help present the most common words throughout the texts analyzed. When working through the analysis, it is also a helpful tool for identifying frequent stopwords that are not included in NLTKs standard stopwords module.

## Bitcoin
![Bitcoin Word Cloud](Images/btc_wordcloud.png)

## Ethereum
![Ethereum Word Cloud](Images/eth_wordcloud.png)


# Named Entity Recognition
---
![Bitcoin NER](Images/btc_ner.png)
---
---
![Ethereum NER](Images/eth_ner.png)