# YouTube Data Analysis - ETL - Data Engineering Project

## Overview

This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube video data based on the video categories and trending metrics.

## Project Goals
1. Data Ingestion — Developing a mechanism to seamlessly gather data from diverse sources
2. ETL System — Transforming raw data into the required format for analysis and storage
3. Data lake — Establishing a centralized repository to efficiently store data from multiple sources
4. Scalability — Ensuring our system dynamically scales to handle growing data volumes effectively
5. Cloud Integration: Leveraging AWS to process and manage vast datasets exceeding local computing capabilities
6. Reporting — Building a dashboard to get answers to the questions we asked earlier

## Services we will be using
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">

