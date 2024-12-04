# Stock Sentiment Analysis
## Overview
This project analyzes sentiment from Reddit discussions about stocks and explores correlations with stock price movements. By using data scraping, sentiment analysis, and visualization, this project provides insights into public sentiment and its potential impact on stock markets.
## Project Structure

📂 stock-sentiment-analysis/
├── 📂 notebooks/       # Contains all the notebooks
│   ├── scraping_and_preprocessing.ipynb
│   ├── sentiment_analysis_and_visualization.ipynb
│   ├── stock_price_correlation.ipynb
├── 📂 results/         # Processed data and visualizations
│   ├── reddit_posts_with_sentiment.csv
│   ├── sentiment_distribution.png
│   ├── sentiment_over_time.png
├── README.md           # Project documentation
├── requirements.txt    # Dependencies
## Setup Instructions

### Prerequisites
- Python 3.8+
- pip (Python package manager)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/deeshanshi/stock-sentiment-analysis.git
## Results

### Processed Data
- `reddit_posts_with_sentiment.csv`: Processed data with sentiment scores.

### Visualizations
- `sentiment_distribution.png`: A bar chart showing sentiment distribution.
- `sentiment_over_time.png`: A line chart illustrating sentiment trends.
## Future Improvements
- Integrate data from multiple platforms like Twitter or financial news.
- Use advanced NLP models (e.g., BERT) for better sentiment analysis.
- Automate real-time analysis and dashboarding.
## Acknowledgments
- [PRAW](https://praw.readthedocs.io/): Python Reddit API Wrapper.
- [VADER Sentiment](https://github.com/cjhutto/vaderSentiment): Sentiment analysis library.
- [Yahoo Finance API](https://pypi.org/project/yfinance/): Stock data retrieval.
- github link-https://github.com/deeshanshi/stock-sentiment-analysis
