# ArSarcasm Dataset

**ArSarcasm** is a new Arabic sarcasm detection dataset. The dataset was created using previously available Arabic sentiment analaysis datasets and adds sarcasm and dialect labels to them.
The dataset contains 10,547 tweets, 1,682 (16\%) of which are sarcastic.

The dataset contains the follwoing feilds:
* `tweet`: the original tweet in text surrounded by qoutes (").
* `sarcasm`: boolean the indicates whether a tweet is sarcastic or not.
* `sentiment`: the sentiment from the new annotation (postive, negative, neutral).
* `original_sentiment`: the sentiment in the original annotations.
* `source`: the orignal source of tweet SemEval or ASTD.
* `dialect`: the dialect used in the tweet, we used the 5 main regions in the Arab world, follows the labels and their meanings:
  * `msa`: moder standard Arabic.
  * `egypt`: the dialect of Egypt and Sudan.
  * `levant`: the Levntine dialect including Palestine, Jordan, Syria and Lebanon.
  * `gulf`: the Guld countries including Sauidi Arabia, UAE, Qatar, Bahrain, Yemen, Oman, Iraq and Kuawait.
  * `magreb`: the north African Arabc countries including Algeria, Libya, Tunisia and Morocco.

```
@inproceedings{abu-farha-magdy-2020-arsarcasm, 
title = "From Arabic Sentiment Analysis to Sarcasm Detection: The ArSarcasm Dataset",
author= "Ibrahim, {Abu-Farha} and Walid Magdy",  
year= "2020",
month= "5",
day= "12",
language= "English",  
booktitle = "Proceedings of the 4th Workshop on Open-Source Arabic Corpora and Processing Tools (OSACT)", 
publisher = "European Language Resources Association (ELRA)", }

```
