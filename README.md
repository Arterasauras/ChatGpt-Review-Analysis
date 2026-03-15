# ChatGpt-Review-Analysis

Project Overview This project analyzes customer reviews of ChatGPT to uncover insights about user sentiment, satisfaction, and common feedback themes. Using Natural Language Processing (NLP) techniques, the project performs sentiment analysis, keyword extraction, and visualization of textual review data.
The analysis transforms unstructured text reviews into structured insights that help identify how users perceive ChatGPT and what aspects they discuss most frequently.

## Project Objectives 

The project aims to understand: 
- The overall sentiment users express about ChatGPT.
- The strength and subjectivity of user opinions. -
- The relationship between ratings and textual sentiment.
- The keywords and phrases users most frequently mention.
- The themes present in positive and negative feedback.

## Dataset 
The dataset contains user reviews of ChatGPT and includes: 
- review: User written review text
- ratings: Numerical rating provided by the user
- review_date: Date the review was posted

## Methodology

1.  Data Preparation Steps include:

  -   Standardizing column names
  -   Handling missing review text
  -   Converting rating values into numeric format
  -   Converting review dates into datetime format
  -   Removing duplicate entries
  -   Cleaning text data by converting to lowercase and removing punctuation

2.  Sentiment Analysis Sentiment analysis is performed using TextBlob. Polarity Range: -1 to +1 Indicates whether a review is negative, neutral, or positive.
    Subjectivity Range: 0 to 1 Measures whether a review is factual or opinion-based. Reviews are categorized into: - Positive - Neutral - Negative

3. Text Analysis The project extracts meaningful information from review text using:

  -  Frequent Word Analysis Identifies the most commonly used words across reviews.
  -  TF-IDF Keyword Extraction Highlights important keywords that appear frequently and carry contextual significance.
  -  Bigram Analysis Extracts common two-word phrases that reveal patterns in how users describe their experiences.

## Data Visualizations 
The project generates multiple visualizations including: 
  - Rating Distribution
  - Sentiment Distribution
  - Subjectivity Distribution
  - Rating vs Sentiment Polarity  
  - Sentiment Heatmap 
  - Average Sentiment by Rating 
  - Word Cloud 
  - Bigram Frequency Analysis 
  - Sentiment Polarity Distribution 
  - Sentiment Pie Chart

All visualizations are saved in: outputs/charts/

## Key Insights & Findings

-  Overall Sentiment Trend Most reviews tend to exhibit positive sentiment, suggesting that users generally have favorable experiences with ChatGPT.
-  Alignment Between Ratings and Sentiment Higher ratings strongly correlate with positive sentiment polarity.
-  Subjectivity of Reviews Many reviews show moderate to high subjectivity, meaning users frequently express personal experiences and opinions.
-  Commonly Mentioned Topics Keyword and frequency analysis highlights recurring discussion topics within user feedback.
-  Frequent Phrases in Feedback Bigram analysis identifies common expressions used by reviewers.

Technologies Used -  Python  -  Pandas  -  NumPy  -  Matplotlib  -  Seaborn  -  TextBlob  -  NLTK  -  Scikit-learn  -  WordCloud

***Outputs Charts will be generated and saved in: outputs/charts/***

##Future Improvements 
- Topic modeling using LDA
- Sentiment trend analysis over time
- Feature-based sentiment analysis
- Interactive dashboards using Plotly or Streamlit

Author 
Lakshay Kumar 
Master’s in Business Analytics
