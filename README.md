Overview:
This project is a mini desktop application built using Python that allows users to scrape and display technology-related news or job postings based on their preferences. The application uses web scraping techniques to gather real-time information from external websites and outputs it to the user in a user-friendly manner.

Key Features:
Technology News Updates (Hacker News):

Users can select the option to fetch the latest technology-related news from the Hacker News website. The app scrapes the homepage of Hacker News and displays top articles with more than 99 votes.
Job Postings (Craigslist):

Users can select the option to scrape job postings for Software Engineer positions from Craigslist (Chennai). The app retrieves job titles and descriptions from the Craigslist search results.
Interactive CLI:

The application has an interactive command-line interface where the user can choose between fetching technology news or job postings.
It allows the user to continue scraping as long as they choose to do so.
Libraries Used:
requests: To send HTTP requests to websites and retrieve their content.
BeautifulSoup: To parse and navigate HTML documents for extracting the necessary data.
pprint: To print data in a structured, easy-to-read format.
