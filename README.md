# First Webscrap

## Booking.com Reviews Scraper

This project represents a personal endeavor to scrape reviews and ratings from Booking.com for three specific hotels. Approximately 300 reviews were collected for each hotel. The challenge of dynamically rendered content on Booking.com was overcome using a combination of Selenium for browser automation and BeautifulSoup for parsing the HTML content.

## Technologies Used

- **Selenium**: Automated web browser interaction to navigate through Booking.com's dynamically rendered pages.
- **BeautifulSoup**: Extracted and parsed HTML content to retrieve reviews and ratings.

## How It Works

The script initiates a Selenium Webdriver to programmatically navigate to each of the three hotel pages on Booking.com. It then dynamically scrolls through the review sections to ensure all reviews are loaded and captures the page's HTML content. BeautifulSoup is utilized to parse the HTML and extract relevant data such as review text and rating.

## Review

- Code is available in Jupyter notebook file named `Scraping Reviews and Ratings.ipynb`
- CSV is generated for the scraped data named `scrap_date.csv`
