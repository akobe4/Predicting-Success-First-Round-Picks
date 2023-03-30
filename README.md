# Predicting-Success-First-Round-Picks

This repository contains the final assignment for the Data Science program at Lighthouse Labs 


Folders:

Data
- includes csv. files of the data pulled from the NHL API 
- data pulled from EliteProspects not included in the repo 

Final
- includes text file with AWS link and data prepared for testing 
- a video of the deployment in Postman

Notebooks 
- Bedard: pulls Bedard's information to be able to run through the model 
- delpoyment_info: has the json info to run the model, and runs the post request in the notebook 
- EDA: data cleaning and exploratory data analysis 
- Elite_Prospects_data: pulls the data from Elite Prospects API 
- final_model_pipeline: includes the pipeline for the model 
- NHL_data: pulls the data from the NHL.com API
- translation_factors: code for calculating NHLe and GVT 

Pickle Files
- pickle file for the model columns 
- model15: accuracy score of 0.66, 3 features (R, European Skater, Jan birth month)
- model17: accuracy score of 0.66, 4 features (R, European Skater, Jan birth month, oGVT)
- model18: accuracy score of 0.66, 5 features (R, European Skater, Jan birth month, oGVT, Feb birth month)
- model20: accuracy score of 0.68, 6 features (R, European Skater, Jan birth month, oGVT, Feb birth month, F)
- model21: accuracy score of 0.68, 5 features (R, European Skater, Jan birth month, oGVT, Feb birth month) ** model that was actually used 
