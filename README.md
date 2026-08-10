# Data Analysis Internship Projects - Codveda Technologies 📊 Python & Power BI

Welcome to my project repository for the Data Analysis Internship at **Codveda Technologies**! This repository showcases end-to-end data pipelines, financial dashboard creation, and Natural Language Processing (NLP) sentiment analysis.
## 📌 Project Overview

This repository demonstrates an end-to-end data analytics workflow using real-world datasets across three distinct domains:

1. **Exploratory Data Analysis (EDA):** Morphometric classification and summary statistics using the classic Iris dataset.
2. **Financial Time Series Analysis:** Trend, seasonality, and residual breakdown of Apple Inc. (`AAPL`) stock prices.
3. **Sentiment & Text Analysis:** Preprocessing and sentiment evaluation on unstructured customer/user feedback data.

---

## 📂 Datasets Used

* **`1) iris.csv`**: Contains sepal and petal measurements across three plant species.
* **`2) Stock Prices Data Set.csv`**: Historical daily stock market data including open, high, low, close prices, and trading volumes.
* **`3) Sentiment dataset.csv`**: Unstructured text dataset used for natural language processing and sentiment classification.

---

## 🛠️ Key Tasks & Technical Implementation

### Task 1: Exploratory Data Analysis (`iris.csv`)
* Audited dataset structure, verified column data types, and checked for missing values.
* Conducted deduplication to ensure data quality and integrity.
* Computed key statistical metrics (mean, median, standard deviation, min, max) across feature measurements to analyze class distribution.

### Task 2: Stock Price Time Series Decomposition (`AAPL`)
* Filtered financial data strictly for Apple Inc. (`AAPL`) daily closing prices (2014–2017).
* Preprocessed date fields into a datetime index and resampled the series to a business-daily frequency (`'B'`), using forward-fill (`.ffill()`) to account for non-trading market days.
* Applied additive time series decomposition (`seasonal_decompose`) using an annual trading window (`period=252`) to isolate:
  * **Observed:** Daily raw price movements.
  * **Trend:** Multi-year directional stock trajectory.
  * **Seasonal:** Recurring annual cyclical patterns.
  * **Residuals:** Unexplained market noise and unexpected volatility.

### Task 3: Text & Sentiment Analysis Workflow
* Loaded and preprocessed `3) Sentiment dataset.csv` for natural language processing.
* Evaluated sentiment distribution trends across feedback entries to uncover underlying user perception patterns.

## ⚙️ Tech Stack & Dependencies

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook / Google Colab
* **Data Manipulation:** `pandas`, `numpy`
* **Time Series & Modeling:** `statsmodels`
* **Data Visualization:** `matplotlib`, `seaborn`
---

## 👤 Author
Aliyu Muhammad Buba
Data Analyst Intern @Codveda Technologies

Data Analyst intern @
- **Name:** Aliyu Muhammad Buba
- **Role:** Data Analyst Intern at Codveda Technologies
