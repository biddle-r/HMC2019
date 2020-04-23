# Data for "Leveraging Sentiment Distributions to Distinguish Figurative From Literal Health Reports on Twitter" paper presented at WebConf 2020.

***

Data file contains three columns:

**TweetID** : The tweet_id needed to query the Twitter API to download the tweet

**Label** : Class Label

| Label        | Label Description           | Example |
| ------------- |-------------| -------------|
| 0      | Figurative Mentions | he is such a *headache* |
| 1      | Other Mentions      | try this home *headache* remedy now |
| 2      | Health mentions     | i have a *headache* |

**Health Keyword** : The health keyword mentioned in the tweet. (i.e, cough, cancer, etc) 


***

If you use this dataset in your work please cite 

```
@inproceedings{10.1145/3366423.3380198,
author = {Biddle, Rhys and Joshi, Aditya and Liu, Shaowu and Paris, Cecile and Xu, Guandong},
title = {Leveraging Sentiment Distributions to Distinguish Figurative From Literal Health Reports on Twitter},
year = {2020},
isbn = {9781450370233},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3366423.3380198},
doi = {10.1145/3366423.3380198},
booktitle = {Proceedings of The Web Conference 2020},
pages = {1217–1227},
numpages = {11},
keywords = {Figurative Language, Public Health Surveillance, Health Mention Classification, Twitter},
location = {Taipei, Taiwan},
series = {WWW ’20}
}
```

Please see https://github.com/emory-irlab/PHM2017/ for the original version of our extended dataset provided here.
