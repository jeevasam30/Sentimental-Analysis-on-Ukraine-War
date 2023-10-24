# Sentimental-Analysis-on-Ukraine-War
Scrapped out twitter and Youtube comments and have done sentimental analysis to get positive negative and neutral reactionss

This repository contains code for performing sentimental analysis on comments related to the Ukraine War from YouTube and Twitter.

## YouTube Scraping

### Requirements
- Python
- Libraries: textblob, wordcloud, pandas, numpy, re, matplotlib

### Installation
```bash
pip install textblob wordcloud pandas numpy matplotlib
```

### Usage
1. Obtain a YouTube Data API key and replace `api_key` in `youtube_sentiment.py`.
2. Run `youtube_sentiment.py` to scrape comments and perform sentiment analysis.

## Twitter Scraping

### Requirements
- Python
- Libraries: tweepy, pandas, textblob, wordcloud

### Installation
```bash
pip install tweepy pandas textblob wordcloud
```

### Usage
1. Obtain Twitter API credentials and replace them in `twitter_sentiment.py`.
2. Run `twitter_sentiment.py` to scrape tweets and perform sentiment analysis.



### Usage
1. Run `sentiment_analysis.py` to perform sentiment analysis on the collected data.

