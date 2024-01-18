# CS412 - Machine Learning Project

## Overview
With this project we tried to predict student's homework grades by using their ChatGPT conversation histories. We merged student's homework scores with conversation stories to create a machine learning model. We hope you like it!

- **Team member names & id number:**
  - Zeynep Derya Selçuk 29391
  - Doğa Koltan 29025

## Repository Structure
- **data:** Involves the datasets used in the project which are HTML files and CVS file.
- **scripts:** Python scripts for data preprocessing,modeling, and feature engineering.
- **code:** Trained machine learning models.
- **docs:** Additional documentation and reports.

## Installation and Setup
We used Google Colab Drive mounting in order to increase contribution and to be able to make changes simultaneously. However if you want to use different tools you need to install necessary libraries.

## Data Description
Our data is provided by our professor, it contains some HTML files and CVS file. HTML files contain students ChatGPT conversations, the CVS file shows scores of each student. The actual defined questions of assigned homework is given as a list inside the code.

## Methodology
- **Data Preparation and Preprocessing:**
  - Parsing HTML files
  - Cleaning data
  - Handling with missing data

- **Feature Engineering:**
  - Tokenization
  - Prompt Analysis
  - Keyword Analysis
  - Sentiment Analysis

- **Vectorization and Similarity Measurement:**
  - Cosine similarity
  - Vectorization

- **Model Evaluation:**
  - Train and test splits
  - Mean Squared Error
 
## Results
There are outputs of some code cells below. It is not possible to put all the results because some cells have too many outputs due to the number of files.
More detailed results are available in the code we have uploaded on sucourse.

- We read and tokanized the file correctly
  
<img width="1276" alt="Ekran Resmi 2024-01-19 00 20 20" src="https://github.com/zeynepderyas/CS-412-Project-/assets/148149481/74046c31-2724-4387-a658-a07fe55bc9c3">

- Dealing with missing values
  
  <img width="371" alt="Ekran Resmi 2024-01-19 00 27 12" src="https://github.com/zeynepderyas/CS-412-Project-/assets/148149481/23303bda-c2ff-45ba-ad90-38ec29fe3d74">

- Vetorizing
  
  <img width="1192" alt="Ekran Resmi 2024-01-19 00 28 33" src="https://github.com/zeynepderyas/CS-412-Project-/assets/148149481/b91f5959-1641-4829-be92-8187e0620fe8">

- Beginning of mapping
   
  <img width="1093" alt="Ekran Resmi 2024-01-19 00 29 18" src="https://github.com/zeynepderyas/CS-412-Project-/assets/148149481/7cf7f092-338d-4837-9ee5-95f289bb2d78">

- Our histogram for grade distribution
  
  <img width="565" alt="Ekran Resmi 2024-01-19 00 31 09" src="https://github.com/zeynepderyas/CS-412-Project-/assets/148149481/cef1bf83-b705-4f21-a4ae-5f2f3b49c81d">

- Merging scores with features
  
  <img width="1279" alt="Ekran Resmi 2024-01-19 00 32 00" src="https://github.com/zeynepderyas/CS-412-Project-/assets/148149481/e6014c2e-3f42-4e88-9296-a3d21a4498d8">

- Training and Testing
  
  <img width="199" alt="Ekran Resmi 2024-01-19 00 33 51" src="https://github.com/zeynepderyas/CS-412-Project-/assets/148149481/d083bd4f-c5a5-4425-ad6e-dbf91b814b7c">

- Our MSE
  
  <img width="586" alt="Ekran Resmi 2024-01-19 00 34 30" src="https://github.com/zeynepderyas/CS-412-Project-/assets/148149481/15940ebc-8481-4868-815d-5b23d0fb53e6">


## Contributions
Since our group was two people,instead of dividing the responsibilities we preferred to do them together. We both took part in every part of the code. We both wrote each part together, but both of us had stronger sides in terms of expressing their opinions on the issues. Below, we have only written about which side we put more effort than the other parts. We both played the same role in every part of the project.

- Zeynep Derya Selçuk: Cosine similarity, Feature analysis parts, mean squares error
- Doğa Koltan: Data preprocessing, tokenization, training and testing
