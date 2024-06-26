# Summary

A Universal Dependencies treebank of 2596 tweets in modern Irish.

# Introduction

The TwittIrish treebank contains 2596 Irish language tweets from two corpora: 1297 tweets from the New Twitter Corpus [NTC] and 1299 tweets from the Lynn Twitter Corpus [LTC]. 

* NTC consists of 25000 tweets posted between 2010 and 2019 randomly sampled from a database of 14111 users who have tweeted in Irish.
* LTC consists of 1493 tweets posted between 2009 and 2014 randomly sampled from 950000 tweets by 8000 users. Lemmas and POS-tags were added to LTC a part of a PhD research project by Dr. Teresa Lynn at Dublin City University, Ireland (Lynn, 2016) (Lynn, Scannell and Maguire, 2015). The LTC data was further annotated with Code-Switching information (Lynn and Scannell, 2019). The LTC data can be found here: https://github.com/tlynn747/IrishTwitterPOS.

Irish language tweets were identified by Kevin Scannell as part of the Indigenous Tweets website project http://indigenoustweets.com/. Non-Irish tweets were filtered out using a simple character-trigram language identifier.

The conversion from the LTC annotation scheme to the UD annotation scheme was designed by Lauren Cassidy as part of an PhD project, supervised by Dr. Teresa Lynn and Dr. Jennifer Foster at Dublin City University, Ireland. The conversion was automatic, with manual review, in consultation with other researchers working on UD annotation of User Generated Content (Sanguinetti et al., 2020).

Trees were parsed automatically using the Irish UD Treebank [IUDT] (Lynn and Foster, 2016) as training data, followed by manual review. The IUDT can be found here https://github.com/UniversalDependencies/UD_Irish-IDT.

# Acknowledgments

We wish to thank all of the contributors to the IUDT annotation, Kevin Scannell for providing data and linguistic advice, and James Barry for improving the accuracy of automatic parsing by experimenting with different models.

The creation of TwittIrish treebank from 2019-2023 is funded by the Irish Government
The Department of Tourism, Culture, Arts, Gaeltacht, Sport and Media under the GaelTech project.

This research is partially supported by Science Foundation Ireland through the ADAPT Centre for Digital Content Technology. The ADAPT Centre for Digital Content Technology is funded under the SFI Research Centres Programme (Grant 13/RC/2106)
and is co-funded under the European Regional Development Fund.

## References
* TwittIrish: A Universal Dependencies Treebank of Tweets in Modern Irish (Cassidy et al., ACL 2022)
* Treebanking user-generated content: a UD based overview of guidelines, corpora and unified recommendations (Sanguinetti et al., Lang Resources & Evaluation 2022)
* Code-switching in Irish tweets: A preliminary analysis (Lynn and Scannell, 2019)
* Irish Dependency Treebanking and Parsing (Lynn, Dublin City University 2016)
* Universal Dependencies for Irish (Lynn and Foster, CLTW 2016)
* Minority Language Twitter: Part-of-Speech Tagging and Analysis of Irish Tweets (Lynn et al., W-NUT 2015)


# Changelog
* 2023-04-05
  * train set (866 tweets) and dev set (864 tweets) added
  * usernames, phone numbers and email addresses anonymised
  * ids updated
* 2021-05-15 v2.8
  * Initial release in Universal Dependencies. 866 tweets in test set

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.8
License: CC BY-SA 4.0
Includes text: yes
Genre: social
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: not available
Relations: manual native
Contributors: Cassidy, Lauren; Lynn, Teresa; Foster, Jennifer; McGuinness, Sarah
Contributing: elsewhere
Contact: lauren.cassidy@adaptcentre.ie; teresa.lynn@adaptcentre.ie
===============================================================================
</pre>
