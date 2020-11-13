# Trip-Advisor-Review-Text-Classifer
My try at text classification using Bag of Words methods and several classification algorithms
  
My inspiration for this project came from watching a video aiming to do a similar task with Amazon reviews (https://www.youtube.com/watch?v=M9Itm95JzL0&list=WL&index=13&t=4130s). I tried to simplify and recreate using pandas libraries and on a different dataset which i obtained from Kaggle (https://www.kaggle.com/andrewmvd/trip-advisor-hotel-reviews). This repo contains my pickled model file as well as my jupyter notebook which goes through the process of model creation including loading data, transforming, vectorizing model, fitting, scoring and then parameter tuning.
  
This is my first attempt at utilizing the expansive sklearn library for classification and i explored its many offerings. I fit an SVM, multinomial Naive Bayes, logistic regression and decision tree model to the data and compared performance. I used standard vectorization as well as Term Frequency–Inverse Document Frequency (TF-IDF) vectorization to compare its impact on the model.
  
Data: "tripadvisor_hotel_reviews.csv"
  
pickled model: "SVM_review_classifier.pkl"
  
Notebook: "Trip Advisor Bag of Words Analysis.ipynb"
