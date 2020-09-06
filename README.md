# Choose best Sephora Make-up Products With A Limited Budget
This repository contains two notebooks:
- One notebook named *Web Scrapping For Infinite Scrolling Websites Using Selenium.ipynb* which provides the web scrapping code I developed for infinite scroll web pages
- Another notebook called *How to choose gifts from Sephora if you know nothing about makeup.ipynb* is a project that applies the web scrapping code to extract product information from Sephora, and finally chooses the best combination of two products for me in a given budget. 
- I also posted an article related to this topic: [Using Python and Selenium to Scrape Infinite Scroll Web Pages](https://medium.com/@kuan.wei0413/using-python-and-selenium-to-scrape-infinite-scroll-web-pages-825d12c24ec7)


# Sephora Project Overview
- Created a script that helps me choose the best combination of products with a given budget of $100
- Scaped over 100 "Just arrived" make-up products on Sephora website


## Code and Resources Used
**Python Version**: 3.7

**Packages**: selenium, Beautifulsoup, urljoin, pandas

**Sephora Make-up Website**: ww.sephora.com/ca/en/beauty/new-makeup


## Medium Article
https://medium.com/@kuan.wei0413/using-python-and-selenium-to-scrape-infinite-scroll-web-pages-825d12c24ec7


## Web Scraping
Used self-designed scrapping script for infinite scroll web pages. With each product, the following information is scrapped:
- Product Name
- Product Rating (in stars)
- Number of Reviews
- Price
