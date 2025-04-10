# 🧠 TrendLens: Real-Time Slang Radar

TrendLens is a live Streamlit app that scrapes Reddit posts to detect and visualize trending slang in real time.  
Built for Gen Z, linguists, data enthusiasts, and trend-watchers, this dashboard extracts common phrases, filters out noise, and connects terms with Urban Dictionary definitions to uncover what’s buzzing online.

## 🔍 Features

- 📥 **Live Reddit Scraping** — Gathers hot posts from Gen Z subreddits
- 🧼 **Text Cleaning** — Preprocesses title and content to extract meaningful terms
- 📊 **Interactive Dashboard** — Bar chart and word cloud visualizations
- 📚 **Slang Definitions** — Auto-fetches Urban Dictionary meanings for top terms
- 📁 **Upload Mode** — Supports custom CSV uploads for personalized analysis

## 📸 Preview

Streamlit Dashboard
<img width="1336" alt="Screenshot 2025-04-09 at 9 33 52 PM" src="https://github.com/user-attachments/assets/da550a9c-4447-46cb-96c9-895fd76c8bda" />

## 🚀 Try It Live

👉 [Launch on Streamlit](https://jenniestrendlens.streamlit.app/)

## 🛠 Built With

- Python (Pandas, NLTK, Requests, Regex)
- Streamlit for UI
- WordCloud & Matplotlib
- Urban Dictionary scraping with BeautifulSoup

## 📂 Project Structure

```bash
├── trendlens.py               # Main Streamlit app
├── slang_terms.csv            # Slang frequency + definitions
├── reddit_trending_posts.csv  # Raw scraped Reddit data
├── requirements.txt           # Python dependencies
└── README.md                  # You're here!
