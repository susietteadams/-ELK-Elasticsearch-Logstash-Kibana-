ELK-Elasticsearch-Logstash-Kibana
Launching  ELK (Elasticsearch, Logstash, Kibana) configurations

Introduction

The data that was used in our analysis is from the 311 Service Requests database. Which was collected from 2010 to present and consist of over 20.2 Million rows with 41 columns. Our goal is to provide The City of  New York  with valuable insights from their huge data set for 311 service requests. My team and I did the analysis using the ELK this the acronym for three open source projects Elasticsearch, Logstash, and Kibana. Elasticsearch is a search and analytics engine. Logstash is a server side data processing pipeline that ingests data from multiple sources simultaneously, transforms it and then sends it to a "stash" like Elasticsearch. Kibana lets users visualize data with charts and graphs in Elasticsearch.

A pie chart showing the top 5 cities each city has an outer layer that shows top 5 descriptors.

![image](https://user-images.githubusercontent.com/43391446/68557191-19a6db80-0403-11ea-91d0-15a72fd46d67.png)

A tag cloud representing the top 20 call descriptors. 

![image](https://user-images.githubusercontent.com/43391446/68557162-00059400-0403-11ea-80a7-f0639d82137e.png)

A coordinated map of all the major call descriptors in each city.

![image](https://user-images.githubusercontent.com/43391446/68557131-e49a8900-0402-11ea-80c6-ebe26ceb7af2.png)
