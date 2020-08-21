# robust_webscraping
## Robust Web Scraping with Proxies using Selenium and Requests, 2020

This repository contains Python Notebooks that can help your web scraping endeavours while using proxies. These proxies are anonymous and use the HTTPS protocol, so you can be confident that your true IP address and any sensitive information being exchanged will be hidden.

The following scraping methods are addressed in this repository:
- How to scrape a list of free, anonymous, HTTPS proxies
- How to use these proxies to surf through the web using selenium, **robustly**
- How to use these proxies to download webpages using requests, **robustly**

**Robust** here means being able to loop through the free proxies until a working one is found to carry out the task. This is incredibly useful given that free proxies can stop working unpredictably. The functions in this repository can help you get around this issue.    

### Scraping FREE proxies seamlessly
These proxies are FREE proxies and will be scraped using the 'proxyscrape' library. Its documentation can be found here: https://pypi.org/project/proxyscrape/ . List of websites where free proxies are scraped from: 
- http://www.proxy-daily.com 
- https://www.sslproxies.org 

Follow the Notebook named 'scraping_proxies.ipynb' to best understand how this library can be used.   

### Robust web surfing with Selenium
The Notebook named 'robust_selenium' can help you better understand how to surf the web with rotating proxies using selenium. This Notebook is built on top of the 'scraping_proxies' Notebook. 

### Robust downloading with Requests
The Notebook named 'robust_requests' can help you better understand how to download webpages with rotating proxies using requests. This Notebook is built on top of the 'scraping_proxies' Notebook. 
