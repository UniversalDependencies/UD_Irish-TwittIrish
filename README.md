# Summary

A Universal Dependencies treebank of 866 tweets in modern Irish.

# Introduction

The TwittIrish treebank contains 866 Irish language tweets from two corpora: 166 tweets from NTC and 700 tweets from TTC. 

NTC consists of 25000 tweets posted between 2010 and 2019 randomly sampled from a database of 14111 users who have tweeted in Irish.
TTC consists of 1493 Irish language tweets posted between 2009 and 2014 randomly sampled from 950000 tweets by 8000 users. Lemmas and POS-tags were added as a part of a PhD research project by Dr. Teresa Lynn at Dublin City University, Ireland (Lynn, 2016)

Irish language tweets were identified by the website http://indigenoustweets.com/. Non-Irish tweets were filtered out using a simple character-trigram language identifier. 

The conversion from the TTC annotation scheme to the UD annotation scheme was designed by Lauren Cassidy, Teresa Lynn and Jennifer Foster at Dublin City University, Ireland. The conversion was automatic, with manual review, in consultation with other researchers working on UD annotation of User Generated Content (Sanguinetti et al., 2020).

Trees were parsed automatically using the Irish UD Treebank (Lynn and Foster, 2016) as training data, followed by manual review.

# Acknowledgments

We wish to thank all of the contributors to the IUDT annotation and Kevin Scannell for providing data and linguistic advice.

The creation of TwittIrish treebank from 2019-2021 is funded by the Irish Government
The Department of Tourism, Culture, Arts, Gaeltacht, Sport and Media under the GaelTech project.

This research is partially supported by Science Foundation Ireland through the ADAPT Centre for Digital Content Technology. The ADAPT Centre for Digital Content Technology is funded under the SFI Research Centres Programme (Grant 13/RC/2106)
and is co-funded under the European Regional Development Fund.

## References

* Lynn, T. (2016) Irish Dependency Treebanking and Parsing. Dublin City University.
* Lynn, T. and Foster, J. (2016) ‘Universal Dependencies for Irish’, p. 14.
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
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Cassidy, Lauren; Lynn, Teresa; Foster, Jennifer; McGuinness, Sarah
Contributing: elsewhere
Contact: lauren.cassidy@adaptcentre.ie; teresa.lynn@adaptcentre.ie; jennifer.foster@dcu.ie
===============================================================================
</pre>
