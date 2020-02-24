# [NYC OPEN DATA 311 DATABASE ANALYSIS](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)

NYC_OpenDataAnalysis: The Initial Data Cleaning and Analysis 

## To run a ML Model I had divided this cleaned data based on different boroughs

ManhattanAnalysis(5) , ManhattanNew_Analysis, Manhattan_Modelling: Manhattan Data Modelling (Please check this Analysis as it has detailed more and this was developed first )

Brooklyn Analysis: Brooklyn Data Modelling 

Queens Analysis: Queens Borough Modelling 

Bronx Analysis: Bronx Borough Modelling

StatenIsland Analysis: StatenIsland Modelling



Predictor : Type of Complaint

Type of Machine Learning: Multi-Class Classification , Multi-Class Text Classification


Machine Learning Models Used: RANDOM FOREST CLASSIFIER , Linear SVC

Languagues and Tools Used: Python (Dask, Pandas, Numpy, matplotlib, seaborn), Power BI

Model Evaluation: Precision and Recall Values for each complaint tells us more about True Positive values out of all labels taht are labelled Positive

**Most of Complaint Types I got Higher Precision and Recall values along with good accuacy that makes a good model  ***


Note: One can access JSON API through dask to load the data in the jupyter notebook using dd.read_json(filepath)

I tried configuring and accessing jupyter in my GCP Cloud through a dataproc cluster . However being a free user I am unable to configure more that 8 GB of Compute Engine in GCP..


https://console.cloud.google.com/dataproc/clusters?project=ezoicassessment&folder&organizationId
