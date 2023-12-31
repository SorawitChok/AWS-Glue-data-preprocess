# Spotify Music Recommendation AWS Glue Job

This repository contains an AWS Glue job developed in Python using PySpark for Spotify music recommendations. The Glue job is designed for use as Extract-Transform-Load (ETL), which is responsible for preprocessing the data.

## Prerequisites

Before running this AWS Glue job, ensure you have the following:

- An AWS account with the necessary permissions to run AWS Glue jobs.
- Required AWS Glue job resources and configurations set up in your AWS environment.
- Python libraries or dependencies required for the Glue job. You can specify the dependencies in the job script or provide a requirements file.

## Dataset
The dataset used in this project can be derived from [Culture-Aware Music Recommendation Dataset](https://zenodo.org/records/3477842) provided by Eva Zangerle.

This dataset encompasses the information of 55,190 users, 3,471,884 tracks, and more than 120 million listening events, along with Hofstede's cultural dimensions data of 47 countries and the World Happiness Report (WHR) of over 160 countries. It consists of 5 files, 4 being *.tsv and one in *.tar.gz format. The following is a list of those files:
- acoustic_features_lfm_id.tsv (265.0 MB)
- events.tar.gz (2.8 GB)
- hofstede.tsv (1.7 kB)
- users.tsv (1.9 MB)
- world_happiness_report_2018.tsv (439.8 kB)


## Job Visualization
Here are the visual ETL generated by AWS Glue for each job 
### WHR job
![WHR-job](https://github.com/SorawitChok/AWS-Glue-data-preprocess/assets/52538051/3f0c7283-924b-401b-959f-b1cf8be8fbbd)

### User job
![user-job](https://github.com/SorawitChok/AWS-Glue-data-preprocess/assets/52538051/51fa0e82-3755-4bd4-84fb-5044ca6bd64f)

### Hofstede job
![hofstede-job](https://github.com/SorawitChok/AWS-Glue-data-preprocess/assets/52538051/e0cfc062-a78a-4dce-82a8-5fbb608cfe28)

### Event-Acoustic job 
![event-acous-job](https://github.com/SorawitChok/AWS-Glue-data-preprocess/assets/52538051/5bcc1487-fe82-4205-9247-77c8de421c46)

### User-EventAcoustic job
![user-eventacous-job](https://github.com/SorawitChok/AWS-Glue-data-preprocess/assets/52538051/2e33cdc4-3686-4a43-a6ac-1b96d29892a2)

### Hofstede-WHR job
![hofstede-whr-job](https://github.com/SorawitChok/AWS-Glue-data-preprocess/assets/52538051/f2747dc2-afe3-4e2d-98c2-1741c00417dd)

### User-profiling job
![user-profile-job](https://github.com/SorawitChok/AWS-Glue-data-preprocess/assets/52538051/4ec526e5-6442-42a5-afa3-72b90bcfa512)


## Copyright
Copyright (c) 2023 Sorawit Chokphantavee and Sirawit Chokphantavee
