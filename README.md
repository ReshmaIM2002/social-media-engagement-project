# social-media-engagement-project
Social Media Engagement Analytics using Python. Analyzed 5,000 social media records using Pandas, NumPy, Matplotlib, Seaborn, and Plotly. Performed data cleaning, exploratory data analysis, statistical analysis, data visualization, and generated insights into content performance, audience behaviour, and engagement trends.


# Social Media Engagement Analytics Using Python

## Project Overview
This project focuses on analyzing social media engagement data using Python. The analysis helps understand audience behaviour, content performance, and engagement patterns through data cleaning, statistical analysis, and visualization.

## Problem Statement
Social media platforms generate large amounts of data, including likes, comments, shares, impressions, and watch time. Analyzing these metrics helps identify user behaviour, understand content performance, and support better decision-making.

## Objectives
- Clean and preprocess social media data.
- Perform Exploratory Data Analysis (EDA).
- Analyze likes, comments, shares, and engagement rates.
- Identify high-performing post types and categories.
- Understand audience behaviour and sentiment patterns.
- Visualize insights using different Python libraries.

## Dataset
- **Dataset Name:** social_media_engagement_5000.csv
- **Total Records:** 5,000
- **Original Columns:** 19

The dataset contains user information, post details, engagement metrics, device types, sentiment, and hashtags.

## Tools and Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Project Tasks

### Task 1: Data Import and Setup
- Imported the CSV dataset using Pandas.
- Checked dataset structure and data types.
- Converted the date column into datetime format.
- Performed NumPy array operations.

### Task 2: Data Cleaning
- Identified and handled missing values.
- Checked and removed duplicate records.
- Standardized gender and sentiment categories.
- Corrected data types.
- Extracted hashtag counts.

### Task 3: Data Exploration
- Explored dataset structure using Pandas.
- Generated descriptive statistics.
- Analyzed categorical distributions.
- Created a correlation matrix.
- Performed groupby analysis.

### Task 4: Data Wrangling
- Created an engagement score.
- Applied log transformations to engagement metrics.
- Analyzed engagement by post type, country, and sentiment.

### Task 5: Statistical Analysis
Calculated:
- Mean
- Median
- Mode
- Standard deviation
- Variance
- Percentiles
- Skewness and kurtosis

### Task 6: Data Visualization
Created 13 visualizations using Matplotlib, Seaborn, and Plotly, including:
- Scatter plot
- Line chart
- Bar chart
- Pie chart
- Histogram
- Box plot
- Count plot
- Violin plot
- Pair plot
- Correlation heatmap
- Swarm plot
- Interactive Plotly chart

## Key Findings

- **Top Post Type:** Video posts achieved the highest average engagement score (12,664.61).
- **Top Content Category:** Music recorded the highest average engagement score (12,788.56).
- **Top Country:** Brazil had the highest average engagement rate (1.54).
- **Age Analysis:** Users aged 49 recorded the highest average engagement score (14,162.21).
- **Verified Accounts:** Non-verified accounts recorded higher average engagement than verified accounts.
- **Device Analysis:** Mobile users had the highest average watch time (4,087.83 seconds).
- **Sentiment Analysis:** Negative sentiment posts recorded the highest average engagement score (12,731.51).

**Note:** The dataset contained dates but no actual posting times, so the best time of day for impressions could not be determined.

## Conclusion
This project successfully analyzed 5,000 social media records using Python. Through data cleaning, exploratory data analysis, statistical analysis, and visualization, meaningful patterns were identified in content performance, audience behaviour, device usage, and sentiment.

The project provided practical experience in Python-based data analysis and demonstrated how raw data can be transformed into meaningful insights for better decision-making.


