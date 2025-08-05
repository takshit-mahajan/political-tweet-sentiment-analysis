# BJP Twitter Sentiment Analysis 🇮🇳

This project performs sentiment analysis on tweets related to **BJP**, one of India's major political parties. Using a dataset from **Kaggle**, it visualizes public sentiment, tweet characteristics, and key topics using various data visualization and NLP techniques.

## 📌 Objective

To explore and analyze the sentiment of tweets mentioning BJP to:
- Understand public perception (positive vs. negative)
- Identify most common words used in each sentiment
- Visualize key insights using graphs and word clouds

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Pandas** – Data manipulation
- **NumPy** – Array computations
- **Matplotlib / Seaborn** – Visualizations
- **NLTK** – Text preprocessing
- **WordCloud** – Word cloud generation

---

## 📊 Key Analyses

### 1. Sentiment Distribution
- Bar and pie charts show positive sentiment dominates (~58%).

### 2. Tweet Length Analysis
- Boxplot and histogram indicate no major difference in tweet length by sentiment.

### 3. Word Clouds
- Positive tweets: _development_, _leadership_, _growth_  
- Negative tweets: _protest_, _unemployment_, _failure_

---

## 📸 Sample Visualizations

| Sentiment Distribution | Word Clouds |
|------------------------|-------------|
| ![Sentiment Chart](images/sentiment_bar_pie.png) | ![Word Cloud](images/wordclouds.png) |

*(Save your output plots in a `/images` folder to use these.)*

---

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/bjp-twitter-sentiment-analysis.git
cd bjp-twitter-sentiment-analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the analysis
python sentiment_analysis.py
