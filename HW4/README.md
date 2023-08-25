### README for Homework #4
# Web Crawling Assignment

## Overview
This assignment aims to familiarize students with **web crawling** by extracting data from the website [ketabrah.ir](http://ketabrah.ir). The goal is to collect information about books categorized under different subjects and store the data in a structured CSV file.

## Functionality
Using a Python web crawling library (e.g., BeautifulSoup, Scrapy, or Selenium), the assignment involves crawling the website ketabrah.ir and extracting book information. Each book contains details such as:
- **Subject** (Category of the book)
- **Title** (Book name)
- **Author** (Writer of the book)
- **Translator** (If available)
- **Publisher**
- **Price**
- **Year of Publication**
- **User Rating** (Score given by users)
- **Number of Reviews** (Count of user reviews)

## Libraries Used
- **BeautifulSoup**: For parsing HTML and extracting data from web pages.
- **Scrapy**: A framework for web crawling and scraping.
- **Selenium**: For automating web browsers and handling dynamic content.

## Requirements
- **Language**: Python
- **Libraries**: Install the required libraries using pip:
  ```bash
  pip install beautifulsoup4 scrapy selenium
  ```