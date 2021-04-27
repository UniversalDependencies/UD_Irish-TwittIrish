# Summary

A Universal Dependencies treebank of 866 tweets in modern Irish.

# Introduction

The TwittIrish treebank contains 866 Irish language tweets from two corpora: 166 tweets from the Cassidy Twitter Corpus [CTC] and 700 tweets from the Lynn Twitter Corpus [LTC]. 

* CTC consists of 25000 tweets posted between 2010 and 2019 randomly sampled from a database of 14111 users who have tweeted in Irish.
* LTC consists of 1493 tweets posted between 2009 and 2014 randomly sampled from 950000 tweets by 8000 users. Lemmas and POS-tags were added to LTC a part of a PhD research project by Dr. Teresa Lynn at Dublin City University, Ireland (Lynn, 2016) (Lynn, Scannell and Maguire, 2015). The LTC data was further annotated with Code-Switching information (Lynn and Scannell, 2019). The LTC data can be found here: https://github.com/tlynn747/IrishTwitterPOS.

Irish language tweets were identified by Kevin Scannell as part of the Indigenous Tweets website project http://indigenoustweets.com/. Non-Irish tweets were filtered out using a simple character-trigram language identifier.

The conversion from the TTC annotation scheme to the UD annotation scheme was designed by Lauren Cassidy as part of an MSc project, supervised by Dr. Teresa Lynn and Dr. Jennifer Foster at Dublin City University, Ireland. The conversion was automatic, with manual review, in consultation with other researchers working on UD annotation of User Generated Content (Sanguinetti et al., 2020).

Trees were parsed automatically using the Irish UD Treebank [IUDT] (Lynn and Foster, 2016) as training data, followed by manual review. The IUDT can be found here https://github.com/UniversalDependencies/UD_Irish-IDT.

# Acknowledgments

We wish to thank all of the contributors to the IUDT annotation, Kevin Scannell for providing data and linguistic advice, and James Barry for improving the accuracy of automatic parsing by experimenting with different models.

The creation of TwittIrish treebank from 2019-2021 is funded by the Irish Government
The Department of Tourism, Culture, Arts, Gaeltacht, Sport and Media under the GaelTech project.

This research is partially supported by Science Foundation Ireland through the ADAPT Centre for Digital Content Technology. The ADAPT Centre for Digital Content Technology is funded under the SFI Research Centres Programme (Grant 13/RC/2106)
and is co-funded under the European Regional Development Fund.

## References

* Lynn, T. (2016) Irish Dependency Treebanking and Parsing. Dublin City University.
* Lynn, T. and Foster, J. (2016) ‘Universal Dependencies for Irish’, p. 14.
* Lynn, T. and Scannell, K. (2019) ‘Code-switching in Irish tweets: A preliminary analysis’, p. 9.
* Lynn, T., Scannell, K. and Maguire, E. (2015) ‘Minority Language Twitter: Part-of-Speech Tagging and Analysis of Irish Tweets’, in Proceedings of the Workshop on Noisy User-generated Text. Proceedings of the Workshop on Noisy User-generated Text, Beijing, China: Association for Computational Linguistics, pp. 1–8. doi: 10.18653/v1/W15-4301.
* Sanguinetti, M. et al. (2020) ‘Treebanking User-Generated Content: A Proposal for a Uniﬁed Representation in Universal Dependencies’, p. 11.

# Changelog

* 2021-05-15 v2.8
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.8
License: CC BY-SA 4.0
Includes text: yes
Genre: social
Lemmas: converted with corrections
UPOS: converted with corrections
XPOS: not available
Features: not available
Relations: automatic with corrections
Contributors: Cassidy, Lauren; Lynn, Teresa; Foster, Jennifer; McGuinness, Sarah
Contributing: elsewhere
Contact: lauren.cassidy@adaptcentre.ie; teresa.lynn@adaptcentre.ie
===============================================================================
</pre>
