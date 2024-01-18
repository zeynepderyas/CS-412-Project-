# CS412 - Project - Zeynep Derya Selçuk 29391 - Doğa Koltan 29025

## Overview
With this project we tried to predict student's homework grades by using their ChatGPT conversation histories. We merged student's homework scores with conversation stories to create a machine learning model.

## Repository Structure
-**data/:** Involves the datasets used in the project which are HTML files and CVS file.
-**scripts/:** Python scripts for data preprocessing,modeling, and feature engineering.
-**code/:** Trained machine learning models.
-**docs/:** Additional documentation and reports.

## Installation and Setup
We used Google Colab Drive mounting in order to increase contribution and to be able to make changes simultaneously. However if you want to use different tools you need to install necessary libraries.

## Data Description
Our data is provided by our professor, it contains some HTML files and CVS file. HTML files contain students ChatGPT conversations, the CVS file shows scores of each student. The actual defined questions of assigned homework is given as a list inside the code.

## Methodology
-**Data Preparation and Preprocessing:**
Parsing HTML files
Cleaning data
Handling with missing data

-**Feature Engineering:**
Tokenization
Prompt Analysis
Keyword Analysis
Sentiment Analysis

-**Vectorization and Similarity Measurement:**
Cosine similarity
Vectorization

-**Model Evaluation:**
Train and test splits
Mean Squared Error 


