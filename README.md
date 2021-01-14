# Reddit Webscraper

<img src="https://miro.medium.com/max/640/1*3PBf6sHuFXsPec47pJ0mXQ.png" alt="logo" align="left" width=300/>

This script will use a Python wrapper for the Reddit API ([PRAW](https://praw.readthedocs.io/en/latest/)) to scrape data from one or more subreddits. The data will initially be parsed and stored in a dictionary. As will be demonstrated, the information can be presented in more readable formats, including a [Pandas DataFrame](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html), a data structure readily converted into HTML tables and CSV documents as well.