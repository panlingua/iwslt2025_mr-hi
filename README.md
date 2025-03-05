# [Dialectal and low-resource speech translation: Marathi to Hindi@IWSLT2023](https://iwslt.org/2025/low-resource)(https://iwslt.org/2025/low-resource)

# Introduction
Marathi is an Indo-Aryan language which has the ISO code mr, and is dominantly spoken in India’s Maharashtra state. It is one of the 22 scheduled languages of India and the official language of Maharashtra and Goa. As per the 2011 Census of India, it has around 83 million speakers which covers 6.86% of the country’s total population. Marathi speakers rank third amongst the languages that are spoken in India.

IWSLT participants may obtain the [Marathi-Hindi speech translation data](https://github.com/panlingua/iwslt2025_mr-hi). This corpus consists of 22 hours of audio speech data from the news domain and translations into Hindi text.


## Structure of the ` Shared Task data`:
```
iwslt2025_mr-hi/
├─ data/
   ├─ iwslt2023-2024_mr-hi/
│	└─ train/
│  	└─ dev/
│  	└─ test-2023/
│  	└─ test-2024 (only audio files for the IWSLT 2024 evaluation campaign)/
│  ├─ test (only audio files for the IWSLT 2025 evaluation campaign)/
│     └─ stamped.tsv
│     └─ wav/
├─ LICENSE.md
├─ README.md
   
```
**The data statistics are presented below:
-----------------------------------------------------
```
│ Language	             		| Total_audios ( Total_Hours) | Total_translated_Sentences/   │
│                            		│                             │    Total_translated_Segements │ 
│ Marathi-Hindi (train)      		│      7990            	     │          7990                  │
│ Marathi-Hindi (dev)        		│      2103                   │          2103                 │
│ Marathi-Hindi (test 2023 & 2024)       │      2455                   │         2455                  │
│ Marathi-Hindi (test)  		│      -                   │         -                   │
```
* Participants can get the additional Marathi audio data (with transcription) from here: [Common Voice](https://commonvoice.mozilla.org/en/datasets), [OpenSLR](https://www.openslr.org/64/), and [Indian Language Corpora](https://www.cse.iitb.ac.in/~pjyothi/indiccorpora/).

# License
Please see the [LICENSE](https://github.com/panlingua/iwslt2025_mr-hi/blob/main/LICENSE.md) file.

# Acknowledgments
We would like to thank [Panlingua Language Processing LLP](http://panlingua.co.in/) for providing Marathi-Hindi speech translation data. We would also like to thank [Science Foundation Ireland (SFI)](https://www.sfi.ie/) [(grant number SFI/12/RC/2289_ P2 Insight _ 2)](https://www.insight-centre.org/) 

## References
<pre>
   @inproceedings{ahmad-etal-2024-findings,
    title = "{FINDINGS} {OF} {THE} {IWSLT} 2024 {EVALUATION} {CAMPAIGN}",
    author = {Ahmad, Ibrahim Said  and
      Anastasopoulos, Antonios  and
      Bojar, Ond{\v{r}}ej  and
      Borg, Claudia  and
      Carpuat, Marine  and
      Cattoni, Roldano  and
      Cettolo, Mauro  and
      Chen, William  and
      Dong, Qianqian  and
      Federico, Marcello  and
      Haddow, Barry  and
      Javorsk{\'y}, D{\'a}vid  and
      Krubi{\'n}ski, Mateusz  and
      Kim Lam, Tsz  and
      Ma, Xutai  and
      Mathur, Prashant  and
      Matusov, Evgeny  and
      Maurya, Chandresh  and
      McCrae, John  and
      Murray, Kenton  and
      Nakamura, Satoshi  and
      Negri, Matteo  and
      Niehues, Jan  and
      Niu, Xing  and
      Ojha, Atul Kr.  and
      Ortega, John  and
      Papi, Sara  and
      Pol{\'a}k, Peter  and
      Posp{\'\i}{\v{s}}il, Adam  and
      Pecina, Pavel  and
      Salesky, Elizabeth  and
      Sethiya, Nivedita  and
      Sarkar, Balaram  and
      Shi, Jiatong  and
      Sikasote, Claytone  and
      Sperber, Matthias  and
      St{\"u}ker, Sebastian  and
      Sudoh, Katsuhito  and
      Thompson, Brian  and
      Waibel, Alex  and
      Watanabe, Shinji  and
      Wilken, Patrick  and
      Zem{\'a}nek, Petr  and
      Zevallos, Rodolfo},
    editor = "Salesky, Elizabeth  and
      Federico, Marcello  and
      Carpuat, Marine",
    booktitle = "Proceedings of the 21st International Conference on Spoken Language Translation (IWSLT 2024)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand (in-person and online)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.iwslt-1.1",
    pages = "1--59",
    abstract = "This paper reports on the shared tasks organized by the 21st IWSLT Conference. The shared tasks address 7 scientific challenges in spoken language translation: simultaneous and offline translation, automatic subtitling and dubbing, speech-to-speech translation, dialect and low-resource speech translation, and Indic languages. The shared tasks attracted 17 teams whose submissions are documented in 27 system papers. The growing interest towards spoken language translation is also witnessed by the constantly increasing number of shared task organizers and contributors to the overview paper, almost evenly distributed across industry and academia.",
}
</pre>
<pre>
@inproceedings{agrawal-etal-2023-findings,
    title = "{FINDINGS} {OF} {THE} {IWSLT} 2023 {EVALUATION} {CAMPAIGN}",
    author = {Agarwal, Milind  and
      Agrawal, Sweta  and
      Anastasopoulos, Antonios  and
      Bentivogli, Luisa  and
      Bojar, Ond{\v{r}}ej  and
      Borg, Claudia  and
      Carpuat, Marine  and
      Cattoni, Roldano  and
      Cettolo, Mauro  and
      Chen, Mingda  and
      Chen, William  and
      Choukri, Khalid  and
      Chronopoulou, Alexandra  and
      Currey, Anna  and
      Declerck, Thierry  and
      Dong, Qianqian  and
      Duh, Kevin  and
      Est{\`e}ve, Yannick  and
      Federico, Marcello  and
      Gahbiche, Souhir  and
      Haddow, Barry  and
      Hsu, Benjamin  and
      Mon Htut, Phu  and
      Inaguma, Hirofumi  and
      Javorsk{\'y}, D{\'a}vid  and
      Judge, John  and
      Kano, Yasumasa  and
      Ko, Tom  and
      Kumar, Rishu  and
      Li, Pengwei  and
      Ma, Xutai  and
      Mathur, Prashant  and
      Matusov, Evgeny  and
      McNamee, Paul  and
      P. McCrae, John  and
      Murray, Kenton  and
      Nadejde, Maria  and
      Nakamura, Satoshi  and
      Negri, Matteo  and
      Nguyen, Ha  and
      Niehues, Jan  and
      Niu, Xing  and
      Kr. Ojha, Atul  and
      E. Ortega, John  and
      Pal, Proyag  and
      Pino, Juan  and
      van der Plas, Lonneke  and
      Pol{\'a}k, Peter  and
      Rippeth, Elijah  and
      Salesky, Elizabeth  and
      Shi, Jiatong  and
      Sperber, Matthias  and
      St{\"u}ker, Sebastian  and
      Sudoh, Katsuhito  and
      Tang, Yun  and
      Thompson, Brian  and
      Tran, Kevin  and
      Turchi, Marco  and
      Waibel, Alex  and
      Wang, Mingxuan  and
      Watanabe, Shinji  and
      Zevallos, Rodolfo},
    editor = "Salesky, Elizabeth  and
      Federico, Marcello  and
      Carpuat, Marine",
    booktitle = "Proceedings of the 20th International Conference on Spoken Language Translation (IWSLT 2023)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada (in-person and online)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.iwslt-1.1",
    doi = "10.18653/v1/2023.iwslt-1.1",
    pages = "1--61",
    abstract = "This paper reports on the shared tasks organized by the 20th IWSLT Conference. The shared tasks address 9 scientific challenges in spoken language translation: simultaneous and offline translation, automatic subtitling and dubbing, speech-to-speech translation, multilingual, dialect and low-resource speech translation, and formality control. The shared tasks attracted a total of 38 submissions by 31 teams. The growing interest towards spoken language translation is also witnessed by the constantly increasing number of shared task organizers and contributors to the overview paper, almost evenly distributed across industry and academia.",
}
</pre>
<pre>
=== Machine-readable metadata (DO NOT REMOVE!) =====================================================
Data available since: Marathi-Hindi Speech Translation Shared Task@IWSLT-2025
License: CC BY-NC-SA 4.0
=======
Includes text/audio: yes
Shared Task Organisers: Ojha, Atul Kr.; McCrae, John P.
Contact: atulkumar.ojha@insight-centre.org or shashwatup9k@gmail.com, info@panlingua.co.in
Contributor/&copy;holder: Panlingua Languague Processing LLP, India and Insight Centre for Data Analytics, Data Science Institue, University of Galway, Ireland
=======================================================================================================
</pre>
