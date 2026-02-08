Web Scraping Assignment
-----------------------

This repository contains my web scraping assignment completed using Python.
The goal of this assignment is to practice fetching web pages, extracting
textual content, and parsing HTML elements using the requests and
BeautifulSoup libraries.

Requirements:
-------------
- Python 3.x
- requests
- beautifulsoup4

You can install the required libraries using:
pip install requests beautifulsoup4


Assignment Tasks:
-----------------
1. Fetch the website https://www.visitmaryland.org/ using the requests library
   and print the HTTP status code.

2. Extract and display all visible text from the Maryland website while
   ignoring script and style tags.
   Note: The website returns an HTTP 403 status code and displays a bot
   protection message because it blocks automated requests that do not
   execute JavaScript.

3. Fetch the Wikipedia page for "Natural Language Processing" and extract
   all headings (h1, h2, h3) from the page.

4. Extract and display all URLs (href values) found on the Wikipedia page.

5. Extract the first paragraph from the Wikipedia page, print it to the
   console, and save it to a local text file named "nlp_intro.txt".
