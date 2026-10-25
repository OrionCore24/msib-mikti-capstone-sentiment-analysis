# Indonesia National Team News Sentiment Analysis

An MSIB MIKTI Data Analyst capstone project that explores public sentiment and news trends surrounding the Indonesian national football team (*Timnas Indonesia*) using Python, Natural Language Processing (NLP), topic modeling, and data visualization.

## 📌 Project Overview

Digital news platforms generate large amounts of information about the Indonesian national football team. Analyzing these articles can help us understand news coverage patterns, identify dominant topics, and explore sentiment trends over time.

This project combines news data from multiple sources and applies text preprocessing, topic modeling, sentiment analysis, and exploratory data analysis (EDA) to uncover meaningful insights from news articles about Timnas Indonesia.

### Objectives

- Analyze public sentiment reflected in news coverage of the Indonesian national football team.
- Classify news articles into positive, negative, and neutral sentiment categories.
- Identify dominant topics and track their development over time.
- Explore monthly news trends and sentiment distributions through data visualization.
- Transform raw news data into structured information that supports data-driven insights.

## 📊 Dataset

The dataset consists of news articles related to the Indonesian national football team, collected from multiple news portals.

| Dataset Stage | Number of Records |
|---|---:|
| Raw dataset | 9,607 |
| Final dataset | 5,369 |

The dataset was cleaned and processed to prepare it for further analysis.

**Note:** The dataset figures are based on the project's capstone presentation. The original data sources, collection period, and detailed dataset schema should be documented when those details are available.

## 🛠️ Tools & Technologies

- **Python** — Data processing and analysis.
- **NumPy** — Numerical operations.
- **Matplotlib** — Data visualization.
- **Natural Language Processing (NLP)** — Text preprocessing and analysis.
- **Latent Dirichlet Allocation (LDA)** — Topic modeling to identify dominant themes in news articles.
- **Sentiment Analysis** — Analysis and classification of positive, negative, and neutral sentiment.

## ⚙️ Project Workflow

The project follows a structured data analysis workflow:

### 1. Data Collection and Integration
Collect news articles about Timnas Indonesia from multiple news portals and combine them into a single dataset.

### 2. Data Cleaning
- Identify and handle missing values.
- Detect and remove duplicate records.
- Prepare the dataset for subsequent processing.

### 3. Text Preprocessing
Prepare the text data for analysis through preprocessing steps, including:
- Data filtering.
- Stopword removal.
- Text normalization.
- Stemming.

### 4. Exploratory Data Analysis (EDA)
Explore the characteristics of the dataset through visualizations, including:
- Monthly news article counts.
- Average and total article content length per month.
- Overall sentiment distribution.
- Monthly sentiment trends.
- Positive versus negative sentiment comparisons.
- Monthly word trends and word clouds.
- Sentiment distribution across topics.

### 5. Topic Modeling
Apply Latent Dirichlet Allocation (LDA) to identify dominant topics in the news dataset and explore how those topics change over time.

### 6. Sentiment Analysis
Analyze news sentiment and categorize articles into three classes:
- **Positive**
- **Negative**
- **Neutral**

### 7. Model Evaluation
Evaluate the sentiment classification model as part of the model development workflow.

*Detailed model configurations, evaluation metrics, and numerical performance results can be added when the corresponding experimental results are available.*

### 8. Data Visualization and Insights
Present the findings through visualizations to make sentiment distributions, news trends, and dominant topics easier to understand.

## 🔍 Key Findings

Based on the project's exploratory analysis and visualizations, several observations were highlighted:

- **Neutral sentiment dominated:** Neutral sentiment was the most prominent category in the analyzed news coverage.
- **World Cup qualification attracted significant attention:** The topic modeling analysis showed a notable increase in coverage related to World Cup qualification.
- **News coverage varied over time:** Monthly analysis was used to explore changes in article volume, sentiment, and topic distribution.

These findings describe patterns observed in the analyzed dataset and should not automatically be interpreted as a direct measurement of all Indonesian football fans' opinions.

## 📈 Expected Outcomes

This project demonstrates how text data can be transformed into meaningful analytical insights through a combination of data preparation, NLP, topic modeling, sentiment analysis, and visualization.

The resulting analysis provides an overview of news coverage patterns and sentiment trends related to the Indonesian national football team.

## 👥 Project Team

**Program:** MSIB MIKTI  
**Team:** Team 3 — Data Analyst 2

- Denta Septyan Afandi
- Ida Bagus Gede Basudewa W.
- Leo Fetri Hendli
- I Gede Surya Adi Pradana
- Dea Ananda Refiza R.
- Siti Aminah

## 🚀 Future Improvements

Potential improvements for future development include:

- Documenting the original news sources and data collection period.
- Adding detailed sentiment classification metrics, such as accuracy, precision, recall, and F1-score.
- Comparing different sentiment classification models.
- Developing an interactive dashboard to explore sentiment and topic trends.
- Automating news data collection and analysis to support more frequent updates.

## 📁 Repository Structure

The repository can be organized as follows:

```text
indonesia-national-team-sentiment-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── final_team3_capstone_mikti.ipynb
│   └── lanjutan_file_diatas_predictive_model.ipynb
├── visualizations/
├── README.md
└── requirements.txt
```

*The structure above is still messy report.*

## 🎓 Project Context

This project was developed as part of the MSIB MIKTI Data Analyst program capstone project.

It represents a collaborative effort to apply data analysis and NLP techniques to Indonesian national football news.

---

**Project Focus:** Data Analytics | NLP | Sentiment Analysis | Topic Modeling | Data Visualization
