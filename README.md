# Striking a new chord: Music Recommendation using Amazon Stack
This project repository is final deliverables the Big Data Analytics course (Spring 2022) offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.

## Executive Summary

Music recommendations are part of a Music streaming personalization strategy wherein songs are dynamically populated to a user on a webpage, app, or email based on data such as customer attributes, browsing behavior, or situational context—providing a personalized listening experience. This is done by leveraging machine learning algorithms. Music companies are collecting this data via different products such as “Daily Streaming”, “Playlists”, “Liked Songs” etc. 

Big data plays an important role in enabling these recommendations for real-time playlists and advertising on these platforms. Such a model will cater to Music streaming companies and online songs recommendation platforms. Further, the project particulars are curated for data scientist, platform engineers and data engineers can at such firms looking to upgrade or understand migration to AWS.

## Data Resource
[The Data](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r&guce_referrer=aHR0cHM6Ly9naXRodWIuY29tL2Nhc2VyZWMvRGF0YXNldHMtZm9yLVJlY29tbWVuZGVyLVN5c3RlbXM&guce_referrer_sig=AQAAAAkyH74jyiIv4JxPjvejltL1_Sk-yDNtNAbIpHn2YfUnG1v-2mxj_XOD-qtpvdqg-aoNtTk9pzWVkYzz3ZbvN5C2_RrjVAowWPR7lmx-GidaMerX8qOzosJayRViVuW2IEoTjMAeZ8xJlIoK38-6GQAJOwZjFsSv0AyQNj4oagqX&guccounter=2) we used is over 10M+ ratings of musical artists which were given by the Yahoo! Music users, include three columns:
1. user_id
2. artist_id
3. rating_score

## Recommendation Engine Building Video
### Overview of the project
https://www.youtube.com/watch?v=vgsROeIWHX0
### Recommendation engine demo
https://www.youtube.com/watch?v=-XfFkIkRHYE


## Business Use Case
The USP (unique selling point) of this project is that it allows small scale companies to quickly build a recommendation engine which can help them boost revenue. It's a MVP (Minimal Viable product) and offcourse needs curation for a specific company. That's where the Plugins will help us improve it.

## Technology Stack
AWS S3, QuickSight, AWS DMS/Kinesis, EMR, Apache Spark

## Resources
The following online resources provide valuable reference in the implementation of this project:
1. [10 Open-Source Datasets One Must Know To Build Recommender Systems](https://analyticsindiamag.com/10-open-source-datasets-one-must-know-to-build-recommender-systems/) 
2. [PySpark Collaborative Filtering with ALS](https://towardsdatascience.com/build-recommendation-system-with-pyspark-using-alternating-least-squares-als-matrix-factorisation-ebe1ad2e7679)
3. [Build Amazon SageMaker notebooks backed by Spark in Amazon EMR](https://aws.amazon.com/blogs/machine-learning/build-amazon-sagemaker-notebooks-backed-by-spark-in-amazon-emr/)

