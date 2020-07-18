# Social Analytics

A group project for SMU's IS434 Social Analytics & Applications

## Background

Singapore is a food paradise and it is a billion-dollar industry where it consists of S$8.3billion annual receipts, S$4.3billion annual contribution to the country’s GDP, and 48,000 workers are employed. According to the Ministry of Trade & Industry’s (MTI) Food Industry Transformation Map, there is a 4.5% of productivity growth and 2,000 new jobs are created in the food industry. Our team is interested in assisting the new and existing food business owners to maximise their share in this industry by recommending potentially popular food items or cuisine to them based on Instagram and identifying potential food influencers to work with to maximise their reach and exposure.

## Problem

Due to the current COVID-19 pandemic, a lot of usual businesses eg. manufacturing, offices, are suffering. In order to help them, we want to identify a promising industry for them to start a new business. The food industry is also experiencing a slight setback and we want to help them identify what they can sell in order to increase their income. 
This can be done by suggesting food that is going to be trending, which they can sell, and the respective influencers to engage.

## Brief Workflow

1. Instagram Scraping
2. Corpus Creation
3. Sentiment Analysis
4. Food/Cuisine and Influencers Analysis
5. Social Network Analysis

## Outcomes

- Tableau dashboards for new and existing business owners who are interested in the food industry
- Social Network Graph

## Dataset Used

- [Instagram](https://github.com/terenceneo/Social-Analytics/tree/master/Instagram)

## Getting Started

### Tools & Packages
- Python Selenium WebDriver, BeautifulSoup, Pandas:
```
from selenium import webdriver
from selenium.webdriver.chrome.options import Options
from bs4 import BeautifulSoup as bs
from urllib.request import urlopen
import pandas as pd
```
- Phantombuster: https://phantombuster.com/login
- Tableau (2020.1): https://www.tableau.com/products/desktop/download
- Gephi (0.9.2): https://gephi.org/users/install/

### Environment

- [Jupyter lab](environment.md)

## View project:

- [Website](https://terenceneo.github.io/Social-Analytics/)
- [Proposal Pitch](https://github.com/terenceneo/Social-Analytics/blob/master/Final%20Submission/G10_Group6-Terence_FoodieBuddie_IS434_Social_Analytics_Proposal_Pitch.pptx)
- [Final Presentation](https://github.com/terenceneo/Social-Analytics/blob/master/Final%20Submission/G10_Group6-Terence_FoodieBuddie_IS434_Social_Analytics_Final_Presentation.pdf)
- [Code](https://github.com/terenceneo/Social-Analytics/tree/master/Code)
- [Report](https://github.com/terenceneo/Social-Analytics/blob/master/Final%20Submission/Group%20Project%20Report.docx)
- [Medium Article](https://medium.com/@terencenyy/b7f3eed0ac77)

## The Team
- Terence Neo
- Gracia Yuwono Kwantalalu
- Kok Jim Meng
- Christal Poon

## Acknowledgements
- https://www.enterprisesg.gov.sg/industries/type/food-manufacturing/industry-profile
- https://en.wikipedia.org/wiki/Category:Asian_cuisine_by_country
- https://en.wikipedia.org/wiki/Category:Singaporean_cuisine
- https://en.wikipedia.org/wiki/Singaporean_cuisine
- https://monkeylearn.com/text-classification/
- https://www.analyticsvidhya.com/blog/2018/04/a-comprehensive-guide-to-understand-and-implement-text-classification-in-python/
- https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0
- https://simpleanalytical.com/how-to-web-scrape-wikipedia-python-urllib-beautiful-soup-pandas
- https://towardsdatascience.com/named-entity-recognition-with-nltk-and-spacy-8c4a7d88e7da
- https://towardsdatascience.com/custom-named-entity-recognition-using-spacy-7140ebbb3718
- https://towardsdatascience.com/step-by-step-tutorial-web-scraping-wikipedia-with-beautifulsoup-48d7f2dfa52d
