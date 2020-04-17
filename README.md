### Usage Of Disaster News Information For Predicting Disasters In Ukraine

This is a supplement code for the research dedicated to extraction of valuable terminology / facts from disaster-related news in Ukraine.

Script provided in `Disaster prediction.ipynb`:
* collects news from one of the Ukrainian internet news portals (**24tv.ua**)
* classifies them using provided tags
* extracts location where disaster happened using NER model for Ukrainian language
* detects anomalies in the news frequency by location
* compares number of gathered news with information published by State Emergency Service of Ukraine

### Data

News were collected from web-portal of ukrainian news - 24tv.ua 
Collected database of news is stored in the `allnews.csv`
Links to the news are stores in the  `urls_.csv`

### Libraries

- scrapy
- NER model for Ukrainian language (https://github.com/lang-uk)
- numpy
- pandas
- scipy
- sklearn
