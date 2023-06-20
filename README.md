# MLOps-Assignment
An MLOps Assignment to create an end-to-end MLOps pipeline for customer churn case study

## Table of Contents
* [General Info](#general-information)
* [Project Contents](#project-contents)
* [Conclusion](#conclusion)
* [Software and Library Versions](#software-and-library-versions)
* [Acknowledgements](#acknowledgements)

### General Information
Code pro is an edtech startup that had a phenomenal seed A funding round. They used this funding to gain significant market share by campaigning aggressively. Due to aggressive campaigns the amount of junk leads increased.

A lead is generated when any person visits Code pro’s website and enters their contact details on the platform. A junk lead is when the person sharing his contact details has no interest in the product/service.

Having junk leads in the pipeline creates a lot of inefficiency in the sales process. Thus the goal of the Data Science team is to build a system that categorizes leads on their propensity to purchase Code pros course. This system will help remove the inefficiency caused by junk leads in the sales process.

#### Data Set Brief Information
Inorder to classify any lead we will require 2 types of information about the lead. The 2 types are

1.Source of origin of the lead: In order to better predict the propensity of the lead to purchase the course, we need some information on the source of origin of the lead. The column from ‘city_mapped’ to ‘reffered_leads’ contain the information about the source of origin of the lead

2.Interaction of the lead with the website/platform: In order to better predict the propensity of the lead to purchase the course, we need some information on what was the interaction of the lead with the platform. The column from ‘1_on_1_industry_mentorship’ to ‘whatsapp_chat_click’ store the information about the interaction the lead had with the platform.

#### Business Objective
Create and execute MLOps pipeline architecture to resolve customer chur case study.

#### Business Solution
Create Airflow DAGS and use MLFlow UI to automate and monitor data engineering, model training and model inference for given case study.


### Project Contents
* **Lead_scoring_data_pipeline** - Folder containing required files for Airflow DAGS - Lead_Scoring_Data_Engineering_Pipeline
* **Lead_scoring_training_pipeline** - Folder containing required files for Airflow DAGS - Lead_scoring_training_pipeline
* **Lead_scoring_inference_pipeline** - Folder containing required files for Airflow DAGS - Lead_scoring_inference_pipeline
* **unit_test** - Folder containing required files for unit testing of data pipeline
* **notebooks** - Folder containing required files for lead_scoring_model_experimentation
* **dummy_notebooks** - Folder containing dummy notebooks to test th
* **Screenshot.pdf** - PDF file containing screenshots of Airflow and MLFlow UI's
* **.gitattributes** - Attribute file to track *.db sqlite files for **git LFS**
* **README.md** - Readme file


### Conclusion
Created Airflow DAGS and used MLFlow UI to automate and monitor data engineering, model training and model inference for given case study.

#### Recommendation

##### LightGBM Model with AUC score - 0.82

###### Top 10 predictor variables
'total_leads_droppped', 'city_tier', 'referred_lead_0.0', 'first_platform_c_Level0', 'first_platform_c_Level1', 'first_platform_c_Level2', 'first_platform_c_Level3', 'first_platform_c_Level7', 'first_platform_c_Level8', 'first_platform_c_others'


### Software and Library Versions
* ![Jupyter Notebook](https://img.shields.io/static/v1?label=Jupyter%20Notebook&message=4.9.2&color=blue&labelColor=grey)

* ![NumPy](https://img.shields.io/static/v1?label=numpy&message=1.21.5&color=blue&labelColor=grey)

* ![Pandas](https://img.shields.io/static/v1?label=pandas&message=1.4.2&color=blue&labelColor=grey)

* ![matplotlib](https://img.shields.io/static/v1?label=matplotlib&message=3.5.1&color=blue&labelColor=grey)

* ![optuna](https://img.shields.io/static/v1?label=optuna&message=2.10.1&color=blue&labelColor=grey)

* ![shap](https://img.shields.io/static/v1?label=shap&message=0.41.0&color=blue&labelColor=grey)

* ![pycaret](https://img.shields.io/static/v1?label=pycaret&message=3.0.2&color=blue&labelColor=grey)

* ![mlflow](https://img.shields.io/static/v1?label=mlflow&message=2.4.1&color=blue&labelColor=grey)

* ![sqlite3](https://img.shields.io/static/v1?label=sqlite3&message=2.6.0&color=blue&labelColor=grey)

* ![sklearn](https://img.shields.io/static/v1?label=sklearn&message=1.0.2&color=blue&labelColor=grey)


### Acknowledgements
This case study is an assignment, done as part of [Upgrad](https://www.upgrad.com/ ) - **Master of Science in Machine Learning & Artificial Intelligence** programme.


### Contact
Created by [Sanjeev Surendran](https://github.com/Sanjeev-Surendran)


<!-- ## License -->
<!-- This project is not a open source and sharing the project files is prohibited. -->
