# YouTube Trending Video Data Cleaning & Analysis

## Project Overview

This project focuses on cleaning, preprocessing, and analyzing the YouTube Trending Videos dataset. The main objective is to improve data quality, handle inconsistencies, and extract meaningful insights from trending video statistics such as views, likes, comments, categories, and publishing patterns.

The project demonstrates industry-level data cleaning practices using Python and provides exploratory data analysis (EDA) for understanding video engagement and trending behavior.

---

# Dataset Information

Dataset Used: YouTube Trending Videos Dataset

Source: https://www.kaggle.com/datasets/datasnaek/youtube-new

The dataset contains information about trending YouTube videos from multiple countries, including:
- Video title
- Channel title
- Category ID
- Publish time
- Trending date
- Views
- Likes
- Dislikes
- Comment count
- Tags
- Description

---

# Objectives

The main goals of this project are:

- Perform data cleaning and preprocessing
- Handle missing and inconsistent values
- Remove duplicate records
- Detect and manage outliers
- Standardize dataset formatting
- Create meaningful derived features
- Perform exploratory data analysis (EDA)
- Prepare cleaned data for dashboarding and visualization

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI

---

# Project Workflow

## 1. Data Collection

- Downloaded dataset from Kaggle
- Imported CSV dataset into Jupyter Notebook

---

## 2. Data Cleaning

The following cleaning steps were performed:

### Missing Value Handling
- Filled missing descriptions with placeholder values
- Removed rows with missing critical identifiers

### Duplicate Removal
- Identified and removed duplicate records

### Data Type Conversion
- Converted publish and trending dates into datetime format

### Invalid Data Removal
- Removed records containing invalid or negative engagement metrics

### Text Standardization
- Cleaned and standardized text columns

### Outlier Detection
- Used IQR (Interquartile Range) method to detect and handle outliers in views

### Feature Engineering
Created additional useful columns such as:
- Engagement Rate
- Like Ratio
- Publish Hour
- Publish Day
- Title Length

---

# Exploratory Data Analysis (EDA)

The following analyses were performed:

- Distribution of video views
- Relationship between likes and views
- Trending categories analysis
- Channel performance analysis
- Engagement rate analysis
- Publish timing trends
- Correlation analysis between engagement metrics

---

# Key Insights

- Videos with higher likes generally receive higher views
- Certain publishing hours show better engagement performance
- Entertainment and music categories dominate trending sections
- Engagement rate varies significantly across channels and categories
- Viral videos can strongly affect overall distribution patterns

---

# Data Cleaning Techniques Used

| Technique | Purpose |
|---|---|
| Missing Value Handling | Improve data completeness |
| Duplicate Removal | Maintain data uniqueness |
| Datetime Conversion | Enable time analysis |
| Outlier Handling | Reduce skewness |
| Standardization | Maintain consistency |
| Feature Engineering | Improve analytical capability |

---

# Project Structure

```text
youtube-project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│
├── visuals/
│
├── dashboard/
│
├── README.md
│
└── requirements.txt
```

---

# Sample Visualizations

The project includes:
- Boxplots
- Histograms
- Heatmaps
- Scatter plots
- Bar charts
- Correlation matrices

---

# Dashboard

An interactive Power BI dashboard was created to visualize:
- Total Views
- Engagement Metrics
- Trending Categories
- Top Channels
- Publishing Trends
- Video Performance Analysis

---

# Conclusion

This project demonstrates the importance of data cleaning in the analytics pipeline. By handling missing values, duplicates, inconsistent formatting, and outliers, the dataset became more reliable for analysis and visualization.

The cleaned dataset and insights generated can support further analytics, dashboarding, and machine learning applications.

---

# Future Improvements

Possible future enhancements include:
- Sentiment analysis on video titles/descriptions
- Machine learning models for trend prediction
- Advanced time-series analysis
- Cross-country comparison analysis
- Real-time YouTube analytics integration

---

# Author

Khushi Kumari

---

# License

This project is intended for educational and portfolio purposes.
