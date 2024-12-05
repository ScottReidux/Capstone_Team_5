# Capstone_Team_5
AAI-590_Capstone_Project

Justin (Scott) Reid and Christi Moncrief

Shiley-Marcos School of Engineering, University of San Diego

MSAAI – 590: Capstone Project

Professor Anna Marbut

December 9, 2024

## Description
Our capstone project tackles the challenge of efficiently identifying relevant grants by
creating a deep learning-based topic modeling system for grant characterization. The project
addresses a common issue: researchers and administrators often face an overwhelming number
of grant descriptions across platforms making it hard to find ones that align with their research
areas. By automating grant classification into specific topics our system will save time for
research teams helping them find targeted opportunities and boosting their chances of securing
funding.

For this project we built an RNN model to classify grants into catagories based on thier title, and compare that to the classifications that BerTopic produced.

### Dataset

https://www.kaggle.com/datasets/webdevbadger/federal-grants-and-funding-opportunities

### Data Cleaning
- Capstone_Project.ipynb
- - cleaned_grants.csv
- Capstone_Project EDA Update.ipynb

### Exploratory Data Analysis
- Capstone_Project EDA Update_1.1.ipynb
- Capstone_Project EDA Update_1.2.ipynb
- - Includes BertTopic model

### Model Design/Building
- Capstone_Project_RNN_FFNN.ipynb
- tokenizer.pkl
- label_encoder.pkl
  
### Model Training
- Capstone_Project_RNN_2.1.ipynb
- rnn_funding_category_model_2.5.h5
  
### Model Optimization
- Capstone_Project_RNN_2.2_Auto_Tune.ipynb
- - Caused too much overfitting
- Capstone_Project_RNN_2.3_Fine_Tune.ipynb
- - Caused too much overfitting
- Capstone_Project_RNN_2.4.ipynb

 ### Model Analysis
- Capstone_Project_RNN_2.5.ipynb
- - Final model and evaluation
