# The Corpus of Singapore English Messages (CoSEM)

![](https://github.com/wdwgonzales/CoSEM/blob/main/logo.png)


### Overview
The Corpus of Singapore English Messages (CoSEM) is a monitor corpus of online text messages collected between 2016 and 2022, compiled and managed by a group of scholars who share an interest in Colloquial Singapore English (CSE) research.
<br />

#### Features
- Contains the following metadata (as reflected in tags)
	- age
	- gender
	- race
	- nationality
	- year of collection
	- year of utterance
- in hierarchical text format: primed for concordance software including AntConc, CasualConc
<br />
<br />

### Disclaimer
The public version of the CoSEM (see 'Corpus Version' below) is a "sample" version with limitations. For example, based on our initial assessment, the scrubber does its work for the most part. However, we note that it scrubs non-name information that might be important for analyses. For example, (a) below becomes (b). Furthermore, we observed that it only scrubs information from the [`scrubadub`](https://scrubadub.readthedocs.io/en/stable/ "scrubadub") package. As such, we recommend that you exercise caution in using the public version of the corpus. We put forward our intention of contributing to the scholarly community by showing whatever we can at this time. We thank you for your patience.

<br />

```
(a) <COSEM:18MF02-9431-23CHF-2014> Why u still dunwan go homr
(b) <COSEM:18MF02-9431-23CHF-2014> Why u still {{NAME}} go {{NAME}}
```

<br />
<br />



<br />

### Overview


#### Collection methodology

Please check out [our overview paper](https://github.com/wdwgonzales/CoSEM/tree/main/Overview%20paper).
<br />
<br />


#### Personal Data Scrubbing
We used the [`scrubadub`](https://scrubadub.readthedocs.io/en/stable/ "scrubadub") package to scrub the public version of the corpus.

<br />


#### Corpus metadata or tag format
Every line of utterance has been tagged with an identifier tag. The tag format allows for easy identification of a line of utterance within the corpus, and for easy interpretation of relevant metadata. For example, the tag < 17CF15-40341-20CHF-2016 > shows that the utterance was collected in the year 2017 by a Chinese female with identification number 15; the utterance is line 40341 in the corpus; and the line was produced by a 20-year-old Chinese Singaporean female in 2016.

<br />
<br />

#### Corpus Version
The current version stands at 6.9 million words (as of November 2, 2022); however, the version released to the public - fully anonymized using the [`scrubadub`](https://scrubadub.readthedocs.io/en/stable/ "scrubadub") package - is roughly 2 million words. We hope to release the scrubbed corpus incrementally over the next few years.

<br />
<br />

### Team
- [Assoc. Prof. Mie HIRAMOTO](https://profile.nus.edu.sg/fass/ellmh/ "Assoc. Prof. Mie HIRAMOTO") (National University of Singapore, Singapore) - Principal Investigator
- [Prof. Jakob LEIMGRUBER](https://jakobleimgruber.ch/en/home "Prof. Jakob LEIMGRUBER") (University of Regensburg, Germany)
- [Asst. Prof. Wilkinson Daniel Wong GONZALES](https://www.wdwgonzales.com "Asst. Prof. Wilkinson Daniel Wong GONZALES") (The Chinese University of Hong Kong, Hong Kong SAR, People's Republic of China) - Database Manager, Data Analyst
- [Jun Jie LIM](https://limjunjie.com "Jun Jie LIM") (University of California, San Diego, USA)

<br />
<br />


### Overview paper
We have published a paper that explains the motivations behind developing a new corpus for the investigation of CSE in 2021. It documents the process of compiling and organizing CoSEM and describes the corpus’s initial structure and composition. We further discuss the social variables used in tagging the data, as well as ethical challenges, advantages, and disadvantages unique to online message datasets. In addition, we present preliminary analyses of two selected CSE features: (1) the Hokkien-derived expression (bo)jio and (2) sentence-final adverbs (already, also, only). We concluded the article with notes on future directions.

The paper can be found [here](https://github.com/wdwgonzales/CoSEM/tree/main/Overview%20paper).
<br />
<br />
<br />

##### To Cite
Please cite the overview paper if you use our corpus or mention it in your work.

<br />
<br />

Gonzales, Wilkinson Daniel Wong, Mie Hiramoto, Jakob Leimgruber, Jun Jie Lim. 2021. The Corpus of Singapore English Messages (CoSEM). _World Englishes_, Wiley. https://doi.org/10.1111/weng.12534

<br />
<br />

```
@article{gonzales_corpus_2021,
	title = {The {Corpus} of {Singapore} {English} {Messages} ({CoSEM})},
	issn = {0883-2919, 1467-971X},
	url = {https://onlinelibrary.wiley.com/doi/10.1111/weng.12534},
	doi = {10.1111/weng.12534},
	language = {en},
	urldate = {2022-02-19},
	journal = {World Englishes},
	author = {Gonzales, Wilkinson Daniel Wong and Hiramoto, Mie and R. E. Leimgruber, Jakob and Lim, Jun Jie},
	month = feb,
	year = {2021},
}
```

<br />
<br />


### Related papers
We would highly appreciate it if you can cite these alongside the overview paper, if you decide to use or mention our corpus:

1. Gonzales, Wilkinson Daniel Wong, Mie Hiramoto, Jakob Leimgruber, Jun Jie Lim. 2022. Is it in Colloquial Singapore English: What variation can tell us about its conventions and development. _English Today_, Cambridge University Press. https://www.doi.org/10.1017/S0266078422000141

2. Leimgruber, Jakob, Jun Jie Lim,  Wilkinson Daniel Wong Gonzales, Mie Hiramoto. 2020. Ethnic and gender variation in the use of Colloquial Singapore English discourse particles, _English Language and Linguistics_, Cambridge University Press.
https://doi.org/10.1017/S1360674320000453

3. Hiramoto, Mie,  Wilkinson Daniel Wong Gonzales, Jakob Leimgruber, Jessica Choo, Junjie Lim. 2022. From Malay to Colloquial Singapore English: A case study of sentence-final particle sia. In A. Ngefac, H. Wolf & T. Hoffmann (eds.) _World Englishes and creole languages today: Existing paradigms and current trends in action_, 117-130. Lincom. https://lincom-shop.eu/LSEL-24-World-Englishes-and-Creole-Languages-Today/en

```

@article{leimgruber_ethnic_2020,
	title = {Ethnic and gender variation in the use of {Colloquial} {Singapore} {English} discourse particles},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	journal = {English Language and Linguistics},
	author = {Leimgruber, Jakob and Lim, Jun Jie and Gonzales, Wilkinson Daniel Wong and Hiramoto, Mie},
	year = {2020},
}

@incollection{hiramoto_malay_2022,
	series = {{LINCOM} {Studies} in {English} {Linguistics} 24},
	title = {From {Malay} to {Colloquial} {Singapore} {English}: {A} case study of sentence-final particle sia},
	booktitle = {World {Englishes} and creole languages today existing paradigms and current trends in action},
	publisher = {Lincom Europa},
	author = {Hiramoto, Mie and Gonzales, Wilkinson Daniel Wong and Leimgruber, Jakob and Lim, Jun Jie and Choo, Jessica Xue Ming},
	editor = {Ngefac, Aloysius and Wolf, Hans-Georg and Hoffman, Thomas},
	year = {2022},
	pages = {117--130},
}

@article{gonzales_is_2022,
	title = {\textit{{Is} it} in {Colloquial} {Singapore} {English}: {What} variation can tell us about its conventions and development},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	issn = {0266-0784, 1474-0567},
	shorttitle = {\textit{{Is} it} in {Colloquial} {Singapore} {English}},
	url = {https://www.cambridge.org/core/product/identifier/S0266078422000141/type/journal_article},
	doi = {10.1017/S0266078422000141},
	language = {en},
	urldate = {2022-08-08},
	journal = {English Today},
	author = {Gonzales, Wilkinson Daniel Wong and Hiramoto, Mie and Leimgruber, Jakob R. E. and Lim, Jun Jie},
	month = jun,
	year = {2022},
	pages = {1--14},
}

```
<br />

### Support
##### Funding/Grants
Singapore Ministry of Education (MOE) Academic Research Fund Tier 1 Funding, Singapore
*Colloquial Singapore English in Social Media and Other Forms of Messaging*
R-103-000-167-115 (2019-2022)
Principal Investigator: Assoc. Prof. Mie Hiramoto

<br />
<br />

##### Research Assistants
_(In alphabetical order of their family names, in upper case)_

- CHOO Xue Ming Jessica
- Sydelle D SOUZA
- Aura Valentine EDEN
- Mohamed Hafiz Bin MOHAMED JURAIMI
- Nadine NG Hui Ning
- PAK Yongkang Vincent
- Luqman Aqil Bin ROZMAN
- YEO Rei-Chi Lauren

<br />
<br />

##### National University of Singapore Undergraduate Research Opportunities (UROP) module
_(In alphabetical order of their family names, in upper case)_

- CHANG Wei Xing
- Athena CHOO
- LIN Taohai
- MAK Kai Feng Darren
- Mohamed Hafiz Bin MOHAMED JURAIMI
- Magdalene ONG Wenli
- PEK Wee Kit Terence
- Reno SAM Wei Jie
- TEN Ting Kai
- Francisca Ann VINCENT
- YEO Ming Wen, Megan Maria
