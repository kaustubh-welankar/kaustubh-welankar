---
layout: post
title:  "Analysing sentiments of tweets"
date:   2018-03-03 12:00:00 +0530
categories: jekyll update
---

I did this project as a demonstration of my skills for an internship that I applied to. This was the first time I've done such a task, and it was a great experience learning! 

The Data collected
----------------------------
I collected random tweets a week back and stored them into a MongoDB instance locally. From each tweet, I found out the named entities. I selected 5 named entities that were mentioned the most. I analyzed the tweet sentiment for those named entities and news articles related to those named entities. The results are interesting!

Results:
----------------------------
The most named entities were `Trump`, `BTSARMY`, `BestFanArmy`, `BTS`, `EXOL`.
Their corresponding sentiment analysis :
1. BestFanArmy (Appears in 344 tweets)
![BestFanArmy Analysis](/media/precogTaskOutput/BestFanArmy.png)
2. BTSARMY (229 Tweets)
![BTSARMY Analysis](/media/precogTaskOutput/BTS.png)
3. Trump (Appears in 133 tweets)
![Trump](/media/precogTaskOutput/TRUMP.png)
4. BTS (Appears 103 times)
![BTS](/media/precogTaskOutput/BTS.png)
5. EXOL (98 tweets)
![EXOL](/media/precogTaskOutput/EXOL.png)

