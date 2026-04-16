# Big_Data_Final_Project
# YouTube Data Analytics and Sentiment Analysis

## Course Information
Course: PROG73040 – Big Data Integration and Processing  
Project: Final Group Project  
Group: 16
Members: Nikhil Aji, Mohammad Aljabrery
Submission Date: 18th April 2026

---

## Project Overview

This project focuses on building a complete big data workflow using YouTube as the data source. It involves extracting data through the YouTube API, performing data preprocessing, analyzing trends, and applying natural language processing techniques to understand audience sentiment.

The analysis is centered around understanding content performance, publishing patterns, and viewer engagement through both quantitative metrics and sentiment analysis.

---

## Objectives

- Extract structured data from a YouTube channel using the YouTube Data API
- Analyze view trends over time
- Identify dominant content topics using word cloud visualization
- Evaluate publishing consistency and frequency
- Perform sentiment analysis on video titles and comments
- Generate meaningful insights about audience engagement and content strategy

---

## Data Source

Data is collected from 3blue1brown YouTube channel using the YouTube Data API.

Extracted Data Fields:
- Video ID  
- Title  
- Publish Time  
- View Count  
- Comment Count  

---

## Technologies and Tools

- Python  
- Databricks  
- YouTube Data API  
- Pandas  
- Matplotlib  
- WordCloud  
- TextBlob  

---

## Project Tasks

### Task 1: Data Extraction and Initial Analysis
- Retrieved video metadata using the YouTube API
- Created a structured dataset for analysis

### Task 2: View Trend Analysis
- Converted publish time to datetime format
- Analyzed how view counts change over time
- Generated a time-series plot of views

### Task 3: Topic Analysis using Word Cloud
- Generated a word cloud from video titles
- Identified key content themes

### Task 4: Publishing Frequency Analysis
- Analyzed number of videos published per month
- Created a time-series visualization of publishing frequency

### Task 5: Sentiment Analysis of Video Titles
- Used TextBlob to classify titles as Positive, Neutral, or Negative
- Visualized sentiment distribution using a pie chart

### Task 6: In-depth Sentiment Analysis of Comments
- Identified top 5 most commented videos
- Selected the video with the highest comments
- Performed sentiment analysis on comments
- Created:
  - Pie chart for sentiment distribution
  - Word clouds for Positive, Neutral, and Negative comments
- Derived insights about audience opinion

---

## Results and Insights

- View trends revealed how engagement evolves over time
- Word cloud highlighted dominant topics in the channel
- Publishing frequency showed consistency patterns
- Sentiment analysis provided insights into audience perception
- Comment analysis revealed deeper audience reactions and opinions

---

## Conclusion

This project demonstrates how big data tools and techniques can be applied to analyze social media content. By combining data extraction, visualization, and sentiment analysis, we gained insights into content strategy and audience engagement.

The methods used in this project can also be extended to detect trends, evaluate content effectiveness, and understand public sentiment, which can be valuable in addressing issues like misinformation on digital platforms.

---

## How to Run the Project

1. Open Azure Databricks or a local Jupyter environment  
2. Install required dependencies:
   ```
   pip install google-api-python-client pandas matplotlib wordcloud textblob
   ```
3. Add your YouTube API key  
4. Run the notebook step by step  

---

## Deliverables

- Final Project Report (Word/PDF)  (Final report will be uploaded soon)
- IPython Notebook (.ipynb)  

---

## References

- YouTube Data API  
- TextBlob Documentation  
- Pandas Documentation  
- Matplotlib Documentation  
- WordCloud Library  