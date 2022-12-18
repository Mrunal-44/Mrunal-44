# Sentimental Analysis on Movie Reviews

Fachhochschule des Mittelstands,Berlin
Final Python Project
Mrunal Badhe  



Background

Sentiments analysis is a data mining approach that uses NLP to assess and comprehend people's opinions and preferences. Information from the web, social media, and other sources is analyzed using computational linguistics and text analysis.This data measures people's feelings, sentiments, views, or points of view; hence, it is also known as opinion mining. This uses NLP to study people's moods in general in society using data from social networking sites on the internet.Raw data for NLP-based sentiment analysis is data in the form of multimedia, text, and pictures. When these data sets are evaluated, they might communicate the poster's tone or attitude.



Project Details

In This Project, We Would Be Using Certain Libraries Such As:-
Numpy 
Pandas 
Scikit-Learn
Nltk 
Re
Sentimental analysis is the study and extraction of meaningful subjective information from textual data using natural language processing. In our case, we were also given an IMDB movie review dataset including around 50k sentimental movie reviews classified as positive or negative. However, our goal is to study the given dataset, build, and train a model that can accurately classify a new unseen review as positive or negative.

The full details about this project is available on our Github Repository.




Data Preprocessing


The first part of processing is Data Pre-Processing. Since original dataset contains only raw text with its label,we need to transform the shape of natural language and remove noises in order to better fit our model. After the completion of this section, the followings steps must be taken:

Load text data and clean it.
Remove HTML tags- The dataset  contains a lot ofhtml tags such as <br>, </br > to remove such tagss this steps is compulsory.
Remove special characters- The dataset also includes special characters such as@,% to remove all the characters this steps is also included. Since before compiling the entire data set needs to be cleaned. 
Convert everything into lower case- Since there are a lot of words which are Uppercase accordingly we need to convert every word in lowercase so that sentiments can be evaluated.
Remove stopwords- Stopwords are use to evaluate the sentiments present inside the sentences.
Stemming- There are a lot of words with same stem but different meanings needs to be evaluated and removed so that the words cannot be repeated. Exchanging of words according to the rules of NLTK Stemming.






