# web-scraping-project
Fetching data from a website using requests + BeautifulSoup and structuring it with pandas.

🌍 Web Scraping & Data Fetching using Python
This project demonstrates how to collect real-world data from a website using Python Web Scraping techniques and convert unstructured HTML content into a structured dataset using Pandas.
It is a beginner-friendly project focused on understanding how websites work behind the scenes and how data can be extracted for analysis.

*Project Goal:

The main objective of this project is to:
Send HTTP requests to a webpage
Parse HTML content
Extract useful information from specific tags
Store extracted data in structured form
Prepare the dataset for analysis

*Technologies & Libraries:

Technology	Purpose
Python	Programming language used
Requests	To fetch webpage content
BeautifulSoup (bs4)	To parse and extract HTML data
lxml	HTML parser for BeautifulSoup
Pandas	To structure and manage data

⚙️ How the Project Works

A request is sent to the target website using the Requests library.
A browser-like User-Agent header is included to avoid request blocking.
The webpage’s HTML is parsed using BeautifulSoup.
Specific HTML elements are located to extract:
Company names
Rating counts
Company type
Address
Extracted data is stored in Python lists.
Lists are combined into a Pandas DataFrame for structured output.

Future improvements section

GitHub badges (Python, Pandas, etc.)

ChatGPT can make mistakes. Check important info.
