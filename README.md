# Sparkify-Apache-Cassandra Data Modeling Project by Eddie Wamutu





## Introduction
A startup called Sparkify wanted to analyze the data they had been collecting on songs and user activity on their new music streaming app. The analysis team is  interested in understanding what songs app users are listening to. Right now, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions. His role is to create a database for this analysis and to test his database by running queries given to him by the analytics team from Sparkify to create the results.

## Project Description
I have applied what I've learned on data modeling with Apache Cassandra and have completed an ETL pipeline using Python. To finish this project, I had to model my data by creating  Apache Cassandra tables to run queries. I had been provided with part of the ETL pipeline that transfers data from a dataset of CSV files within a directory to create a smaller CSV file to model and insert data into Apache Cassandra tables.

I was given a project template that took care of  the imports and also provided a structure for ETL pipeline  to process the data.

## Datasets
I worked with one dataset, "event_data". This directory of csv files is partitioned by date. Below are examples of filepaths of two files in the dataset:

- event_data/2018-11-08-events.csv

- event_data/2018-11-09-events.csv

## ETL Pipeline


Running ***Project_1B_Project_template.ipynb*** first processes the csv file. Then,it  includes Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables. The tables are tested by running SELECT statements.

