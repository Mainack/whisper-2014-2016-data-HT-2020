## Data collected from Whisper, an anonymous social media site
[Take me to "How can I get this data" section](#how-can-i-get-this-data)

1. This repository contains information to access data from *Mainack Mondal, Denzil Correa and Fabricio Benevenuto. 2020. "Anonymity Effects: A Large-Scale Dataset from an Anonymous Social Media Platform." HT'20.* Read the paper [here](http://cse.iitkgp.ac.in/~mainack/publications/whisper-data-ht-2020.pdf).

1. This dataset contained **89,877,121 anonymously written posts** uploaded in the social media site Whisper from June 2014 to June 2016. We further anonymized the data to protect user privacy as mentioned in our [paper](http://cse.iitkgp.ac.in/~mainack/publications/whisper-data-ht-2020.pdf)

1. *If you have any questions about this data feel free to contact Dr. Mainack Mondal (email id in the paper pdf).*

1. **Please cite our paper in any published work that uses this data.**

~~~
@inproceedings{mondal2020,
 author = {Mainack Mondal and Denzil Correa and Fabricio Benevenuto},
 title = {Anonymity Effects: A Large-Scale Dataset from an Anonymous Social Media Platform},
 booktitle = {Proceedings of the 31st ACM Conference on Hypertext and Social Media},
 series = {HT '20},
 year = {2020},
 publisher = {ACM}
}
~~~

## Warning

1. This dataset contain swear words and hateful language that users posted while expressing hate.


## How can I get this data? 

* **The full Whisper dataset (divided into multiple files for ease of downloading) is available upon request for academic research purposes. Please follow the instructions provided in [agreement-whisperdata.txt](https://raw.githubusercontent.com/Mainack/whisper-2014-2016-data-HT-2020/master/agreement-whisperdata.txt).**


## Description of the Whisper data 

1. Whisper is an anonymous social media site. A post on Whisper is called "whisper". 

1. Our Whisper dataset contains a total of 89,877,121 whispers uploaded by anonymous users from June 2014 to June 2016. Each whisper is represented as a json object.

1. Each whisper objects contain the following fields

| Field name | Description | Data Type |
| ---- | ----- | ---|
| **text** | User generated text of the whisper | string|
| **categories** | List of categories assigned to this whisper by the users and/or Whisper’s internal algorithm | list|
| **places** | List of specific locations included the whisper object. Each location contains "placetype" and "name". "placetype" can be either country (e.g., US) or region (e.g., US states) | list |
| **me2** | Number of favorites for the whisper | integer |
| **nickname** | Non-persistent anonymous username | string | 
| **ts** | Unix timestamp in microseconds stating the up-load time of the whisper | integer |
| **serial** | An incremental serial assigned to each post by us.  | integer | 
| **feeds** | List of additional labels for the whisper text. Very few whispers contain this | list |

**Note:** We removed PII from this dataset using a regex-based approach. We used regular expressions to identify potential PII like phone numbers, emails, ip addresses, bitcoin addresses, street addresses, zip codes, po boxes and ssn numbers in the whisper texts. Then we replaced all of those detected strings with easily-detectable placeholders like “[[POS- SIBLE_BTC_ADDRESSES]]” in the whisper texts. 

## Other publications based on this data 

* Part of this data is used in four of our other published works.
~~~
Characterizing Usage of Explicit Hate Expressions in Social Media 
Mainack Mondal, Leandro Araujo Silva, Denzil Correa and Fabricio Benevenuto.
New Review of Hypermedia and Multimedia (THAM), vol. 24, no. 2, pp. 110-130, June 2018.
~~~
Read the THAM paper [here](https://homepages.dcc.ufmg.br/~fabricio/download/tham_mondal2018.pdf)

~~~
A Measurement Study of Hate Speech in Social Media
Mainack Mondal, Leandro Araújo Silva, Fabrício Benevenuto.
In Proceedings of the 25th ACM Conference on Hypertext and Social Media (HT'17), Prague, Czech Republic, July 2017.
~~~
Read the HypterText 2017 paper [here](https://homepages.dcc.ufmg.br/~fabricio/download/HT2017-hatespeech.pdf)

Get the hatespeech data for HypterText 2017 paper from [here](https://github.com/Mainack/hatespeech-data-HT-2017)

~~~
Analyzing the Targets of Hate in Online Social Media.
Leandro Araújo Silva, Mainack Modal, Denzil Correa, Fabricio Benevenuto, and Ingmar Weber.
In Proceedings of The 10th International AAAI Conference on Weblogs and Social Media (ICWSM'16). Cologne, Germany. May 2016. 
~~~
Read the ICWSM 2016 paper [here](https://homepages.dcc.ufmg.br/~fabricio/download/icwsm2016-hate.pdf)

~~~
The Many Shades of Anonymity: Characterizing Anonymous Social Media Content
Denzil Correa, Leandro Araújo Silva, Mainack Mondal, Fabrício Benevenuto and Krishna P. Gummadi.
In Proceedings of The 9th International AAAI Conference on Weblogs and Social Media (ICWSM'15), Oxford, UK, May 2015.
~~~
Read the ICWSM 2015 paper [here](https://homepages.dcc.ufmg.br/~fabricio/download/anonymity_shades.pdf)



###### Release date: 30th June, 2020
###### Authors: Mainack Mondal, Denzil Correa and Fabricio Benevenuto
