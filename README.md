## Project Overview
This project involves working with the modified NASA Airfoil Self Noise dataset using ML with Apache Spark. 

## Scenerio:

The data science team needs to leverage various algorithms and work with datasets in multiple formats. While they excel in Machine Learning, they rely on Data Engineers to handle ETL processes and build efficient ML pipelines.
As a Data Engineer at an aeronautics consulting company specializing in the design of airfoils for planes and sports cars, 
my responsibilities include:
##### 1. Data Cleaning:
   Removing duplicate rows to ensure data integrity.
  
   Eliminating rows with null values for consistent and reliable analysis.
##### 2. Machine Learning Pipeline Development:
  Creating a robust ML pipeline to develop a predictive model that estimates SoundLevel based on other features in the dataset.
##### 3. Model Evaluation:
  Assessing the model’s performance using appropriate metrics to ensure its accuracy and effectiveness.
##### 4. Model Persistence:
  Saving the trained model for future use, ensuring it is readily available for deployment and further analysis.

## Objectives
The objective is to clean the dataset, develop a Machine Learning pipeline, evaluate the model’s performance, and persist it for future applications.

Here are breakdown of the 4 parts:

#### Part 1: Perform ETL Activity

 ##### Load CSV Dataset: 
Import the modified NASA Airfoil Self Noise dataset.

 
 ##### Remove Duplicates: 
   Identify and drop any duplicate rows to ensure data integrity.
   
 
 ##### Drop Rows with Null Values: 
   Clean the data by removing any rows that contain null values.
   
 
 ##### Make Transformations: 
 Apply necessary transformations for data consistency and readiness for analysis.
 
 
 ##### Store in Parquet Format: 
 Save the cleaned dataset in Parquet format for efficient storage and retrieval.
 
#### Part 2: Create a Machine Learning Pipeline
##### Develop ML Pipeline: 
  Build a machine learning pipeline that predicts SoundLevel based on other features in the dataset.
  
#### Part 3: Evaluate the Model
##### Performance Metrics: 
  Evaluate the model using relevant metrics (e.g., RMSE, R-squared) to assess its accuracy and effectiveness.
  
#### Part 4: Persist the Model
##### Model Persistence: 
  Save the trained model for future production use, ensuring it can be reused in real-world applications.
  
##### Load and Verify: 
  Load the stored model and verify its successful retrieval and functionality.
  

### Dataset Information
##### Source: 
The original dataset can be found in the NASA Airfoil Self Noise dataset. https://archive.ics.uci.edu/dataset/291/airfoil+self+noise

In this project We use the modified dataset below and not the original dataset mentioned above.

https://github.com/abdalla92/Machine-Learning-with-Apache-Spark/edit/main/NASA_airfoil_noise_raw.csv

##### License: 
This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.


## Outcome
A comprehensive ML pipeline that enhances the efficiency of data scientists in experimenting with various algorithms and data formats.
