# 🎬 Letterboxd Movie Analytics & Recommendation System

A complete data analytics and machine learning project that explores 9.4K+ films from the [Letterboxd Movie Classification Dataset](https://www.kaggle.com/datasets/sahilislam007/letterbox-movie-classification-dataset/data). This project includes exploratory data analysis, machine learning modeling, content-based recommendation, sentiment analysis, and a fully interactive Power BI dashboard.

*Python, XGBoost, NLP, Power BI, Sklearn, Pandas*
 Oct 2024 – Nov 2024
 •
 Analyzed 10K+ films using clustering, regression (XGBoost R2 = 0.79), and classification (88% accuracy) to uncover traits of blockbuster films, 
high-acclaim predictors, and audience sentiment across 0+ genres and 30+ languages
 •
 Built Power BI dashboards with KPIs, predictive insights, and content-based recommendations using TF-IDF + cosine similarity to inform user 
personalization and marketing strategy
---

## 📁 Project Structure

- `Letterboxd_Analysis.ipynb`: Jupyter notebook containing data cleaning, EDA, ML modeling, clustering, sentiment analysis, and recommendation logic.
- `Letterboxd_Dashboard.pbix`: Power BI dashboard with 4 pages of visual insights and interactive filters.
- `report.pdf`: Final business report answering strategic questions with plots and interpretations.
- `data/`: Cleaned and derived CSV files used for dashboard and analysis.
- `README.md`: This file!

---

## 📊 Key Features

### 🔍 Data Analysis & Visualization
- Analyzed ratings, runtime, fan engagement, genres, studios, directors, and languages.
- Created 40+ visualizations to understand trends, correlations, and audience preferences.
- Segment films into **Popularity** and **Quality** bands.

### 🤖 Machine Learning
- **Regression**: XGBoost model to predict average rating (R² = 0.79).
- **Classification**: XGBoost classifier to identify critically acclaimed films (88% accuracy).
- **Clustering**: K-Means clustering of films to identify "Blockbusters", "Hidden Gems", etc.
- **Feature Importance** analysis to surface key traits of successful films.

### 🗣️ NLP & Sentiment Analysis
- Used `TextBlob` to score sentiment of film descriptions.
- Analyzed which genres have **high sentiment but low visibility** (e.g. Animation, Documentary).

### 🎯 Content-Based Recommender
- TF-IDF vectorization + cosine similarity on movie descriptions to build recommendation engine.
- Output: 5-film recommendations for any selected movie, personalized by metadata.

### 📊 Power BI Dashboard
- 4 interactive pages:
  1. KPIs & Genre Insights  
  2. Engagement & Ratings  
  3. Sentiment & ML Models  
  4. Clusters & Recommendations  
- Dynamic filters: Genre, Language, Quality Segment, Popularity

---

## 📌 Business Questions Answered

- What traits define a **blockbuster** or **critically acclaimed** film?
- Which genres are **underrated but high-quality**?
- How well can we **predict rating success** from metadata?
- Can we **personalize recommendations** by language or genre?
- What role do **sentiment and visibility** play in genre performance?
- Which **studios or directors** consistently deliver hits?

---

## 🧠 Tech Stack

- **Python**: Pandas, Seaborn, Matplotlib, XGBoost, Scikit-learn, TextBlob, NLTK, TF-IDF
- **Power BI**: Interactive dashboards and cross-filtering visualizations
- **NLP**: Sentiment analysis using TextBlob
- **ML Models**: Regression, Classification, Clustering, Cosine Similarity Recommender
- **Dataset**: [Kaggle – Letterboxd Movie Classification](https://www.kaggle.com/datasets/sahilislam007/letterbox-movie-classification-dataset/data)

---

## 🚀 Getting Started

1. Clone the repo or download this directory.
2. Run the Jupyter notebook (`Letterboxd_Analysis.ipynb`) to reproduce the analysis.
3. Open `Letterboxd_Dashboard.pbix` in Power BI Desktop to explore the dashboard.
4. Dataset can be downloaded from [Kaggle here](https://www.kaggle.com/datasets/sahilislam007/letterbox-movie-classification-dataset/data).

---

## 📢 Author

**Aditya Dutta**  
_Data Analyst | Machine Learning Enthusiast_  
📧 [aditya.dutta213@2gmail.com]  
🌐 [https://linkedin.com/in/aditya-dutta-73a272143 / https://www.datascienceportfol.io/adityadutta213]

---

## 📄 License

This project is for educational and portfolio purposes only. All dataset credits go to the original Kaggle uploader.
