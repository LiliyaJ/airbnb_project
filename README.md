## Airbnb_project ##

### Table of content ###

1. [Project Motivation](#ProjectMotivation)
2. [Introduction](#Introduction)
3. [Installations](#Installations)
4. [File Descriptions](#FileDescriptions)
5. [Process](#Process)
6. [Results](#Results)
7. [Licensing, Authors, and Acknowledgements](#LicensingAuthorsAcknowledgements)


#### <a name="ProjectMotivation">Project Motivation ####
I used Airbnb data for Boston and a bit for Seattle from the years 2016, 2017 to better understand:

1. If one want to get a credit for real estate where would it be to earn money and where to live?
2. Once one have chosen the city which location would bring more money or how the prices change inside the city?
3. How size of an apartment affect the price per night?
4. What else affect the price?
5. What is really matters to the guests?

### <a name="Introduction">Introduction ####
Each Airbnb set contains three files with information about description of apartment, neighbourhood, locations, availibility, prices, reveiws, reviews scores, review comments etc. This project is meant to deliver result observations based on analysis of the data. 
  
#### <a name="Installations">Installations ####
The code is written in Python virsion 3. 
Extra installed libraries: numpy, pandas, matplotlib.pyplot, sklearn.linear_model - LinearRegression, sklearn.model_selection - train_test_split, 
sklearn.metrics - r2_score, mean_squared_error, seaborn, nltk - stopwords 
  
#### <a name="FileDescriptions">File Descriptions ####
There is one notebook summary.ipynd with the code that helps to answer the questions and visualize the results. In the notebook every step belongs to a question.
Except for the first four methods that aim to automize some repetitive processes in workint with the data sets.

File with standard stop words, wich I used to clear commentars.

File with feature list which were used for the regression modeling. Just for those who are curious.

#### <a name="Process">Process ####
The process starts with understanding which business questions could one try to unswer with the data set. Defining the questions which I want to answer. Then preapeating and cleaning the data which includes checking all data I might need, turning them into right type, dealing with nulls and categorical variables etc. Modelling with analysing the results. Visualizing the results. Evaluating the results and making conclusions. 

#### <a name="Results">Results ####

[The main findings are summarized in this post](https://medium.com/@liliya.jeromin/this-is-why-you-need-to-rethink-how-to-use-airbnb-64963ae61d06?sk=50a80ef8b27eb233d0e6e61b1ed01511).

#### <a name="LicensingAuthorsAcknowledgements">Licensing, Authors, and Acknowledgements ####

Credit to Airbnb for data sets. Both sets could be find on Kaggle. [Boston](https://www.kaggle.com/airbnb/boston), [Seattle](https://www.kaggle.com/airbnb/seattle/data).
This repository is meant to be a data analytics training but if you find something interesting in the notebook feel free to use it. 
