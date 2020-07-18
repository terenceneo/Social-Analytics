# Social Analytics

![](https://github.com/terenceneo/Social-Analytics/blob/master/docs/cover.jpg)

Social data analysis, building a food and food influencer recommender, a must have for your food business!

## Background

Singapore is an [international food paradise](https://medium.com/r/?url=https%3A%2F%2Fwww.straitstimes.com%2Fopinion%2Fglobal-city-foodies-paradise) with a [billion-dollar food industry](https://medium.com/r/?url=https%3A%2F%2Ffoodindustry.asia%2Fthe-food-industry-a-strong-contributor-to-singapores-economy). The food industry in Singapore is worth S$8.3 billion in annual receipts and makes S$4.3 billion annual contribution to the country's GDP with 48,000 workers employed. According to the Ministry of Trade & Industry's (MTI) [Food Industry Transformation Map](https://medium.com/r/?url=https%3A%2F%2Fwww.enterprisesg.gov.sg%2Findustries%2Ftype%2Ffood-manufacturing%2Findustry-profile), there is a 4.5% of productivity growth and 2,000 new jobs planned for 2020. This makes Singapore's food industry an attractive sector for budding entrepreneurs.

## Problem

Due to the current COVID-19 pandemic, a lot of usual businesses eg. manufacturing, offices, are suffering. In order to help them, we want to identify a promising industry for them to start a new business.

Furthermore, as a [result of the COVID-19 pandemic](https://medium.com/r/?url=https%3A%2F%2Fwww.scmp.com%2Fnews%2Fasia%2Fsoutheast-asia%2Farticle%2F3081906%2Fcoronavirus-singapores-home-based-food-businesses-hit-hard) and in its [aftermath](https://medium.com/r/?url=https%3A%2F%2Fwww.todayonline.com%2Fsingapore%2Ffb-sales-fall-april-amid-circuit-breaker-some-restaurants-choose-close-shop-good), existing food businesses are hard pressed to reconsider their offerings and business strategy in order to amass enough sales to [keep up or fall out](https://medium.com/r/?url=https%3A%2F%2Fvulcanpost.com%2F700385%2Ffb-businesses-closed-down-singapore%2F) of the race.

This can be done by:

1. Making personalised recommendations on trending food for businesses to sell
2. Making personalised recommendations on relevant influencers to engage in promoting their businesses and food

## Brief Workflow

1. Instagram Scraping
2. Corpus Creation
3. Sentiment Analysis
4. Food/Cuisine and Influencers Analysis
5. Social Network Analysis

## Outcomes

- Data visualisation dashboards for new and existing business owners who are interested in the food industry
- Social Network Graph

## Dataset Used

- [Instagram scrapes](https://github.com/terenceneo/Social-Analytics/tree/master/Instagram) of posts from the top 12 food influencers in Singapore from 30th May to 30th June 2020

## Getting Started

### Tools & Packages

- Standard data manipulation packages

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

- Data scraping packages

```python
from selenium import webdriver
from selenium.webdriver.chrome.options import Options
from bs4 import BeautifulSoup as bs
from urllib.request import urlopen

import wikipedia
import codecs
```

- Natural Language Processing packages

```python
import re
from nltk.corpus import stopwords
from nltk.tokenize import word_tokenize
from nltk.sentiment.vader import SentimentIntensityAnalyzer as SIA
from wordcloud import WordCloud
```

- Phantombuster: https://phantombuster.com/login
- Tableau (2020.1): https://www.tableau.com/products/desktop/download
- Gephi (0.9.2): https://gephi.org/users/install/

### Environment

- [Jupyter lab](environment.md)

## View project:

<!-- To change presentation to google slides view only links -->

- [Website](https://terenceneo.github.io/Social-Analytics/)
- [Proposal Pitch](https://github.com/terenceneo/Social-Analytics/blob/master/Final%20Submission/G10_Group6-Terence_FoodieBuddie_IS434_Social_Analytics_Proposal_Pitch.pptx)
- [Final Presentation](https://github.com/terenceneo/Social-Analytics/blob/master/Final%20Submission/G10_Group6-Terence_FoodieBuddie_IS434_Social_Analytics_Final_Presentation.pdf)
- [Code](https://github.com/terenceneo/Social-Analytics/tree/master/Code)
- [Report](https://github.com/terenceneo/Social-Analytics/blob/master/Final%20Submission/Group%20Project%20Report.pdf)
- [Medium Article](https://medium.com/@terencenyy/b7f3eed0ac77)

## The Team

- [Terence Neo](https://github.com/terenceneo)
- [Gracia Yuwono Kwantalalu](https://github.com/GraciaYuwonoKwantalalu)
- [Kok Jim Meng](https://github.com/jimmeng-kok-2017)
- [Christal Poon](https://github.com/chriseasalt)

## Acknowledgements

## References

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
