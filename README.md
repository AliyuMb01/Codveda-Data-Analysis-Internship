# Data Analysis Internship Projects - Codveda Technologies 📊 Python & Power BI

Welcome to my project repository for the Data Analysis Internship at **Codveda Technologies**! This repository showcases end-to-end data pipelines, financial dashboard creation, and Natural Language Processing (NLP) sentiment analysis.

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, NLTK, TextBlob, WordCloud
- **Business Intelligence:** Microsoft Power BI
- **Environment:** Google Colab, Power BI Desktop

---

## 📁 Repository Structure
├── Datasets/
│   ├── Sentiment dataset.csv
│   └── Stock Prices Data Set.csv
├── Notebooks/
│   └── Sentiment_Analysis_and_NLP.ipynb
├── Dashboards/
│   └── Stock_Performance_Dashboard.pbix
└── README.md

## 📌 Project Highlights & Key Modules

### 1. Stock Performance Analysis (Power BI)
- **Objective:** Analyze multi-year stock market metrics (2015–2017) to uncover market trends and average trading volumes.
- **Key Features:**
  - Dynamic stock ticker (`symbol`) filtering for seamless comparison (e.g., A, AAL, AAP).
  - Time-series line chart tracking **Average of Close** prices over time.
  - Executive KPI cards highlighting **Average Close** (`116.84`) and **Average Volume** (`45.17M`).

### 2. Social Media Sentiment Analysis (Python & NLP)
- **Objective:** Process and classify unstructured social media text across multiple platforms (Twitter, Instagram, Facebook).
- **Workflow:**
  1. **Preprocessing:** Text cleaning with regex, lowercasing, stop-word removal, and **NLTK WordNet Lemmatization**.
  2. **Sentiment Scoring:** Polarity assessment using **TextBlob** to classify posts into *Positive*, *Neutral*, and *Negative*.
  3. **Visualization:** Seaborn distribution plots across platforms and custom **WordCloud** theme maps.

---

## 💡 Key Insights
- **Platform Sentiment:** Instagram exhibited the highest proportion of positive posts, whereas Twitter displayed a wider spread across all sentiment categories.
- **Word Drivers:** Positive sentiment was heavily driven by words like *joy*, *new*, *laughter*, and *life*, while negative sentiment centered around *grief*, *despair*, and *bitter*.

---

## 👤 Author
- **Name:** Aliyu Muhammad Buba
- **Role:** Data Analyst Intern at Codveda Technologies
