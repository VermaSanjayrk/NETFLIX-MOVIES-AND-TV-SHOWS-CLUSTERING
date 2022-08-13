# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
![image](https://user-images.githubusercontent.com/91052155/184505894-15913c54-8a42-4be7-927c-10e8772dd8bf.png)

## Introduction

Netflix’s recommendation system gives the idea to them about the popularity of their services provides as it help to increase the sold the subscriptions as more as possible,which offers a varieties of items for selections, this help to get them a user satisfaction,and their loyalty to platform and get them a better understanding of what the user wants.

Then it’s easier to get the user to make better decisions from a wide variety of movie products.

With over 139 million paid subscribers(total viewer pool -300 million) across 190 countries, 15,400 titles across its regional libraries and 112 Emmy Award Nominations in 2018 — Netflix is the leading Internet television network and the most-valued largest streaming service in the world. The success behind the amazing story of Netflix is incomplete without the mention of its recommender systems that focus on personalization according to users. According to your preferences,there are several methods to create a list of recommendations.You can use  (Collaborative-filtering) and (Content-based Filtering) for recommendation.

## Problem Statement
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flexible which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

In this project, we are evaluating as below-
1.	Exploratory Data Analysis
2.	Understanding what type content is available in different countries
3.	Is Netflix increasingly focused on TV rather than movies in recent years?
4.	Clustering similar content by matching text-based features

## Objective
The project's main goal is to create a model that can perform Clustering on comparable material by matching text-based attributes.
## Dataset Peeping
The dataset has 7787 rows and 12 attributes to work with. 
1.	We have NaN values in the  dataset.
2.	Changed the format of the Date.
3.	Added some columns which are extracted from the Date column.
## Approach
As per the problem statement, understanding what type of content is available in different countries and Is Netflix increasingly focused on TV rather than movies in recent years we have to do clustering on similar content by matching text-based features. For that we used Agglomerative Clustering, and K-means Clustering.
## Feature Engineering
●	There are too much classes, so we just obtain the first 50 (the most common 50)
●	Unify some of the similar types(genre)
●	Make a dictionary with similar content by matching text-based features that we are going to use in clustering. 
### Correlation Heatmap
![image](https://user-images.githubusercontent.com/91052155/184506111-945bf8a5-b0ac-4731-92af-5f50a584df31.png)

### Hypothesis Evaluation
![image](https://user-images.githubusercontent.com/91052155/184506129-f01bbfa6-7fe2-4680-8608-8f29d1f3313d.png)![image](https://user-images.githubusercontent.com/91052155/184506134-389c4618-516c-4876-8ce9-49a0dde41e95.png)
Hypothesis from the data visualized-
1. According to the first graph, the number of TV shows launched in the previous few years is growing.
2. According to the second graph, the number of TV shows added to Netflix is stable.

