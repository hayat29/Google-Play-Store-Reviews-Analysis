# 📊 Google Play Store Reviews Analysis  

## 🌟 Overview  
This project conducts an **Exploratory Data Analysis (EDA)** on Google Play Store reviews. It focuses on understanding user sentiment, sentiment polarity, and sentiment subjectivity, providing insights into how users perceive apps on the Play Store. The analysis utilizes **Python, Pandas, Seaborn, and Matplotlib** to clean, visualize, and extract meaningful information from the dataset.

## 🎯 Objectives  
- 🏷️ **Data Cleaning**: Handle missing values, duplicates, and transform data into a structured format.  
- 📊 **Sentiment Analysis**: Explore the distribution of sentiment categories (`Positive`, `Neutral`, `Negative`).  
- 📈 **Sentiment Polarity Analysis**: Measure the positivity or negativity of reviews.  
- 🎭 **Sentiment Subjectivity Analysis**: Evaluate how opinion-based reviews are.  
- 📉 **Data Visualization**: Create meaningful visualizations for sentiment trends.  

## 📂 Dataset Description  
The dataset consists of **user reviews** of apps from the Google Play Store. It includes:
- **App** → Name of the application.  
- **Translated_Review** → User review translated to English.  
- **Sentiment** → Categorized sentiment (`Positive`, `Neutral`, `Negative`).  
- **Sentiment_Polarity** → A numerical score indicating positivity or negativity.  
- **Sentiment_Subjectivity** → Measures how opinion-based the review is.  

## 🛠️ Tech Stack  
- 🐍 **Python** – Core programming language  
- 📦 **Pandas** – Data cleaning & transformation  
- 🎨 **Matplotlib & Seaborn** – Data visualization  
- 🔬 **Scipy** – Statistical analysis  

## 📌 Key Features  
✅ **Automated Data Cleaning** – Handles missing values & duplicates  
✅ **Sentiment Categorization** – Analyzes how users feel about apps  
✅ **Polarity & Subjectivity Trends** – Evaluates user feedback intensity  
✅ **Visualization of Insights** – Graphical representation of user sentiment  

## 📊 Data Cleaning & Preprocessing  
The script **removes duplicates**, **handles missing values**, and **converts columns to proper formats**. Specifically:
- **Duplicates** → Removed to maintain data accuracy.  
- **Missing Values** → Dropped from sentiment-related columns.  
- **Text to Numeric Conversion** → `Sentiment_Polarity` & `Sentiment_Subjectivity` converted to floats.  

## 🔍 Exploratory Data Analysis  
Key insights extracted from the dataset include:
- **Sentiment distribution** – Which apps have more positive vs. negative reviews?  
- **Polarity analysis** – Which apps evoke strong positive/negative reactions?  
- **Subjectivity trends** – Are users providing factual or opinionated reviews?  
- **Visualizing trends** – Histograms & count plots reveal overall app sentiment.  

## 📈 Visualizations  
The project generates **three core visualizations**:
1. **Distribution of Sentiment Polarity** (`sentiment_polarity_distribution.png`)  
2. **Distribution of Sentiment Subjectivity** (`sentiment_subjectivity_distribution.png`)  
3. **Sentiment Category Counts** (`sentiment_categories.png`)  

## 📁 Files & Output  
- `google_play_store_reviews.csv` → Original dataset  
- `cleaned_google_play_store_reviews.csv` → Preprocessed dataset  
- `output_log.txt` → Log file containing insights & numerical analysis  
- `sentiment_polarity_distribution.png` → Sentiment polarity visualization  
- `sentiment_subjectivity_distribution.png` → Sentiment subjectivity visualization  
- `sentiment_categories.png` → Sentiment count plot  

## 🚀 How to Run the Project  
1️⃣ Install the required libraries:  
```bash
pip install pandas numpy seaborn matplotlib scipy
```
2️⃣ Run the script:  
```bash
python google_play_reviews_analysis.py
```
3️⃣ View saved outputs in your project folder.  

## ✨ Conclusion  
This project provides valuable insights into user sentiment trends in the Google Play Store, helping **app developers** and **businesses** understand their audience. Future enhancements could include **predictive sentiment modeling** or **natural language processing (NLP) techniques** for deeper analysis!  
