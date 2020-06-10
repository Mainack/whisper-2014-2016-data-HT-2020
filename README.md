## ANONYMIZED DATA COLLECTED FROM WHISPER

1. This repository contains data from *Mainack Mondal, Denzil Correa and Fabricio Benevenuto. 2020. "Anonymity Effects: A Large-Scale Dataset from an Anonymous Social Media Platform." HT'20.* You can read the paper [here](http://cse.iitkgp.ac.in/~mainack/publications/whisper-data-ht-2020.pdf)

1. *If you have any questions about this data feel free to contact Dr. Mainack Mondal (email id in the paper pdf).*

1. This is data of anonymous posts collected from social media site Whisper on 2014 - 2015. 
1. The dataset contains total 20,705 hate posts from Twitter and 7,604 hate posts from  Whisper.

1. **Please cite our paper in any published work that uses any of these resources.**

~~~
@inproceedings{mondal2017,
 author = {Mainack Mondal and Leandro A. A. Silva and Fabricio Benevenuto},
 title = {A Measurement Study of Hate Speech in Social Media},
 booktitle = {Proceedings of the 28th ACM Conference on Hypertext and Social Media},
 series = {HT '17},
 year = {2017},
 location = {Prague, Czech Republic},
 publisher = {ACM}
}
~~~

## WARNING

1. This dataset contain swear words and hateful language that users posted while expressing hate.
1. The dataset is stored as one whisper json object per line 


## ACCESSING THE DATA

* **Full whispers objects for academic research purposes are available upon request. please follow the instructions provided in [agreement-whisperobject.txt](https://raw.githubusercontent.com/Mainack/whisper-2014-2016-data-HT-2020/master/agreement-whisperobject.txt).**


## DESCRIPTION OF WHISPER DATA

1. Whisper is an anonymous social media site.

1. Our Whisper dataset contains a total of 89,877,121 posts uploaded from June 2014 to June 2016. Each whisper is expressed as a standalone json object.

1. Our whisper objects contain the following fields

| Field name | Description | Data Type |
| --- | ----- | ---|
| **text** | Text of the whisper | string|
| **categories** | List of categories assigned to this whisper by the users and/or Whisper’s internal algorithm | list|
| **places** | List of specific locations included the whisper object. Each location contains "placetype" and "name". "placetype" can be either country (e.g., US) or region (e.g., US states) | list |
| **me2** | Number of favorites for the whisper | integer |
| **nickname** | Non-persistent anonymous username | string | 
| **ts** | Unix timestamp in microseconds stating the up- load time of the whisper | integer |
| **serial** | An incremental serial assigned to each post by us.  | integer | 
| **feeds** | List of additional labels for the whisper text. Very few whispers contain this | list |



###### Release date: 10th June, 2020
###### Authors: Mainack Mondal, Denzil Correa and Fabricio Benevenuto
