# Stock-Market-News-Sentiment-Analysis
NLP-based stock market news analysis project that classifies financial news sentiment using Word2Vec, GloVe, and Sentence Transformers, with Mistral LLM-powered summarization to extract key positive and negative market events.



## Context

The prices of the stocks of companies listed under a global exchange are influenced by a variety of factors, with the company's financial performance, innovations and collaborations, and market sentiment being factors that play a significant role. News and media reports can rapidly affect investor perceptions and, consequently, stock prices in the highly competitive financial industry.
With the sheer volume of news and opinions from a wide variety of sources, investors and financial analysts often struggle to stay updated and accurately interpret its impact on the market. As a result, investment firms need sophisticated tools to analyze market sentiment and integrate this information into their investment strategies.

## Problem Definition

With an ever-rising number of news articles and opinions, an investment startup aims to leverage artificial intelligence to address the challenge of interpreting stock-related news and its impact on stock prices. They have collected historical daily news for a specific company listed under NASDAQ, along with data on its daily stock price and trade volumes.

Analyzing the data, developing an AI-driven sentiment analysis system that will automatically process and analyze news articles to gauge market sentiment, and summarizing the news at a weekly level to enhance the accuracy of their stock price predictions and optimize investment strategies. This will empower their financial analysts with actionable insights, leading to more informed investment decisions and improved client outcomes.

## Data Dictionary

1. Date: The date the news was released
2. News: The content of news articles that could potentially affect the company's stock price
3. Open: The stock price (in $) at the beginning of the day
4. High: The highest stock price (in $) reached during the day
5. Low: The lowest stock price (in $) reached during the day
6. Close: The adjusted stock price (in $) at the end of the day
7. Volume: The number of shares traded during the day
8. Label: The sentiment polarity of the news content

1: Positive
0: Neutral
-1: Negative
