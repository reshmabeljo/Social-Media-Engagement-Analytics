# Social Media Engagement Analytics Using Python

## Project Overview

This project focuses on analyzing social media engagement data using Python. The main objective is to explore user interactions, understand content performance, identify engagement trends, and gain insights into audience behavior.

The analysis is performed using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

## Objectives

- Clean and preprocess the social media dataset.
- Handle missing values and duplicate records.
- Perform exploratory data analysis (EDA).
- Calculate statistical measures such as mean, median, mode, standard deviation, and variance.
- Analyze engagement across different post categories and post types.
- Examine relationships between likes, comments, shares, impressions, and engagement rates.
- Visualize data using different charts and graphs.
- Identify meaningful insights from social media engagement patterns.

## Dataset

**Dataset name:** `social_media_engagement_5000.csv`

The dataset contains 5,000 social media records with information about user activity, posts, engagement metrics, and audience characteristics.

Some of the analyzed attributes include:

- Likes
- Comments
- Shares
- Engagement rate
- Follower count
- Impression count
- Post category
- Post type
- Gender
- Age
- Sentiment
- Posting date and time

## Technologies and Libraries Used

- **Python** – Programming language
- **Jupyter Notebook** – Development environment
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical calculations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Plotly** – Interactive visualizations

## Project Structure

```text
Social-Media-Engagement-Analytics/
│
├── Social_Media_Engagement_Analytics.ipynb
├── social_media_engagement_5000.csv
└── README.md
```

## Installation and Setup

Make sure Python and Jupyter Notebook are installed.

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

## How to Run the Project

1. Download or clone the project files.
2. Keep the CSV dataset and Jupyter Notebook in the same folder.
3. Open Jupyter Notebook.
4. Open `Social_Media_Engagement_Analytics.ipynb`.
5. Run all cells from top to bottom.
6. Review the analysis, statistical results, and visualizations.

## Analysis Performed

### 1. Data Loading and Understanding
- Imported the dataset using Pandas.
- Checked dataset dimensions, columns, and data types.
- Examined the dataset using `head()`, `info()`, and `describe()`.

### 2. Data Cleaning
- Identified and handled missing values.
- Checked and removed duplicate records where appropriate.
- Handled invalid values and inconsistent categories.
- Converted date columns into appropriate datetime formats.

### 3. Exploratory Data Analysis
- Analyzed engagement metrics.
- Examined post categories and post types.
- Compared engagement across different user groups.
- Investigated relationships between numerical variables.

### 4. Data Wrangling and Feature Engineering
- Created an engagement score.
- Calculated hashtag counts.
- Generated additional features for analysis.

### 5. Statistical Analysis
Calculated:
- Mean
- Median
- Mode
- Standard deviation
- Variance
- Percentiles

### 6. Data Visualization
Created visualizations using Matplotlib and Seaborn, along with interactive visualizations using Plotly.

The visualizations include:
- Daily average engagement rate trend
- Likes versus impressions
- Posts by category
- Gender distribution
- Age distribution
- Engagement rate distribution
- Post count by type
- Average likes by post category
- Follower count distribution by sentiment

## Expected Outcomes

This project helps understand:
- Which post categories receive more engagement.
- How likes relate to impressions.
- How engagement changes over time.
- How audience characteristics relate to social media activity.
- How sentiment relates to follower count and engagement patterns.

## Conclusion

The project demonstrates how Python can be used for social media data analysis. Through data cleaning, exploratory analysis, statistical calculations, and visualization, meaningful patterns and insights can be extracted from social media engagement data.

The findings can help understand audience behavior and support data-driven social media content strategies.

---

**Project Title:** Social Media Engagement Analytics Using Python  
**Project Type:** Data Analytics  
**Tools:** Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, Plotly  
**Dataset:** Social Media Engagement (5,000 Records)
