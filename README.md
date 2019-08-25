# Introduction to unsupervised machine learning with Amazon Web Services (AWS Sagemaker)

In this interesting 3hr workshop, you will take the massive dataset of UFO sightings (80,000 reports over the past century) from National UFO Reporting Center (NUFORC) and use Amazon's machine learning services (Sagemaker) to identify the top 10 locations that are most likely to have UFO sightings. To do so, you will need to use an unsupervised machine learning algorithm.

You will then take your trained model, deserialise it, convert its output to a csv format and visualise it on a map using AWS Quicksights to see where these locations are. Then you can try correlating these locations with landmarks.

## Questions you will answer in this workshop

- What areas of the world are most likely to have UFO sightings?
- Do clusters of UFO sightings correlate with landmarks, such as airports or research centers?

This repository contains instructions for setting up your AWS account to get you started with Amazon Sagemaker, S3 and Quicksight. Workshop assignments for are included in the `exercises` folder.

## Learning Objectives

- Learn the difference between Artificial Intelligence, Machine Learning and Deep learning
- Learn how K-means Clustering Algorithm works
- See unsupervised machine learning LIVE In the CLOUD!
- Learn the process of loading and preparing data for training
- Experiment with AWS Sagemaker, S3 and Quicksight

## What will I learn during this workshop

- Creating and configuring IAM roles and permissions in AWS
- Creating and configuring buckets in AWS
- Creating and configuring Jupyter notebooks in AWS
- Reading and Writing to your buckets via Jupyter Notebook
- Cleaning and Wrangling data with Pandas and Numpy packages
- Training models in the cloud using unsupervised machine learning and saving it
- Deserialising a trained model's output
- Setting up AWS Quicksight datasources
- Visualising the results of your model's output on a map using AWS QuickSight
- Most importantly, you will learn how to use AWS sagemaker to cluster your data using unsupervised machine learning algorithms

## Prequisites

While you won't need prior experience in practical machine learning or with the AWS to follow along with this class, we'll assume some familiarity with:

- Python programming language: See [Udacity - Intro to Python](https://eu.udacity.com/course/introduction-to-python--ud1110)
- Getting Started with AWS: See [AWS Getting Started Resource Center](https://aws.amazon.com/getting-started)
- **pandas** and **numpy** python packages

## Steps

This workshop consists of three activities:

1. Setting up AWS accounts and S3 buckets
2. Processing the dataset with AWS Sagemaker
3. Visualising the model outputs with AWS Quicksight on a map

> Note: If you get stuck, take a look at the solutions notebook. It is recommended that you solve your problem as far as you can via googling. Only refer to the solutions notebook if you are frustrated.

## Flow

1. Clone this git reposiroty using `git clone https://github.com/beginners-machine-learning-london/intro_to_unsupervised_ml_with_AWS_Sagemaker`
2. Set a budget for your AWS account
3. Setup up your AWS user accounts and permissions
4. Create an S3 bucket and uploading the UFO dataset onto your bucket
5. Create an AWS Sagemaker EC2 instance
6. Upload the Jupyter notebook file on AWS EC2 instance
7. Complete the Jupyter notebook assignments on AWS and save the model outputs in your S3 bucket
8. Create an AWS Quicksight account
9. Configure AWS Quicksight to visualise your model output on a map

## Featured technologies

- [Python](https://www.python.org/): Python is a programming language that lets you work more quickly and integrate your systems more effectively.
- [AWS](https://aws.amazon.com): Amazon Web Services is a subsidiary of Amazon that provides on-demand cloud computing platforms to individuals, companies, and governments, on a metered pay-as-you-go basis.

## About NUFORC

**The National UFO Reporting Center (NUFORC)** is an organization in the United States that investigates UFO sightings and/or alien contacts.

## Dataset Source

The dataset for this workshop can be obtained via Kaggle. However, a static copy is also provided in the `exercises/datasets` folder. You can download the ufo sightings dataset from [Kaggle](https://www.kaggle.com/NUFORC/ufo-sightings)

## Learn More

- **A Cloud Guru - AWS Certified Machine Learning - Speciality 2019**: Enjoyed this workshop? The content was inspired from A Cloud Guru's [AWS Certified Machine Learning - Specialty 2019](https://acloud.guru/learn/aws-certified-machine-learning-specialty).
- **Towards Data Science**: [How Does k-Means Clustering in Machine Learning Work?](https://towardsdatascience.com/how-does-k-means-clustering-in-machine-learning-work-fdaaaf5acfa0)
- **Towards Data Science**: [Clustering using K-means algorithm](https://towardsdatascience.com/clustering-using-k-means-algorithm-81da00f156f6)
- **The Amazon SageMaker K-means algorithm Documentation**: [K-Means Algorithm](https://sagemaker.readthedocs.io/en/stable/kmeans.html)
- **AWS Guide to Using Amazon SageMaker Built-in Algorithms**: [K-Means Algorithm](https://docs.aws.amazon.com/sagemaker/latest/dg/k-means.html)

## Collaboration, Questions and Discussions

- [**BML Slack Channel**](http://tiny.cc/bmlslack) - Join our slack workspace to collaborate with others, discuss ideas and post any questions you have about our group or the workshops
- Have questions about workshop exercises or setting up your AWS account and configurations? Post them [**here**](https://app.slack.com/client/TLQ81UB7A/CLHTZDGGZ)

## Workshop Feedback

- How was this workshop? Please provide us with some feedback [**here**](http://tiny.cc/BMLfeedback) so that we can improve the content and delivery of future workshops.
