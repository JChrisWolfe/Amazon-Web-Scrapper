# Amazon-Web-Scrapper

## Project Description
This is a simple project that can be used in future projects to scrape a set of pre-scripted Amazon Product webpage(s). The information scraped from the Amazon Product pages would then be added to `AmazonWebScraperDataset.csv`. Any future Web Scrapping projects where more information would be scraped from [Amazon](https://www.amazon.com/) could be based from this project unless more conplex web scrapping is involved. In which case modules like Scrapy, Selenium, etc. would be needed as Beautiful Soup 4 has some limitations as the project grows.

## Required Software and Modules

For this project Jupyter was used via [Anaconda](https://www.anaconda.com/products/distribution). This would insure that you'd have all the necessary software and even modules are installed to use the project files. In addition depanding on the Operating System you are using you are going to want to install modules with Conda via the command line prompt:

<p><code>conda install -c anaconda beautifulsoup4</code></p>

Then add the following modules to your Python Code:

<ul>
<li><code>from bs4 import BeautifulSoup</code></li>
<li><code>import requests</code></li>
<li><code>import time</code></li>
<li><code>import datetime</code></li>
<li><code>import pandas as pd</code></li>
<li><code>import csv</code></li>
</ul>

## Run the Notebook using Jupyter
All that is required once you've installed the necessary software and modules is to only run this Jupyter Python Notebook is to just startup Jupyter alone or using the Anaconda Software. This project was created on a Windows 10 Operating System using Anaconda.

## Where to Start
Everything on this project starts and ends with `Amazon_Web_Scrapper.ipynb`. This is the Python Notebook also creates the `AmazonWebScraperDataset.csv` file.
