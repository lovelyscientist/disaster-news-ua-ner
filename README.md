### Usage Of Disaster News Information For Predicting Disasters In Ukraine

This is a supplement code for the research paper dedicated to extraction of valuable terminology / facts from disaster-related news in Ukraine.
The paper: [Usage of Disaster News Information for Predicting the Emergency Situations in Ukraine](http://visnikkrnu.kdu.edu.ua/statti/2020_1_2020-1-93.pdf)

Script provided in `Disaster prediction.ipynb`:
* collects news from one of the Ukrainian internet news portals (**24tv.ua**)
* classifies them using provided tags
* extracts location where disaster happened using NER model for Ukrainian language
* detects anomalies in the news frequency by location
* compares number of gathered news with information published by State Emergency Service of Ukraine

### Data

News were collected from the web-portal of Ukrainian news - *24tv.ua* 

Database of the collected news is stored in the `allnews.csv`

Links to the news are stores in the  `urls_.csv`

### Libraries

- scrapy
- NER model for Ukrainian language (https://github.com/lang-uk)
- numpy
- pandas
- scipy
- sklearn
