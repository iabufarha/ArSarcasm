# ArSarcasm Dataset

**ArSarcasm** is a new Arabic sarcasm detection dataset. The dataset was created using previously available Arabic sentiment analysis datasets ([SemEval 2017](https://www.aclweb.org/anthology/S17-2088.pdf) and [ASTD](https://www.aclweb.org/anthology/D15-1299.pdf)) and adds sarcasm and dialect labels to them.
The dataset contains 10,547 tweets, 1,682 (16\%) of which are sarcastic. For more details, please check our paper [From Arabic Sentiment Analysis to Sarcasm Detection: The ArSarcasm Dataset]()

## Dataset details:
**ArSarcasm** is provided in a CSV format, we provide an 80/20 train/test split to keep things consistent for future comparisons. The training set contains 8,437 tweets, while the test set contains 2,110 tweets.

The dataset contains the following fields:
* `tweet`: the original tweet text surrounded by quotes (").
* `sarcasm`: boolean the indicates whether a tweet is sarcastic or not.
* `sentiment`: the sentiment from the new annotation (positive, negative, neutral).
* `original_sentiment`: the sentiment in the original annotations (positive, negative, neutral).
* `source`: the original source of tweet SemEval or ASTD.
* `dialect`: the dialect used in the tweet, we used the 5 main regions in the Arab world, follows the labels and their meanings:
  * `msa`: modern standard Arabic.
  * `egypt`: the dialect of Egypt and Sudan.
  * `levant`: the Levantine dialect including Palestine, Jordan, Syria and Lebanon.
  * `gulf`: the Gulf countries including Saudi Arabia, UAE, Qatar, Bahrain, Yemen, Oman, Iraq and Kuwait.
  * `magreb`: the North African Arab countries including Algeria, Libya, Tunisia and Morocco.


## Citation
Please use the follwing citation if you use ArSarcasm:
```
@inproceedings{abu-farha-magdy-2020-arsarcasm, 
title = "From Arabic Sentiment Analysis to Sarcasm Detection: The ArSarcasm Dataset",
author= "Abu-Farha, Ibrahim  and Walid Magdy",  
year= "2020",
language= "English",  
booktitle = "Proceedings of the 4th Workshop on Open-Source Arabic Corpora and Processing Tools (OSACT)", 
publisher = "European Language Resources Association (ELRA)", }

```

## Other resources
If you are interested in other Arabic NLP resources check:
* [Mazajak Sentiment Analyser](http://mazajak.inf.ed.ac.uk:8000)
* [Mazajak Word Embeddings](http://mazajak.inf.ed.ac.uk:8000/#embedding-page)
