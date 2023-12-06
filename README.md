# Youtube_case_study

Welcome to the GitHub repository for the YouTube Engagement Analysis project! This project provides a comprehensive analysis of user engagement on YouTube, covering aspects such as sentiment analysis, emoji usage, category-wise likes, and much more.

Project Overview:

1. Data Loading and Cleaning:
Loaded YouTube comments data from a CSV file using Pandas.
Handled warnings during data loading and addressed missing values.
Cleaned the dataset to ensure data integrity.


2. Sentiment Analysis:
Employed TextBlob for sentiment analysis on user comments.
Appended sentiment polarity values to the comments dataframe.
Explored insights into user sentiments.


3. Wordcloud Analysis:
Utilized word clouds to analyze highly positive and negative sentences.
Identified key words expressing positive and negative sentiments.


4. Emoji Analysis:
Extracted emojis from comments using the Emoji library.
Visualized emoji usage with a bar chart.
Concluded that the majority of users express happiness.


5. YouTube Data Collection:
Gathered and merged data from various YouTube CSV files.
Handled different types of encodings during data collection.


6. Data Exportation:
Exported cleaned data into CSV, JSON, and a SQLite database.
Discussed the process of dropping duplicates and handling encoding issues.


7. Likes Analysis in Different Categories:
Mapped category IDs to their corresponding names.
Explored likes distribution across various video categories using a boxplot.

8. Audience Engagement Analysis:
Calculated like, dislike, and comment rates for audience engagement.
Visualized like rates across different video categories.


9. Top Trending Channels:
Identified channels with the largest number of trending videos using Plotly.

10. Punctuation Impact Analysis:
Explored the relationship between title and tag punctuation and views, likes, dislikes, and comments.
Used boxplots to visualize the impact of punctuation on engagement metrics.
