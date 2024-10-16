# OpenHack – DevOps for Data Science

**Product ID**: 22992
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: OHDTSC
**Vendor Code**: MS
**Vendor Name**: Microsoft
**URL**: [Course Link](https://www.fastlaneus.com/course/microsoft-ohdtsc)

## Objective
This OpenHack enables attendees to employ fundamental up to advanced DevOps practices for the Data Science process, leveraging Azure Machine Learning Service, Azure DevOps, Azure Data Factory, and other relevant Azure services. 
This OpenHack simulates a real-world scenario where an insurance company needs to predict the probability that a driver will initiate an auto insurance claim in the next year and needs to be able to take the Data Scientist’s local functional model and associated data used to train the model to production in a high-quality, secure, scalable way.

During the “hacking”, attendees will focus on: 



- 1. Understanding DevOps fundamentals as applied to the Data Science process to train and deploy machine learning models
- 2. Begin to apply more advanced DevOps practices (such as canary rollout or taking automated actions based on instrumentation)
By the end of the OpenHack, attendees will have built out a technical solution that automatically trains, evaluates, registers, and deploys a model, connects fundamental DevOps practices for the Data Ops for ML used to train the model, as well as implements observability aspects for the system.

## Essentials
Knowledge Prerequisites  To be successful and get the most out of this OpenHack, familiarize yourself with the following: Data Science: 



- What is Machine Learning? (website)
- What is Azure Machine Learning? (website with video)
- Basic familiarity with Jupyter notebooks (website with tutorial)
DevOps: 



- What is DevOps? (website)
- Continuous Integration
- Continuous Delivery
- DevOps Practices
- Azure DevOps Overview (website)
- Comfortable with git basics or git hands on learning (only Main: Intro sequence, Ramping up, Remote: push & Pull sections)
- Understand Azure Pipelines basics or Create your first Azure Pipeline Do YAML, not classic (website + code sample)
- Azure DevOps Branch Policies (website)

Programming Languages: 



- • Participants should have familiarity with programming languages like Python.
 
Tooling Prerequisites To avoid any delays with downloading or installing tooling, you are encouraged to have the following ready to go! 



- Visual Studio Code
- Git
- Python3
- Docker (optional)
- Jupyter (optional)

## Audience
Experts with different skill sets and workflows across data engineering, data science, machine learning engineering, development, operations, and other knowledge areas are working together in a collaborative way emphasizing the skills and strengths of each team member. 



- Software Engineers
- Cloud Solution Architects
- Data Scientists
- ML Engineers

## Outline
Challenge 1: Local Model Build 



- Understand how the model build process works on a local machine/notebook for training and evaluation
Challenge 2: Portable execution 



- Refactor experimentation notebook to run as an experiment in ML service
- Add metrics/parameter logging
Challenge 3: Scripted ML Pipeline Creation 



- Extend notebook from challenge 2 to use Azure ML API to set up ML pipeline that trains and registers the model
- Retrieve the registered model, deploy it as an inferencing service to ACI, and test the deployed service
Challenge 4: Automated ML Pipeline Creation 



- DevOps pipeline integration incorporating MLOpsPython
- Train, evaluate, and register a model via Azure DevOps and Azure ML Service Pipelines
- Deploy and serve a model automatically after model is registered in model registry service
- Implement basic acceptance testing against API endpoint in the pipeline after model deployment
Challenge 5: Observability: ML Training 



- Introduce a change in the model which breaks the model during training in the pipeline.  Be able to understand why it broke utilizing centralized instrumented logging.
- Have a dashboard which reports on one of CPU/Memory/GPU utilization and fires an alert when below or above a set threshold.  This is to ensure there is optimal use of the hardware for cost and performance.
Challenge 6: Observability: ML Inference / Serving 



- Implement a custom metric in the model code which outputs the score, have a dashboard to see the results of this metric over time
- Have a dashboard which reports on one of CPU/Memory/GPU utilization and fires an alert when below or above a set threshold.  This is to ensure there is optimal use of the hardware for cost and performance.
Challenge 7: Data Ops for ML: Data Ingestion & Pre-processing 



- Understand the pros and cons of various Data Ingestion options available with Azure services.
- Implement a solution when new data drops (i.e. file to a blob store) it automatically triggers a data ingestion pipeline to run a Python notebook to process the data, dump the file to a different folder on the blob store and invokes model training pipeline.
Challenge 8: Data Ops for ML: CI/CD Pipelines as Code 



- Store the source code of the data ingestion solution in SCM repository.
- Implement branching policy for the data pipeline and the notebooks.
- Implement CI/CD pipelines deploying the data ingestion pipeline and the notebooks to the target environment. Have the solution parametrized so it can be deployed to multiple environments.
- Have CI/CD pipelines stored in SCM repository
Challenge 9: Advanced: Canary deployment 



- Setup a canary deployment pipeline of the model being served to production users
- Analyze results of score on dashboard for the canary versus production

## Summary
Please note attendees work together in teams of 5 as a minimum and the pricing advertised is per team of 5.

## Course Duration
3 days

## Last Changed
2024-01-24T21:23:49.000Z
