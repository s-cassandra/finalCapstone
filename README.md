# Project Name: Sentiment Analysis of Amazon Reviews

## Description
Sentiment Analysis of Amazon Reviews constitutes a sentiment analysis workflow for analysing Amazon product reviews. This code starts by importing necessary libraries: spaCy for natural language processing (NLP], pandas for handling data, and TextBlob for sentiment analysis. The dataset [(which can be found here)](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products), consisting of Amazon product reviews, is loaded into a pandas DataFrame, and initial data exploration is performed, showcasing the structure and size of the dataset along with missing values. Key preprocessing steps involve removing missing values and tokenizing the 'reviews.text' data using spaCy to lemmatize tokens and remove stopwords and punctuation. Subsequently, a subset of the data is chosen for processing efficiency (though this does limit this models accuracy), and polarity analysis is conducted using TextBlob to assign polarity scores to each review. Finally, a function is implemented to convert polarity scores to sentiment labels. 

This project is important as the use of sentiment analysis in real-world scenarios allows businesses to understand customer opinions and emotions towards their products or services. By analysing sentiment in Amazon product reviews, companies can gain insights into customer satisfaction, identify areas for improvement, and make informed decisions to enhance their products or services. From a coder's perspective, the code demonstrates best practices in data preprocessing, tokenization, and sentiment analysis techniques using popular and beginner-friendly libraries such as spaCy and TextBlob, making it valuable for those eager to practice NLP.

## Table of Contents
1. Installation
2. Usage
3. Credits

## Installation
To install Sentiment Analysis of Amazon Reviews you can do so by simply downloading this file or you can follow these steps:

1. Create a folder in your code editor (I used Visual Studio Code).
2. Open a terminal
3. type into your terminal: git clone (URL for this repository)
4. cd finalCapstone
5. You will also have to follow the link given to access the csv file (dataset) used in this project, download it and rename it "amazon_product_reviews", otherwise the code won't run.

## Usage
Once installed, you can use Sentiment Analysis of Amazon Reviews by following these instructions:

1. Import libraries spacy(NLP) and pandas(handle amazon csv file), textblob for polarity
2. Load spaCy's english model (small)
3. Create a preprocess data function
4. Load dataset and clean data
5. Create functions for sentiment analysis
6. Test accuracy
   
Here are some screenshots of Sentiment Analysis of Amazon Reviews in action:
![Screenshot1](https://github.com/s-cassandra/finalCapstone/assets/152437473/6926bfc2-f4cd-4ff9-82e6-ca177c8760cf)
![Screenshot2](https://github.com/s-cassandra/finalCapstone/assets/152437473/c9c6e113-c309-49b2-ad06-ca071e44937b)
![Screenshot3](https://github.com/s-cassandra/finalCapstone/assets/152437473/295f1f15-84a6-44a9-a0c4-b55662ec9cc4)
![Screenshot 4](https://github.com/s-cassandra/finalCapstone/assets/152437473/e6daa799-8411-45f1-aeeb-143243beeeaa)

## Credits
This project was authored by Seema Cassandra Bickram.
