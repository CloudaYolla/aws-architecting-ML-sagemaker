![ML Logo](images/mod00_logo.png "Logo") 

# Architecting Machine Learning on AWS
Architecting Machine Learning on AWS: A Practitioner’s Guide to Production-Grade ML on AWS Cloud with SageMaker. 
Welcome to the art and science of machine learning! During this 2-day accelerator course you will quickly learn about the theory and application of machine learning for business applications, with a strong focus on building these solutions on the AWS cloud and Amazon SageMaker.

`(Revision History:
PA2, 2021-11-01, @akirmak: Q4 Dry-run updates
`
*Welcome to the Architecting Machine Learning on AWS using SageMaker workshop.*


## Overview

The objective of this workshop is to provide a practitioner's guide to challenges of real-world ML problems, and demonstrate examples of how to tackle them on AWS Cloud. 

There is abundance of online training (online training in Coursera, Data Camp, O'Reilly Online, A Cloud Guru, Udemy), books & articles (medium, blog posts) and code (For AWS SageMaker only, there are hundreds of Sample Notebooks from every imaginable use case, ML domain). So how is this workshop different? We aim to bring together theory & practice for an architectural perspective.

This acceleartor is designed for data scientists who are new to AWS, and architects and developers who are new to machine learning. You will spend two days performing data science tasks: training models, evaluating them, analyzing data, etc. After this two day period you will be better suited to continue building data science solutions on AWS, designing architectural requirements for these, or supporting teams who currently do this.

We will cover:

- Statistical machine learning
- Feature engineering
- Deploying a model into production
- Model evaluation and comparison
- AWS basics for machine learning: S3, EC2, IAM
- SageMaker deep dive: SageMaker Studio, Notebooks, Experiments, Training jobs, Endpoints etc

### Target Audience
This course is designed for Python developers primarily. But since it is group-based, you will still have a great time even if you don't wrangle Python for your day job. We recommend reviewing Python programming using the statistical package Pandas. We also recommend having a Cloud Practiioner AWS Certification, but it is not required. 

- https://pythonprogramming.net/data-analysis-python-pandas-tutorial-introduction/
- https://aws.amazon.com/certification/certified-cloud-practitioner/


### Agenda

**Day One:**

- Learn about ML on AWS
- Go through a sample lab
- Break into teams and focus on a new machine learning project
- First Goal: Download your dataset to an S3 bucket, create a SageMaker Studio domain, and load your data into a Pandas dataframe.
- Second Goal: Use AutoPilot do AutoML for you.

**Day Two:**

- Learn about feature engineering on AWS
- Finish your first set of engineered features
- Train your first model
- Learn about model evaluation on AWS
- [Optional] Tune your model model using SageMaker automatic model tuning
- Learn about putting your model into production on SageMaker Deliverable
- Demo your notebook to your colleagues!

## Requirements

What you'll need

- Your own laptop
- Github account to share code with your project partners
- Kaggle account to download data sets
- We will provide you an AWS account for this course. However, if you would like to bring your own dataset and use the time to build your own project, you're welcome to do that! We ask that you use your own AWS account in that case.

## Areas covered: 

- **Data Preparation:** You will explore various examples of  Data Exploration, Feature Engineering & Data Cleaning using popular frameworks on python using a Jupyter Notebook.  
    
- **ML Training**: You will train a supervised learning algorithm for classification. 

- **Evaluating ML Models:** The key to evaluating performance of an ML model is to be able to generate various metrics (depending on the type of algorithm), and to be able to persist measurements in the ML Project Life Cycle. You will see how model metrics, and metrics related to the compute cluster are persisted in Amazon S3 and AWS CloudWatch.  

- **Optimizing ML Models**: ML Optimization is a stochastic process. You will experiment with Automated Hyperparameter Tuning using Bayesian Search strategy to find the best performing hyperparameters. 

- **Framing the ML Problem:**  Infrastructure Requirements & Business Context


## Preparing for the Labs
#### AWS Provided Temporary Accounts 

As described here, login to your AWS Console and to SageMaker Studio  https://sagemaker-immersionday.workshop.aws/en/prerequisites/option1.html 
       
#### Bring Your Own Account
As described here, login to SageMaker Studio: https://sagemaker-immersionday.workshop.aws/en/prerequisites/option2.html


#### Download Lab Guides & SageMaker Sample Notebooks (in SageMaker)

    - Open SageMaker Terminal
    - Clone SageMaker examples `git clone https://github.com/CloudaYolla/aws-architecting-ML-sagemaker.git`


### 10. Cleaning up resources 

**Very Important:** SageMaker Studio Notebook Kernels run on EC2, and therefore you will be billed by the second unless you save your work (by downloading to your local computer) & terminate the SageMaker Studio instance. 


 Thank you.
