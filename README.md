# Song Recommendation System with Surprise
## General info
<br>This recommender uses user-based collaborative filtering.
<br>The [data](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r&did=2) (R2 - Yahoo! Music User Ratings of Songs with Artist, Album, and Genre Meta Information, v. 1.0) has been obtained from [Yahoo! Webscope](http://webscope.sandbox.yahoo.com) and consists of real data collected from Yahoo! Music services.
<br>[The New Data and New Challenges in Multimedia Research” by Bart Thomee, David A. Shamma, Gerald Friedland, Benjamin Elizalde, Karl Ni, Douglas Poland, Damian Borth, and Li-Jia Li, arXiv:1503.01817](https://www.researchgate.net/profile/David-Shamma/publication/273327809_The_New_Data_and_New_Challenges_in_Multimedia_Research/links/5741fc1508aea45ee84a35f7/The-New-Data-and-New-Challenges-in-Multimedia-Research.pdf)

<br>__In this project used are:__
<br> For model building:


*train data*
<br>Sample
|**ind**|**user\_id**|**song\_id**|**rating**|
|:-----:|:----------:|:----------:|:--------:|
|0|0|166|5|
|1|0|2245|4|
|2|0|3637|4|


*test data*
<br>Sample
**ind**|**user\_id**|**song\_id**|**rating**
:-----:|:-----:|:-----:|:-----:
0|0|7171|5
1|0|8637|4
2|0|21966|4


<br> Metadata:

*genres*
<br>Sample
|**genre\_id**|**parent\_genre\_id**|**level**|**genre\_name**
:-----:|:-----:|:-----:|:-----:
0|0|1|Unknown
1|1|1|Electronic/Dance
2|1|2|Ambient
3|2|3|Ambient Dub

*songs*
<br>Sample
|**song\_id**|**album\_id**|**artist\_id**|**genre\_id**
:-----:|:-----:|:-----:|:-----:
0|12070|8490|0
1|19512|7975|134
2|18953|3492|0


***
## Project includes
<br>1. Data preprocessing
<br>2. Model training (SVD and kNN Baseline) and parameter tuning
<br>3. Model performance visualization
<br>4. Song recommender
<br>5. Exploration on similiar users (SVD) and neighbours (kNN)
<br>6. Music genres graph
