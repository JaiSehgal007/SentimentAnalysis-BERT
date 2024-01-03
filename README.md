# Sentiment Analysis with BERT on Yelp Reviews

## Introduction
This Jupyter Notebook project showcases sentiment analysis using BERT (Bidirectional Encoder Representations from Transformers) on Yelp reviews. It involves the installation of Transformers, performing sentiment scoring using BERT, and scraping reviews from Yelp for analysis.

## Dependencies
- `transformers` from Hugging Face: for BERT model implementation
- `torch`: PyTorch library for tensor computations
- `requests`: for fetching web content
- `BeautifulSoup`: for HTML parsing
- `numpy` and `pandas`: for data handling and analysis

## How it Works
### Installation
1. **Install Transformers**: Download and install BERT from Hugging Face Transformers.
2. **Set up Environment**: Import required libraries and instantiate the BERT model.

### Sentiment Analysis
1. **Encode and Calculate Sentiment**: Utilize BERT to perform sentiment analysis on given text inputs.
2. **Tokenization**: Convert text inputs into tokenized sequences and analyze sentiment using the pre-trained model.

### Yelp Reviews Scraping
1. **Collect Reviews**: Scrape reviews from a specified Yelp URL using `requests` and `BeautifulSoup`.
2. **Load Reviews into DataFrame and Score**: Process the scraped reviews, split them into chunks, and score sentiments for each chunk using BERT. Calculate the average sentiment score per review.

## Usage
1. **Running the Notebook**: Execute the notebook cells sequentially to perform sentiment analysis on Yelp reviews.
2. **Customization**: Modify the scraping URL or adjust sentiment scoring parameters as required.

## Results
The results are presented in a Pandas DataFrame, showcasing the scraped reviews along with their calculated sentiment scores.
