# Front-end Webscraping with Beautiful Soup

## About The Project

### Description
Front-end Web Scraping of Tesco Malaysia website for product countering initiative, utilizing Beautiful Soup python package.

### Methodology
1. Use `requests.get()` to access Tesco Malaysia website and extract the website's HTML using `.text`
2. Parse HTML code using `BeautifulSoup()`
3. Scrape data from parsed HTML using `.find_all()` from BeautifulSoup package
