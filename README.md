**This repository contains the code for a corpus-based analyses of English vowels produced by L1-Japanese speakers.**

The paper reporting this analysis is:

Schweinberger, Martin, & Komiya, Yuki. (2022). A corpus-based computational analysis of high-front and -back vowel production of L1-Japanese learners of English and L1-English speakers. In Rosey Billington (Ed.), *Proceedings of the Eighteenth Australasian International Conference on Speech Science and Technology* (pp. 196-200). Australasian Speech Science and Technology Association.

**Abstract**  
This study combines acoustic phonetics with computational and applied corpus linguistics to analyse and compare the production of the monophthongal vowels /I/, /i:/, /U/, and /u:/ in the speech of 150 L1-Japanese learners (JPN) and 132 L1-speakers of English (ENS) based on *The International Corpus Network of Asian Learners of English* (ICNALE). The study aims to ascertain if JPN merge spectrally close vowels by calculating Bhattacharya coefficients. In addition, the study uses mixed-effects linear regression to determine if JPN compensate the potential mergers by exaggerating durational contrasts between spectrally similar vowels. The results of the analysis confirm that JPN exhibit high degrees of overlap for both /I i:/ and /U u:/. Their L1-English peers, however, also exhibit substantive overlap for /U u:/. With respect to duration, the analysis shows that JPN extend the duration of all vowels and exaggerate  the difference between /I i:/ and /U u:/ to compensate for the lack of qualitative differences between short and long vowel pairs. This study represents the first corpus-based acoustic analysis of JPN vowels in spontaneous speech.   

**Data**  
The study uses data from the [*International Corpus Network of Asian Learners of English* (ICNALE) (Ishikawa 2014)](http://language.sakura.ne.jp/icnale/download.html). The ICNALE is one of the largest publicly available learner corpora comprising more than 10,000 topic-controlled speeches and essays produced by college students in ten countries and regions in Asia as well as English native speakers. For this study, all data representing spoken monologues (spontaneous speech) from 150 JPN and 132 ENS were analyzed. 

The audio and text files of Japanese and the English spoken component of the ICNALE data were downloaded and force-aligned using [WebMAUS ](https://clarin.phonetik.uni-muenchen.de/BASWebServices/interface/WebMAUSBasic). All files were forced aligned twice:  
* once with the target variety being US American English 
* once with the target variety being US British English

This resulted in all files having three variants with each having once British and once American English being the target variety:  
* a txt file
* a mp3 file
* a TextGrid file

The file had the same names but differed in their extension. 

**Folder structure**  
The folder structure for this project requires that the directory has the following format  
* project folder (contains all files relevant for the study)  
  * data (contains all data relevent for the study)  
    * JPN (contains all txt, mp3, and TextGrid files of the L1-Japanese English learners)
    * ENS (contains all txt, mp3, and TextGrid files of the L1-English speakers)  
  * the Rproj file  
  * the Rmd files (the R notebooks)

**References**  
Ishikawa, S. (2014). Design of the ICNALE Spoken: A new database for multi-modal contrastive interlanguage analysis, *Learner Corpus Studies in Asia and the World* 2: 63-76.

