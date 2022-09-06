## **Data guide**

* **emoji_codes_csv**: Emoji table with their corresponding hex and unicode codes for each emoji

* **accuracy_data**: Folder of folders containing all accuracy test result .txt files, divided by language, emoji and hashtag treatment and train/test split. Also contains .csv file with all average results and standard deviations, Accuracy_data_complete

* **corpus**: All raw data files obtained from previous studies that form the project's corpus:
   - **all_files_white_sup**: Text files containing tweet text from [Hate Speech Dataset from a White Supremacy Forum](https://aclanthology.org/W18-5102.pdf), tweet classification found in ```annotations_metadata_white_sup```
   
   - **discarded_data**: Data files from discarded datasets, not used in the project:
     - **abusive_text_data**: Full data WITH tweet text, processed data (english data) - [Large Scale Crowdsourcing and Characterization of Twitter Abusive Behavior](https://arxiv.org/pdf/1802.00393.pdf)
     
     - **en_Hasoc2021_train**: Full data (english data) - [Hate Speech and Offensive Content Identification in English and Indo-Aryan Languages: HASOC 2021](https://hasocfire.github.io/hasoc/2021/index.html)
     
     - **english_dataset**: Train set (english data) - [Hate Speech and Offensive Content Identification in English and Indo-Aryan Languages: HASOC 2019](https://hasocfire.github.io/hasoc/2019/index.html)
     
     - **hasoc2019_en_test-2919**: Test set (english data) - [Hate Speech and Offensive Content Identification in English and Indo-Aryan Languages: HASOC 2019](https://hasocfire.github.io/hasoc/2019/index.html)
     
     - **hasoc_2020_en_test**: Test set (english data) - [Hate Speech and Offensive Content Identification in English and Indo-Aryan Languages: HASOC 2020](https://hasocfire.github.io/hasoc/2020/index.html)
     
     - **hasoc_2020_en_train**: Train set (english data) - [Hate Speech and Offensive Content Identification in English and Indo-Aryan Languages: HASOC 2020](https://hasocfire.github.io/hasoc/2020/index.html)
     
     - **hatespeech_id_label_founta**: Full data WITHOUT tweet text, raw data (english data) - [Large Scale Crowdsourcing and Characterization of Twitter Abusive Behavior](https://arxiv.org/pdf/1802.00393.pdf)
     
    - **2019-05-28_portuguese_hate_speech_hierarchical_classification**: Full data (portuguese data) - [A Hierarchically-Labeled Portuguese Hate Speech Dataset](https://aclanthology.org/W19-3510.pdf)
    
    - **AMI2020_test_raw_gold_anon**: Test set (italian data) - [AMI: Automatic Misogyny Identification-2020](https://s3.cbk.cloud.syseleven.net/elg-public/f0fb46717d154339a9929d707bb27f52_u2235_paper161.pdf)
    
    - **AMI2020_training_raw_anon**: Train set (italian data) - [AMI: Automatic Misogyny Identification-2020](https://s3.cbk.cloud.syseleven.net/elg-public/f0fb46717d154339a9929d707bb27f52_u2235_paper161.pdf)
    
    - **EXIST2021_test_labeled**: Test set for english and spanish data - [sEXism Identification in Social neTworks: EXIST](http://journal.sepln.org/sepln/ojs/ojs/index.php/pln/article/viewFile/6389/3809)
    
    - **EXIST2021_training**: Train set for english and spanish data - [sEXism Identification in Social neTworks: EXIST](http://journal.sepln.org/sepln/ojs/ojs/index.php/pln/article/viewFile/6389/3809)
    
    - **IHSC_ids**: Full data (italian data) - [An Italian Twitter Corpus of Hate Speech against Immigrants: IHSC](https://aclanthology.org/L18-1443.pdf)
    
    - **NAACL_SRW_2016**: Full data (english data) - [Hateful Symbols or Hateful People?](https://aclanthology.org/N16-2013.pdf)
    
    - **NLP+CSS_2016**: Full data (english data) - [Are You a Racist or Am I Seeing Things?](https://aclanthology.org/W16-5618.pdf)
    
    - **ToLD-BR**: Full data (portuguese data) - [Toxic Language Detection in Social Media for Brazilian Portuguese: ToLD-BR](https://arxiv.org/pdf/2010.04543.pdf)
    
    - **annotations_metadata_white_sup**:  Full data (english data) - [Hate Speech Dataset from a White Supremacy Forum](https://aclanthology.org/W18-5102.pdf)
    
    - **csv_result-OffComBR3**: Full data (portuguese data) - [Offensive Comments in the Brazilian Web: OffComBR](http://www.each.usp.br/digiampietri/BraSNAM/2017/p04.pdf)
    
    - **ghc_test**: Test set (english data) - [The Gab Hate Corpus](https://osf.io/edua3/)
    
    - **ghc_train**: Train set (english data) - [The Gab Hate Corpus](https://osf.io/edua3/)
    
    - **haspeede2_dev_taskAB**: Train set (italian data) - [Hate Speech Detection: HaSpeeDe 2](http://ceur-ws.org/Vol-2765/paper162.pdf)
    
    - **hateval2019_en_dev**: Validation set for english data - [Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter: HatEval](https://aclanthology.org/S19-2007.pdf)
    
    - **hateval2019_en_test**: Test set for english data - [Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter: HatEval](https://aclanthology.org/S19-2007.pdf)
    
    - **hateval2019_en_train**: Train set for english data - [Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter: HatEval](https://aclanthology.org/S19-2007.pdf)
    
    - **hateval2019_es_dev**: Validation set for spanish data - [Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter: HatEval](https://aclanthology.org/S19-2007.pdf)
    
    - **hateval2019_es_test**: Test set for spanish data - [Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter: HatEval](https://aclanthology.org/S19-2007.pdf)
    
    - **hateval2019_es_train**: Train set for spanish data - [Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter: HatEval](https://aclanthology.org/S19-2007.pdf)
    
    - **labeled_data_dav_en**: Full data (english data) - [Automated Hate Speech Detection and the Problem of Offensive Language](https://ojs.aaai.org/index.php/ICWSM/article/view/14955/14805)

* **obtained_tweets_data**: Adapted datasets containing extracted tweet text where original sets only contained a tweet ID (except for ```whitesup_data```, which originally contained a .txt name)

* **preprocessed_data**: All completely and uncompletely processed data - files used finally for model training are called either ```removed_[LANGUAGE]_data``` or ```mantained_[LANGUAGE]_data```

* **reclassified_data**: Datasets where some manual labelling has taken place

* **stopwords**: Stopwords used for model training of each language (English, Spanish, Italian, Portuguese)
