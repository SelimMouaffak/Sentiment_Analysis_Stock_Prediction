# ML Project 2: Stock Prediction using Sentiment Analysis
News articles Sentiment Analysis to improve Stock Price Prediction using LTSM

## Description of the project
Investing in stocks is one of the most widespread tools for modern people's financial management, therefore predicting stock market prices has always been  a topic of high interest.  
However, stock predictions remains a challenging task, because
their prices depend on political factors, change of leadership, investor sentiment and many other various factors, making it volatile and hard to predict.
One of the factors that influence stock prices is news publications. Existing studies in sentiment analysis have found that there is a strong correlation between the movement of stock prices and the publication of news article.

## Introduction
In this project, we investigate the impact of news articles on stock predictions. First, we use a Long Term Short Memory Neural Network (LSTM) to  predict stock prices using only historical data of the market prices. Then, we use different Natural Language Processing (NLP) libraries like Flair and Vader to create news sentiment which we include as input to our model stock predictions using sentiment of news written by popular media. 

We showed that with the proper libraries and data cleaning, including news sentiment improved the stock predictions reduced the Mean Absolute Percentage Error (MAPE) by 1.04 \%.


## Content
### Pre Processing
* Removal of stop words, punctuation and special characters
* Lemmatization of articles
* Case normalization
* Dropping sources and companies under threshold
### Sentiment Analysis
* Use of three different libraries : Flair, Vader and TextBlob
* Methodic comparaison of their impact and choice of better fit
### Stock Prediction 
* Use of Tensorflows's Keras LSTM model with 4 different architectures
* Use of Technical and Fundamental analysis models



## Installation

### Clone
* Clone this repository to your machine using this link `https://github.com/SelimMouaffak/Sentiment_Analysis_Stock_Prediction`

### Dataset
* All the datasets that are used in this project can be found in this [Google Drive](https://drive.google.com/drive/folders/1ukot3aSpJVPNmvgSGfJu3aadm62EPVSt?usp=sharing)
* Make sure to change the file paths in the notebooks according to your directories to assure smooth code execution


## How to use 

* Commented notebooks can be found in the relevant folders
* All the models used to obtain results (with and without sentiment analysis) are in the Stock Prediction folder

# Credits
Project realised by three EPFL (Ecole Polytechnique Fédérale de Lausanne) students: Amine Atallah, Mohamed Ali Dhraief and Mohamed Selim Mouaffak

We would like to thank Prof Yu and his team for their continuous guidance throughout the project.

