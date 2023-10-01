Web Scraper for Paginating and Converting HTML Tables to Markdown
Overview
This Python project is a web scraper designed to extract data from a website by paginating through its first 5 pages and converting HTML tables into Markdown format. It uses popular libraries like Requests for HTTP requests and BeautifulSoup for HTML parsing.

Features
Paginates through the first 5 pages of a specified website.
Extracts the title and content of each page.
Converts HTML tables found on the pages into Markdown tables.
Saves the extracted data as JSON files with 'title' and 'content' keys.
Flexible and customizable for different websites.
How to Use
Clone the repository to your local machine.
Install the required libraries using pip install requests beautifulsoup4.
Modify the base_url variable to specify the website you want to scrape.
Run the Python script to start the scraping process.
