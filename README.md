# Data Modeling with Cassandra

## Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. However, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.


The objective of this project is to create an Apache Cassandra database which can create queries on song play data to answer the questions

## Data
User activity data (event data) is provided

![data_modelling_with_Cassandra_data](https://user-images.githubusercontent.com/6285945/75710129-f376b580-5ce9-11ea-857c-5b0e86f458b4.PNG)


## Methodology
* process the event_datafile_new.csv dataset to create a denormalized dataset
* model the data tables keeping in mind the queries you need to run
