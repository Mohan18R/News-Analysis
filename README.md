# News Analysis using NewsAPI

This project fetches news articles related to "Infosys" from the past 3 days using the **NewsAPI**, performs sentiment analysis, and visualizes trends.

## Features
- Fetches latest articles using **NewsAPI**
- Extracts and processes article data with **Pandas**
- Visualizes article publication trends using **Matplotlib** & **Seaborn**
- Performs sentiment analysis on article headlines using **NLTK**
- Generates a **word cloud** of frequently used words in headlines

## Installation
Ensure you have the required libraries installed before running the script.
```bash
pip install requests pandas matplotlib seaborn nltk wordcloud
```

## API Setup
- Obtain a free API key from [NewsAPI](https://newsapi.org/)
- Replace `api_key` in the script with your actual API key.

## Usage
Run the script in a Python environment:
```bash
python news_analysis.py
```

## Output Visualizations
1. **Number of Articles Published Over Time**
2. **Top 10 News Sources by Article Count**
3. **Sentiment Distribution of Headlines**
4. **Sentiment Breakdown by Top 5 News Sources**
5. **Word Cloud of Article Headlines**

## Example Graphs
The script produces various graphs to analyze trends and sentiment:
- **Line plot** showing the number of articles published over time.
- **Bar chart** highlighting the top news sources.
- **Histogram** of sentiment scores for article headlines.
- **Stacked bar chart** showing sentiment distribution for top news sources.
- **Word cloud** visualizing frequently used words in headlines.

## Sentiment Analysis
Sentiment scores are computed for article headlines using NLTK’s **VADER SentimentIntensityAnalyzer**:
- `Positive` if sentiment score > 0.05
- `Negative` if sentiment score < -0.05
- `Neutral` otherwise

## License
This project is for educational purposes only and uses data from **NewsAPI** under its free-tier limitations.

