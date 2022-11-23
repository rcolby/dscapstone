# YouTube Trending Video Dataset
## Exploration and Sentiment Analysis

This is my capstone project from the [Data Science Certificate](https://www.uclaextension.edu/digital-technology/data-analytics-management/certificate/data-science) program through UCLA Extension. For this project, I used the US data from the YoutTube Trending Video Dataset.

I began by importing the data and creating some charts. Due to time and reource constraints, I created a subset of the most recent data to scrap the YouTube pages and retrieve the most recent 100 comments. Since the pages are dynamic, I had to use [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver/) to open each page and scrape the data. After that was completed, I used [VADER](https://github.com/Holek/vader_sentiment) to perform sentiment analysis on the collected comments.

Youtube. (2022). *YouTube Trending Video Dataset (updated daily)* Data set [Kaggle](https://doi.org/10.34740/KAGGLE/DSV/4536214) License: CC0: Public Domain