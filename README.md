# LibraryOverview

This project scrapes a user's GoodReads data and visually displays info about the user's GoodReads library and about the books the user has read.
The project consists of 4 jupyter notebooks.

The notebooks:
1. scrape_goodreads.ipynb - This file takes a user's username and password to scrape and download the user's GoodReads data (which books they have read) and saves it as a csv file.
2. Library_analysis.ipynb - This notebook summarizes the user's GoodReads library (number of books read, top 5 books, favorite authors etc.)
3. download_pdfs.ipynb - This file takes the user's GoodReads data and uses it to download pdf's (from www.libgen.is) for later analysis.
4. Wordclouds.ipynb - This notebook displays a list of the downloaded PDF's and lets the user pick one of the books and make a wordcloud.

Furthermore, the project contains a requirements.txt file with all the necessary packages/libaries and their versions. 
