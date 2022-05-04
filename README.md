# LibraryOverview

This project is a simple web application that scrapes a user's GoodReads data and visually displays info about the books the user has read.

The project contains four python files:
1. Scraping GoodReads - This file takes a user's username and password to scrape the user's GoodReads data (such as their favorite books)
2. Downloading PDF's - This file takes the user's GoodReads data and uses it to download pdf's for later analysis.
3. Semantic Analysis and Visualization - This file uses the downloaded PDF's to analyze and visualize the books using tools such as sentiment analysis and wordclouds.
4. Flask App - This file deploys the project as a web application using flask.

The following anaconda environment with python 3.10 version, and the following packages installed is required:
- pandas
- requests
- selenium
- beautifulsoup
- ...
- etc.
