# Python Web Scraping Project

## Project Overview

This project demonstrates how to collect data from a website using Python web scraping techniques.

---

## Project Structure

```
python-web-scraping-project
¦
+-- notebook
¦   +-- scraping_table_from_website.ipynb
¦
+-- data
¦   +-- scraped_data.csv
¦
+-- images
¦   +-- scraping_preview.png
¦
+-- README.md
```

---

## How the Script Works

1. Send a request to a website using the `requests` library.
2. Parse the HTML content using BeautifulSoup.
3. Locate the desired table within the webpage.
4. Extract rows and columns from the table.
5. Store the extracted data in a structured format.