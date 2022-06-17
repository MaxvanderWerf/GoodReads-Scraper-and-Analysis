# LibraryOverview

This project scrapes a user's GoodReads data and visually displays info about the user's GoodReads library and about the books the user has read.
The project consists of 4 jupyter notebooks.

The notebooks:
1. scrape_goodreads.ipynb - This file takes a user's username and password to scrape and download the user's GoodReads data (which books they have read) and saves it as a csv file. - Check example video 1. below to see how this works.
2. Library_analysis.ipynb - This notebook summarizes the user's GoodReads library (number of books read, top 5 books, favorite authors etc.)
3. download_pdfs.ipynb - This file takes the user's GoodReads data and uses it to download pdf's (from www.libgen.rs) for later analysis. - Check example video 2. below to see how this works.
4. Wordclouds.ipynb - This notebook displays a list of the downloaded PDF's and lets the user pick one of the books and make a wordcloud. - Check below to see one of those wordclouds.

Furthermore, the project contains a requirements.txt file with all the necessary packages/libaries and their versions. 


#### Examples
https://user-images.githubusercontent.com/68983725/174291079-0890f65e-50f7-4ca7-b313-8596043470dd.mp4
Example Video 1. - Scraping GoodReads

(https://user-images.githubusercontent.com/68983725/174291094-56af4f6a-0abc-4789-83ae-b60385adbf36.mp4)
Example Video 2. - Downloading PDFs from libgen.rs

![WordCloud - Thinking, Fast and Slow](https://user-images.githubusercontent.com/68983725/174292092-da27fa47-29a8-47d2-be49-edee40bb850f.png)

Example Image - WordCloud of Daniel Kahneman's Thinking, Fast and Slow


