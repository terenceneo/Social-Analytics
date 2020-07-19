# Getting Started

## Files

### Code

- [Corpus_Wikipedia.ipynb](Corpus_Wikipedia.ipynb): Food corpus creation from Wikipedia and Blog posts scrapes
- [Corpus_Name Entity Recognition.ipynb](Corpus_Name%20Entity%20Recognition.ipynb): Named Entity Extraction for Corpus creation
- [Data Labelling.ipynb](Data%20Labelling.ipynb): Labelling of Instagram posts with Food and Cuisine names from Wikipedia Corpus, and Pareto Analysis to supplement corpus
- [Sentiment Analysis.ipynb](Sentiment%20Analysis.ipynb): Sentiment Analysis on Instagram posts and comments

### Data Sources

- [japfood.html](japfood.html): Japanese food blog - _required for [Corpus_Wikipedia.ipynb](Corpus_Wikipedia.ipynb)_
- [koreanfood.html](koreanfood.html): Korean food blog - _required for [Corpus_Wikipedia.ipynb](Corpus_Wikipedia.ipynb)_

## Tools & Packages

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

## Environment

- [Jupyter lab](../environment.md)
