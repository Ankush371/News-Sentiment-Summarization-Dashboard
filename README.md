# News-Sentiment-Summarization-Dashboard
This project provides an automated pipeline to fetch, analyze, and summarize news articles on any given topic using AI.

Features :
• Live News Fetching: Uses the NewsAPI to retrieve the latest 20 articles on a user-defined topic.
• Data Cleaning: Processes raw JSON data into structured Pandas DataFrames.
• Sentiment Analysis: Utilizes a distilbert-base-uncased-finetuned-sst-2-english model via Hugging Face Transformers to classify headlines as Positive or Negative.
• Executive Summarization: Employs the facebook/bart-large-cnn model to generate a concise summary of the top headlines.
• Visual Insights: Generates pie charts for sentiment distribution and histograms for model confidence scores using Seaborn and Matplotlib.

Prerequisites :
• Python 3.x
• A NewsAPI Key (available at newsapi.org)
• Libraries: requests, pandas, transformers, torch, matplotlib, seaborn

How to Use :
• Run the first cell and enter your NewsAPI key.
• Provide a search topic (e.g., 'Artificial Intelligence', 'SpaceX').
• Execute the subsequent cells to process data, run AI models, and view the visual dashboard.
