# The Corpus of Singapore English Messages (CoSEM)

![](https://github.com/wdwgonzales/CoSEM/blob/main/logo.png)


### Overview
The Corpus of Singapore English Messages (CoSEM) is a corpus of online text messages collected between 2016 and 2022, compiled and managed by a group of scholars who share an interest in Colloquial Singapore English (CSE) research.
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

### License
The CoSEM follows the CC BY-NC-SA 4.0 License, meaning that you are free to:  

- Share — copy and redistribute the material in any medium or format; 
- Adapt — remix, transform, and build upon the material. 

The licensor cannot revoke these freedoms as long as you follow the license terms. 

Under the following terms:

- Attribution — You must give appropriate credit , provide a link to the license, and indicate if changes were made . You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- Non-Commercial — You may not use the material for commercial purposes.
- ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

<br />
<br />

### Disclaimer
The public version of the CoSEM (see 'Corpus Version' below) has some limitations. For example, based on our initial assessment, the scrubber does its work for the most part. However, we note that it scrubs non-name information that might be important for analyses. For example, (a) below becomes (b). Furthermore, we observed that it only scrubs information from the [`scrubadub`](https://scrubadub.readthedocs.io/en/stable/ "scrubadub") package. As such, we recommend that you exercise caution in using the public version of the corpus. We put forward our intention of contributing to the scholarly community by showing whatever we can at this time. We thank you for your patience.

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

Ensuring the privacy for messaging data is paramount, and as such, we try our best to adopt a strict standard in dealing with sensitive data in the message itself. We utilize the [`scrubadub`](https://scrubadub.readthedocs.io/en/stable/ "scrubadub") package in Python as well as a customized RegEx script to remove sensitive data as much as we can. For example, any detected email address will be replaced by the code {{EMAIL}}. This process gives at least some protection against publishing sensitive data. While we remove such conﬁdential information, it is generally impossible to remove all sensitive data with any custom RegEx-based script or computation-based, especially one trained with machine learning methods like scrubadub. We did this to lower the anxiety of contributors and protect their privacy.

We thank Tao Chen and Min-Yen Kan for the disclaimer template.

<br />


#### Corpus metadata or tag format
Every line of utterance has been tagged with an identifier tag. The tag format allows for easy identification of a line of utterance within the corpus, and for easy interpretation of relevant metadata. For example, the tag < 17CF15-40341-20CHF-2016 > shows that the utterance was collected in the year 2017 by a Chinese female with identification number 15; the utterance is line 40341 in the corpus; and the line was produced by a 20-year-old Chinese Singaporean female in 2016.

<br />
<br />

#### Corpus Version
The current public version stands at 10.9 million tokens (as of September 17, 2023). It is anonymized using the [`scrubadub`](https://scrubadub.readthedocs.io/en/stable/ "scrubadub") package as well as customized `RegEx` scripts. As with any type of automated scrubbing, there is a chance that some utterances are not properly scrubbed, in which case, we ask the corpus users to exercise tact in using the data, anonymizing unscrubbed private information if they intend to present examples that contain them. 

<br />

The corpus can be accessed [here](https://github.com/wdwgonzales/CoSEM/blob/main/Corpus/COSEM_v4_publicrelease_SEP172023.zip). You need to click on 'Download' from the upper right menu or "View raw" in the center. The file is in `zip` format. It needs to be decompressed/unzipped before use.

<br />



##### Plans for future versions

- more targetted scrubs
- reduction of mis-scrubbed tokens
- increased size

<br />
<br />

### Team
- [Assoc. Prof. Mie HIRAMOTO](https://profile.nus.edu.sg/fass/ellmh/ "Assoc. Prof. Mie HIRAMOTO") (National University of Singapore, Singapore) - Principal Investigator
- [Prof. Jakob LEIMGRUBER](https://jakobleimgruber.ch/en/home "Prof. Jakob LEIMGRUBER") (University of Regensburg, Germany)
- [Asst. Prof. Wilkinson Daniel Wong GONZALES](https://www.wdwgonzales.com "Asst. Prof. Wilkinson Daniel Wong GONZALES") (The Chinese University of Hong Kong, Hong Kong SAR, People's Republic of China) - Database Manager, Data Analyst
- [Jun Jie LIM](https://limjunjie.com "Jun Jie LIM") (University of California, San Diego, USA)
- Mohamed Hafiz Bin MOHAMED JURAIMI (National University of Singapore, Singapore)
- [Asst. Prof. Nick HUANG](https://discovery.nus.edu.sg/16346-nick-huang) (National University of Singapore, Singapore)

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

Gonzales, Wilkinson Daniel Wong.; Mie Hiramoto.; Jakob R.E. Leimgruber.; and Jun Jie Lim. 2023. The Corpus of Singapore English Messages (CoSEM). World Englishes 42.371–388. doi:10.1111/weng.12534.

<br />
<br />

```
@article{gonzales_corpus_2023,
	title = {The {Corpus} of {Singapore} {English} {Messages} ({CoSEM})},
	volume = {42},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	issn = {0883-2919, 1467-971X},
	url = {https://onlinelibrary.wiley.com/doi/10.1111/weng.12534},
	doi = {10.1111/weng.12534},
	language = {en},
	number = {2},
	urldate = {2022-02-19},
	journal = {World Englishes},
	author = {Gonzales, Wilkinson Daniel Wong and Hiramoto, Mie and Leimgruber, Jakob R.E. and Lim, Jun Jie},
	year = {2023},
	pages = {371--388},
}
```

<br />
<br />


### Related papers
We would highly appreciate it if you can cite these papers ([available here](https://github.com/wdwgonzales/CoSEM/tree/main/Related%20papers)) alongside the overview paper, if you decide to use or mention our corpus:

1. Gonzales, Wilkinson Daniel Wong, Mie Hiramoto, Jakob Leimgruber, Jun Jie Lim. 2022. Is it in Colloquial Singapore English: What variation can tell us about its conventions and development. _English Today_, Cambridge University Press. https://www.doi.org/10.1017/S0266078422000141

2. Leimgruber, Jakob, Jun Jie Lim,  Wilkinson Daniel Wong Gonzales, Mie Hiramoto. 2020. Ethnic and gender variation in the use of Colloquial Singapore English discourse particles, _English Language and Linguistics_, Cambridge University Press.
https://doi.org/10.1017/S1360674320000453

3. Hiramoto, Mie,  Wilkinson Daniel Wong Gonzales, Jakob Leimgruber, Jessica Choo, Junjie Lim. 2022. From Malay to Colloquial Singapore English: A case study of sentence-final particle sia. In A. Ngefac, H. Wolf & T. Hoffmann (eds.) _World Englishes and creole languages today: Existing paradigms and current trends in action_, 117-130. Lincom. https://lincom-shop.eu/LSEL-24-World-Englishes-and-Creole-Languages-Today/en

4. Hafiz, Mohamed, Hiramoto, Mie, Leimgruber, Jakob R. E., Gonzales, Wilkinson Daniel Wong & Lim, Jun Jie. 2024. Sociolinguistic variation in Colloquial Singapore English sia. World Englishes, weng.12700, https://doi.org/10.1111/weng.12700

5. Lim, Jun Jie, Hafiz, Mohamed, Gonzales, Wilkinson Daniel Wong & Hiramoto, Mie. 2024. Adverbial confirm in colloquial Singapore English: insights from a text message corpus.

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


@article{hafiz_sociolinguistic_2024,
	title = {Sociolinguistic variation in {Colloquial} {Singapore} {English} \textit{sia}},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	issn = {0883-2919, 1467-971X},
	url = {https://onlinelibrary.wiley.com/doi/10.1111/weng.12700},
	doi = {10.1111/weng.12700},
	abstract = {Colloquial Singapore English (CSE), also known as ‘Singlish’, features a wide range of sentence-final particles (SFP) influenced by local languages such as Hokkien, Cantonese, Mandarin and Malay. This study focuses on the SFP SIA, a relatively new and less-explored particle with Malay roots. We examine SIA and its variants (sia, sial, siak and siol) using data from the Corpus of Singapore English Messages, a 6.9-million-word text-message corpus from 2016 to 2022.},
	language = {en},
	urldate = {2024-07-22},
	journal = {World Englishes},
	author = {Hafiz, Mohamed and Hiramoto, Mie and Leimgruber, Jakob R. E. and Gonzales, Wilkinson Daniel Wong and Lim, Jun Jie},
	month = jul,
	year = {2024},
	pages = {weng.12700},
	file = {Hafiz et al. - 2024 - Sociolinguistic variation in Colloquial Singapore .pdf:/Users/wdwg/Zotero/storage/SC5INIFV/Hafiz et al. - 2024 - Sociolinguistic variation in Colloquial Singapore .pdf:application/pdf},
}

@article{lim_adverbial_nodate,
	title = {Adverbial confirm in colloquial {Singapore} {English}: insights from a text message corpus},
	copyright = {All rights reserved},
	abstract = {Despite its innovative, salient, and robust usage in Colloquial Singapore English (CSE), the adverbial use of confirm has largely gone unnoticed. In this paper, we provide morphosyntactic and semantic evidence to show that adverbial confirm behaves like a strongly subjective speaker-oriented adverb (SpOA). We argue that adverbial confirm developed as a result of contact with the Mandarin adverbial kending, likely due to English–Mandarin bilin­ gualism amongst Chinese Singaporeans, although its use has pro­ liferated throughout the general CSE-speaking population. Quantitatively, adverbial confirm emerges as the most frequently used SpOA when compared to surface-semantically equivalent strongly subjective SpOAs, such as definitely, sure, for sure and surely. The results suggest an increase in preference by CSE speak­ ers to use confirm to express strong speaker certainty.},
	language = {en},
	author = {Lim, Jun Jie and Hafiz, Mohamed and Gonzales, Wilkinson Daniel Wong and Hiramoto, Mie},
	file = {Lim et al. - Adverbial confirm in colloquial Singapore English.pdf:/Users/wdwg/Zotero/storage/EI9PL8LP/Lim et al. - Adverbial confirm in colloquial Singapore English.pdf:application/pdf},
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

- Latané BULLOCK
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
