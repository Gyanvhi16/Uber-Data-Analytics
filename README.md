# Uber Data Analytics | Data Engineering GCP Project

 End-to-end Data Pipeline & Analytics on Uber Trips using GCP, Mage, BigQuery & Looker Studio.


## Overview

This project aims to analyze Uber datasets by leveraging a combination of cloud-based tools and advanced analytics technologies. The workflow incorporates data storage and management using **GCP Storage**, data processing and transformation with **Python** and **Mage Data Pipeline Tool**, and scalable computing via **Compute Engine**. The processed data is then analyzed and queried using **BigQuery**, with visualizations and insights presented through **Looker Studio**.
The objective is to derive meaningful insights, optimize workflows, and demonstrate the integration of various tools for end-to-end data analytics.


 ## Architecture 

The goal of this project is to build a modern data pipeline for analyzing Uber trip records. The pipeline involves:
✅ Extracting & loading data from NYC’s open taxi dataset
✅ Processing & transforming using Mage (ELT tool)
✅ Storing & querying using BigQuery
✅ Visualizing using Looker Studio


## Technology Stack
🔹### Programming Language : Python

🔹### Google Cloud Platform (GCP) Services
1. ### Google Cloud Storage (GCS)
2. ### Compute Engine
3. ### BigQuery
4. ### Looker Studio
🔹 ### Data Pipeline Tool : 
Mage.ai

## Dataset Used
We use NYC TLC Trip Record Data, which contains Uber ride details, including:
1. Pick-up & drop-off locations (Latitude/Longitude)
2. Trip timestamps
3. Trip distance
4. Fares, payment types
5. Passenger counts


#### 1. Dataset in this project : [Click Here](https://github.com/Gyanvhi16/Uber-Data-Analytics/tree/main/dataset)
#### 2. NYC TLC Data Website : [Click Here](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
#### 3. Data Dictionary : [Click Here](https://github.com/Gyanvhi16/Uber-Data-Analytics/blob/main/Data%20Dictionary.png) 

## Data Model 

<img src="Data Model.png">


 ## Looker Studio Dashboard
Used Looker Studio to create an interactive dashboard displaying:
📌 Total Trips by Date
📌 Revenue Breakdown by Payment Type
📌 Most Popular Pickup & Drop-off Locations
📌 Average Trip Duration & Distance
