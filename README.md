# LibraryOverview

This project scrapes a user's GoodReads data and visually displays info about the user's GoodReads library and about the books the user has read.
The project consists of 2 python files and 2 jupyter notebooks.

The python files:
1. scrape_goodreads.py - This file takes a user's username and password to scrape and download the user's GoodReads data (such as their favorite books) and saves it as a csv file.
2. download_pdfs.py - This file takes the user's GoodReads data and uses it to download pdf's (from www.libgen.is) for later analysis.

The jupyter notebook files:
1. library_analysis.py - This notebook summarizes the user's GoodReads library (number of books read, top 5 books, favorite authors etc.)
2. make_wordclouds.py - This notebook uses the downloaded PDF's to analyze and visualize the books using tools such as sentiment analysis and wordclouds.

To make the code work, the python files need to be run in that order. 

An anaconda environment with python 3.10 version, and the following packages installed is required:
- pandas
- requests
- selenium
- beautifulsoup
- ...
- etc.
