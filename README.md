# Sentiment Analysis and Topic Modelling on Covid Vaccine Tweets

This project is intended for mining the opinion of general public regarding Covid Vaccination. Worldwide people have been dubious about vaccination drive, so the main objective of this project was to discover important topics of discussion and analyze the ratio of public having negative to positive opinions. <br/>
<br/>
Country level Vaccination advancement is analyzed to track the progress of Covid Vaccination.

## Description

### Dataset Used

1. [Covid Vaccine Tweets Dataset](https://www.kaggle.com/kaushiksuresh147/covidvaccine-tweets)<br/>
   This Twitter dataset is taken from Kaggle, which consists of tweets extracted with #CovidVaccine. It comprises of more than 200k Tweets with 13 attributes namely 'user_name', 'user_location', 'user_description', 'user_created', 'user_followers', 'user_friends', 'user_favourites', 'user_verified', 'date', 'text', ' hashtags', 'source', 'is_retweet' <br/>
 
2. [Covid-19 World Vaccination Progress Dataset](https://www.kaggle.com/gpreda/covid-world-vaccination-progress)<br/>
  Data is collected daily from Our World in Data GitHub repository for covid-19, merged and uploaded. Country level vaccination data is gathered and assembled in one single file. Then, this data file is merged with locations data file to include vaccination sources information. A second file, with manufacturers information, is included. The dataset comprises of 15 attributes only 5 attributes are mainly used in our work. They are 'total_vaccinations', 'country', 'date', 'daily_vaccinations', 'vaccines'
 <br/><br/>
 
### EDA Covid Vaccine Sentiments

1. Pre-processed Tweets by removing special symbols (#,@), retweets and emoticons
2. Tokenized Tweets to get seperate each token from complete sentence
3. Removed Stop Words using NLTK's english stop words' list
4. Extracted Nouns and Verbs using POS Tagging
5. Applied Lemmatizer to get the root word
6. Converted data in location field to respective Country
7. Exploratory Data Analysis


### Classification Covid Vaccine Sentiments
1. Vectorized data using Tf-idf Vectorizer
2. Trained model using three classifiers <br/>
         i. Gaussian Naive Bayes (Accuracy: 72%) <br/>
         ii. SVM (Accuracy: 87%) <br/>
         iii. LSTM (Accuracy 96%) <br/>
         

### Topic Modelling LDA
1. Tokenized tweets
2. Removed Stop words
3. Extracted useful terms using POS Tagging
4. Applied Lemmatizer
5. Vectorized using Count vectorizer
6. Trained LDA Model
7. Extracted Top 7 topics disccued 

### Libraries Used

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Plotly
* Vader
* NLTK
* Sklearn

## Results

![alt text](http://url/to/img.png)

## Contact

[E-Mail](malvipatel1999@gmail.com) <br/>
[LinkedIn](https://www.linkedin.com/in/malvi-m)

