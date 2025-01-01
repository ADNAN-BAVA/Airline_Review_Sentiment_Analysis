![wc_neg](https://github.com/user-attachments/assets/54a84027-2996-4875-95bc-4af46f110daf)# ✈️ British Airways Customer Sentiment Analysis Based on Skytrax Reviews
 
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)  
![License](https://img.shields.io/badge/license-MIT-green)  
![Status](https://img.shields.io/badge/status-complete-brightgreen)


---

### 📖 **Table of Contents**
1. [📚 Introduction](#-introduction)
2. [🎯 Project Goals](#-project-goals)
3. [📊 Data Collection](#-data-collection)
4. [🛠️ Data Preprocessing](#-data-preprocessing)
5. [🔍 Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
6. [🤖 Sentiment Analysis](#-sentiment-analysis)
7. [📈 Visualizations](#-visualizations)
8. [🚀 Future Enhancements](#-future-enhancements)
9. [📝 How to Use](#-how-to-use)

---

### 📚 **Introduction**

In the highly competitive airline industry, understanding customer sentiment is essential for delivering quality service and improving passenger satisfaction. This project leverages data scraped from Skytrax reviews to perform a comprehensive sentiment analysis of British Airways' customer feedback. By identifying key themes and sentiment trends, this analysis aims to offer actionable insights for the airline industry.

---

### 🎯 **Project Goals**

- 🔍 Analyze customer reviews to uncover sentiment trends and identify key areas for improvement.
- 📊 Provide detailed visualizations of customer feedback.
- 🤖 Demonstrate the efficacy of natural language processing (NLP) techniques in sentiment analysis.

---

### 📊 **Data Collection**

#### Tools and Libraries Used:
- 🛠️ **`requests`**: For fetching HTML content.
- 🛠️ **`BeautifulSoup`**: For parsing and extracting relevant data.
- 🛠️ **`pandas`**: For creating and managing structured datasets.

#### Data Points Collected:
- 👤 Reviewer details (e.g., name, country)
- 📝 Review text and ratings
- ✈️ Flight details (e.g., route, class)
- ⭐ Service aspect ratings (e.g., comfort, cabin service)

---

### 🛠️ **Data Preprocessing**

#### Key Steps:
1. ✂️ **Cleaning Text**: Removing punctuation, converting text to lowercase, and tokenizing.
2. 🔍 **Stopword Removal**: Excluding common words that do not carry sentiment information.
3. 📆 **Date Formatting**: Converting publication dates into a uniform format.
4. 📖 **Corpus Creation**: Extracting and cleaning review text for analysis.

#### Tools Used:
- 🛠️ **NLTK**: Tokenization and stopword removal.
- 🛠️ **Pandas**: Data manipulation and preprocessing.

---

### 🔍 **Exploratory Data Analysis (EDA)**

#### Insights:
- 💡 **Overall Sentiment**: Average rating of 4/10 indicates a largely negative sentiment.
- 📉 **Rating Distribution**: Skewed towards lower ratings, with a significant proportion of 1-3 stars.
- 🌍 **Geographic Trends**: Reviews are predominantly from the UK and US.

#### Key Visualizations:
- 📊 Rating distribution countplot.
- 🌎 Geographic distribution pie chart.

---

### 🤖 **Sentiment Analysis**

#### Methodology:
1. 🧠 **VADER Sentiment Analysis**: Extracts positive, neutral, and negative sentiment scores.
2. 🎯 **Compound Score Categorization**: Tags reviews as positive, neutral, or negative based on compound scores.
3. 🌟 **Word Cloud Generation**: Highlights frequent terms in positive and negative reviews.

#### Results:
- 🚨 A significant portion of reviews exhibit negative sentiment.
- ✅ Positive reviews emphasize crew friendliness and comfort.
- ❌ Negative reviews highlight delays and poor customer service.

---

### 📈 **Visualizations**

#### Positive Sentiment Word Cloud:

![wc_pos](https://github.com/user-attachments/assets/8df8c9a0-37ff-46fa-a8a6-6c6399df0fd2)

#### Negative Sentiment Word Cloud:

![wc_neg](https://github.com/user-attachments/assets/269c864e-52a6-44b6-a8cf-20794a0913df)

#### Frequent Words:
- ✅ **Positive Reviews**: "friendly," "helpful," "comfortable."
- ❌ **Negative Reviews**: "delayed," "cancelled," "frustrated."

---

### 🚀 **Future Enhancements**

1. 🤖 **Advanced NLP Techniques**:
   - Incorporate transformer-based models like BERT for deeper sentiment analysis.
   - Use topic modeling to uncover hidden themes in reviews.
2. 🌍 **Geographic Sentiment Analysis**:
   - Analyze sentiment trends by country to understand regional differences.
3. 📆 **Time Series Analysis**:
   - Track sentiment changes over time.

---

### 📝 **How to Use**

#### Prerequisites:
- 🐍 Python 3.8+
- 📦 Libraries: `requests`, `beautifulsoup4`, `pandas`, `nltk`, `matplotlib`, `seaborn`

#### Steps:
1. 🖥️ Clone the repository:
   ```bash
   git clone https://github.com/yourusername/british-airways-sentiment.git
   ```
2. 📥 Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. 📜 Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. 🛠️ Run the **`BA_Sentiment_Analysis.ipynb`** notebook step-by-step to replicate the analysis.

---

### 📬 **Contact Information**
For questions or suggestions, please contact adnan.bava123@gmail.com.
