# wmnlp-materials-final-project
Week 7 Custom Web Scraping project


# Article Summarizer Using Lemma-Based Sentiment Analysis

This project is a Python-based text summarization tool that processes an article, analyzes its content based on sentiment polarity derived from lemmatized sentences, and generates a concise summary. The summarization is based on the sentiment of the lemmatized sentences, ensuring that only relevant sentences with positive sentiment (or those above a specified cutoff) are included in the summary.

## Features

- **Text Extraction**: Extracts text from an HTML file.
- **Lemmatization**: Uses spaCy to lemmatize the sentences in the article, removing stop words and punctuation.
- **Sentiment Analysis**: Uses `SpacyTextBlob` for sentiment analysis on lemmatized sentences.
- **Filtering**: Applies filters to exclude irrelevant sentences (e.g., ads, promotional content).
- **Customizable**: Allows for setting a sentiment cutoff and limits the number of sentences in the final summary.

## Requirements

- Python 3.x
- spaCy (installed with language model)
- SpacyTextBlob
- BeautifulSoup4