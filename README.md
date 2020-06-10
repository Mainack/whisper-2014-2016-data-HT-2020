## DATA COLLECTED FROM WHISPER

1. This repository contains information to access data from *Mainack Mondal, Denzil Correa and Fabricio Benevenuto. 2020. "Anonymity Effects: A Large-Scale Dataset from an Anonymous Social Media Platform." HT'20.* Read the paper [here](http://cse.iitkgp.ac.in/~mainack/publications/whisper-data-ht-2020.pdf).

1. This dataset contained **89,877,121 anonymously written Whisper posts** uploaded from June 2014 to June 2016. We further anonymized the data to protect user privacy as mentioned in our [paper](http://cse.iitkgp.ac.in/~mainack/publications/whisper-data-ht-2020.pdf)

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

## WARNING

1. This dataset contain swear words and hateful language that users posted while expressing hate.


## HOW CAN I GET THIS DATA?

* **The full Whisper dataset is available upon request for academic research purposes. Please follow the instructions provided in [agreement-whisperobject.txt](https://raw.githubusercontent.com/Mainack/whisper-2014-2016-data-HT-2020/master/agreement-whisperobject.txt).**


## DESCRIPTION OF WHISPER DATA

1. Whisper is an anonymous social media site.

1. Our Whisper dataset contains a total of 89,877,121 posts uploaded by anonymous users from June 2014 to June 2016. Each whisper is expressed as a standalone json object.

1. Our whisper objects contain the following fields

| Field name | Description | Data Type |
| ---- | ----- | ---|
| **text** | Text of the whisper | string|
| **categories** | List of categories assigned to this whisper by the users and/or Whisper’s internal algorithm | list|
| **places** | List of specific locations included the whisper object. Each location contains "placetype" and "name". "placetype" can be either country (e.g., US) or region (e.g., US states) | list |
| **me2** | Number of favorites for the whisper | integer |
| **nickname** | Non-persistent anonymous username | string | 
| **ts** | Unix timestamp in microseconds stating the up- load time of the whisper | integer |
| **serial** | An incremental serial assigned to each post by us.  | integer | 
| **feeds** | List of additional labels for the whisper text. Very few whispers contain this | list |

## Other publications based on this data 

* Part of this data is used in two other of our published work.
~~~
Characterizing Usage of Explicit Hate Expressions in Social Media 
Mainack Mondal, Leandro Araujo Silva, Denzil Correa and Fabricio Benevenuto.
New Review of Hypermedia and Multimedia (THAM), vol. 24, no. 2, pp. 110-130, June 2018.
~~~
Read the THAM paper [here](https://homepages.dcc.ufmg.br/~fabricio/download/tham_mondal2018.pdf)

~~~
Analyzing the Targets of Hate in Online Social Media.
Leandro Silva, Mainack Modal, Denzil Correa, Fabricio Benevenuto, and Ingmar Weber.
In Proceedings of the Int'l AAAI Conference on Weblogs and Social (ICWSM’16). Cologne, Germany. May 2016. 
~~~
Read the ICWSM paper [here](https://homepages.dcc.ufmg.br/~fabricio/download/icwsm2016-hate.pdf)


###### Release date: 10th June, 2020
###### Authors: Mainack Mondal, Denzil Correa and Fabricio Benevenuto
