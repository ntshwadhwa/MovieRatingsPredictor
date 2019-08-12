
 The primary objective of the project is to develop a robust framework for predicting the audience and critics ratings of the upcoming movies based on several attributes
 The successful prediction of ratings plays a vital role in movie industry because it involves huge investment
 
 
__________ Data Collection __________
The Data is collected from “Rotten Tomatoes” a review-aggregation website for film and television
Data for Director and Actors likes has been collected from Facebook pages.
Data has attributes:Movie Name, Audience Rating,Critics Rating,Actor_names, Actor_links, Synopsis,Release Date,Genre ,Studio, Directed By etc.


__________ Data Preparation : Cleaning of Data __________
We have performed the data cleaning on the data set  to make sure there is no missing values and outliers.
We have converted special characters like $ and % to numbers.
We modified the data in a layout and format that is capable to be read by csv reader tool
 
 Refer to RT_data.zip for final prepared data set reference

__________ Methodology : SVM  __________
To obtain the desired prediction about ratings of the movie we will be using the Support Vector Machine model.
 SVM is a supervised machine learning algorithm which can be used for classification or regression problems. 
It uses a technique called the kernel trick to transform your data and then based on these transformations it finds an optimal boundary between the possible outputs. 
It does some extremely complex data transformations, then figures out how to separate your data based on the labels or outputs you've defined.


Training data: 70% of data set
Test data: 30% of data set
We have used K-cross folds validation with k=10


We have used SVM Linear (SVC) for the Linear Classification
SVM Linear performs classification by finding the hyper plane that maximizes the distance margin between the two classes
We have used SVM Regression(SVR) for the Regression.
SVR is used for working with continuous values instead of Classification 

__________ Software Package __________
1.) CSV : To read the data from the stock prices
2.) Numpy : To perform calculations
3.) Scikit-Learn : To build a predictive model
4.) Pandas : To perform data manipulation and analysis
