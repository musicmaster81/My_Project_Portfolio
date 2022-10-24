# The Portfolio of Danny Garcia
# Please visit [this link](https://musicmaster81.github.io/Danny_Portfolio/) to see my most up to date portfolio

##### Email: dannyboy4928398@gmail.com

## 1. [House Prices Machine Learning Project](https://github.com/musicmaster81/Housing_Prices_Project/blob/main/House%20Prices%20Project%20v2.py)
#### Attempting to find a "deal" on a piece of real estate is a problem that has plagued investors for years. Luckily, thanks to a data set provided by the Housing Prices Kaggle competition, I was able to create a Regression model that is able to accurately depict the prices of homes in a small town in Iowa. There were many technical skills involved in this project, but some of the problems that I had to overcome were:
- How can categorical variables be incorporated into a Linear Regression model?
- Which features are most correlated with the Sale Price of each home?
- How should outliers be handles to not wreak havoc on our model?

### While Linear Regression may be considered a less robust Machine Learning model, the techniques that I learned throughout this project has really helped me understand what it takes to set-up and follow through on a Machine Learning workflow. One of the ways I was able to determine that I needed to scale my data and get rid of outliers was by plotting both a kernel density estimation along with a boxplot, which I'll show here:
![](/Images/Housing_Boxplot.png)

## 2. [Titanic Classification Project](https://github.com/musicmaster81/Titanic_ML_Project/blob/main/Titanic%20Project.py)
#### As part of a competition on Kaggle, I created this Machine Learning project to try and predict which passengers survived the tragic sinking of the Titanic. It follows a standard ML workflow, whereby we create our data matrix, define our feature and target vectors, and fit our classification model (Logistic Regression is the model I chose). However, in order to do so, we had to answer the following questions:
- Which features are the best choices to use for our model?
- Do we need to quantify any features that contain data as strings?
- Which model is best for the end goal of the project?

### As a  Machine Learning Engineer, understanding concepts like bias, variance, and train/test splits are pivotal for the success of any model that I create. Note that the datasets for this project are stored in my Titanic Project respository along with my prediction series if you would like to verify the most recent model's accuracy. Additionally, here is a correlation heatmap matrix that I used to choose my features:
![](/Images/Titanic Correlation Heatmap.png)

## 3. [Car Prices Machine Learning Project](https://github.com/musicmaster81/Car_Prices_Project/blob/main/Car_Prices_Project.ipynb)
#### For this project, I created a K-Nearest-Neighbors model to help predict car prices based upon the best features of automobiles in the corresponding dataset. Some questions that I attempted to answer were:
- Which features give us the lowest RMSE score?
- For which value of the hyperparameter K gives us the best performance?
- Is a Univariate or Multivariate model better for predicting the price?

### While not necessarily the most robust algorithm, the K-Nearest-Neighbors model is a fundamental Machine Learning algorithm to understand. I would argue that one could consider it a sort of "predecessor" to more robust algorithms like Linear Regression or even Neural Networks. It's also a good model to practice tuning techniques. As an example, here is a visualization of my model's perfornace for various values of neighbors, k:
![](/Images/K_Values2.png)

## 4. [SMS Spam Classification Project](https://github.com/musicmaster81/Spam_Classifier_Project/blob/main/Spam_Classifier_Project.ipynb)
#### One of the major problems plaguing technologically advanced society is the never ending amount of robocalls and spam text messages. For this project, I created a Classification model that helps predict if a given message is spam or not. The following techniques were used in this project:
- Multinomial Naive Bayes was used to calculate the probability of a message being spam given the words in the messge.
- Conditional probability fundamentals were useed in order to calculate all of the necessary elements of the Naive Bayes algorithm formula.
- Smoothing techniques like the addition of a smooting parameter were used to help address issues pertaining to the vocabulary set.

### This is yet another project dedicated to showcase my abilities as a Machine Learning engineer. Spam classification algorithms are used extensively within email applications to identify spam emails and automatically redirect these emails from your inbox to your spam folder. As such, this project, with a few modifications, has numerous "real world" applications. 

## 5. [Fandango Movie Project](https://github.com/musicmaster81/Fandango_Movie_Project/blob/main/Fandango_Movie_Project.ipynb)
#### In 2015, there was a scandle involving the movie rating site Fandango in which they were accused of rating movies too high by rounding up ratings to the nearest star. Admitting that there was a bug, Fandango released a statement saying the issue had been resolved beginning in 2016. However, they provided no proof of fixes. The goal of this project is to answer the following questions:
- Did Fandango keep their word when they announced they had fixed the rating issue?
- Was there a marked difference in the way Fandango rated movies in 2015 vs. 2016?

### This project is meant to showcase my ability to use statistical analysis to generate insights and answers for real world questions. Here is a Kernal Density Estimation that will help us craft an answer:
![](/Images/Fandango_KDE.png)

## 6. [E-learning Advertisement Project](https://github.com/musicmaster81/Advertisement_Project/blob/main/Advertising%20Project.ipynb)
#### For this project, we imagine that we work for a popular e-learning platform that teaches coding (eg Coursera, Udemy, etc.). Management has expressed interest in increasing the advertising budget and wishes to begin a new marketing campaign in two markets. The goal of this project is to answer the following questions:
- Which kinds of topics are potential learners interested in?
- Which two markets are the best for advertisement?
- How much would potential learners in those markets be willing to pay for our product?

### Similar to my Fandango project, this project is dedicated to showing how I can apply statistical concepts like frequency tables and distributions in order to generate meaningful insight.
![](/Images/Web_Developer_Count.png)

## 7. [Lottery Addiction Project](https://github.com/musicmaster81/Lottery_Addiction_Project/blob/main/Lottery_Addiction_Project.ipynb)
#### With the continuation of the complete legalization of Sports betting across the US, one could expect that the number of gambling addicts across the country will continue to increase. This project is meant to help individuals addicted to playing the lottery visualize how slim their chances are of winning by answering the following questions:
- What is the probability of winning the big prize in a single ticket?
- What is the probability of winning a prize if we play 40 tickets?
- What is the probability of having at least 5 winning numbers on a single lottery ticket?

### This project is meant to showcase my knowledge of Probability and Statistics. We craft several functions in here that are based upon the ever-important "n-choose-k" combination forumula.

## 8. [Hacker News Posts Project](https://github.com/musicmaster81/Hacker_News_Project/blob/main/Hacker%20News%20Post%20Project.py)
#### For this project, we examine the posts from a popular technology news website called [Hacker News](https://news.ycombinator.com/). There are two different types of posts that users can submit to the Hacker News website, "Ask HN" and "Show HN". The former posts are used to ask a question, whereas the latter are used to impart content that users find interesting or insightful. We seek to answer two questions in this analysis:
- Which type of posts, on average, receive more comments?
- Do posts created at a certain time have an above average amount of comments?

### With the importance of Social Media in our society, insights like these can be invaluable to marketing teams for companies looking to improve the amount of interatcion between the company and potential consumers. 

## 9. [Legacy Automation Project](https://github.com/musicmaster81/Legacy_Automation_Project/blob/main/Legacy%20Automation%20Project.py)
#### This project is one that I created to assist me with a daily report that I run each day for work. I was able to automate a 40 minute process and condense it down to 2 minutes. Please note that the workflow will appear somewhat vague as I would rather not disclose any remotely sensitive information about our processes. While I try to describe the flow via comments as best I can in the source code, here is a brief summary of what is required by this process each day:
- Save a set of emails that contain data for that particular day
- Edit an excel file to update the date
- Update quntiessential workbooks with the most recent data
- Run previously constructed VBA macros to generate pdf's
- Update links in another pivotal workbook to reflect accurate days
- Run a batch file that uploads required documents to the cloud

### To reiterate, this is an example of what I have been able to accomplish using my skills as an aspiring Data Scientist and Python developer to bring value to my organization by saving roughly 158hrs of work each year. 

## 10. [Traffic Analysis for I-94](https://github.com/musicmaster81/Traffic_Indicators_Project/blob/main/Traffic%20Indicators%20Project.py)
#### For this project, we wish to analyze traffic volume for a section of the I-94 expressway in Minnesota between Minneapolis and Saint Paul. Some of the questions that we wish to answer are:
- Is there a time of day where traffic volume is the most heavy?
- Is there a difference in travel patterns on weekends as opposed to weekdays?
- Do certain types of weather have an impact on traffic volume?

### With the amount of travel only increasing after the pandemic, perhaps a company like Uber or Door Dash would like to know precisely when traffic will be bad so they can prepare or avoid these above average travel times. 

## 11. [Euro vs. the USD Analysis](https://github.com/musicmaster81/EURO_vs_USD_Project/blob/main/Exchange%20Rates%20Project.py)
#### No project on my portfolio is probably more relevant than this one. For all of 2022, the Federal Reserve's FOMC has been hiking interest rates in an attempt to curb inflation that is boarderline run-away. This project takes a look at the value of the Euro compared to the USD to examine the following:
- Did the slashing of interest rates during the 2008 Recession strengthen or weaken the Euro compared to the USD?
- Did the slashing of interest rates during the 2020 Pandemic strengthen or weaken the Euro compared to the USD?

### My hypothesis is that since hiking rates generally strengthens a currency, we should expect to see the slasing of rates weaken a currency. This project is also mainly meant to showcase my matplotlib graph construction skills. Here is the image that I created to validate my hypothesis:

![](/Images/EUR_USD_Graph.png)

## 12. [Employee Exit Survey Project](https://github.com/musicmaster81/Employee_Exit_Project/blob/main/Exit%20Survey%20Project.ipynb)
#### In an era where it appears that the average tenure for an employee continues to decline, it is relevant for any organization to gain insight into just exactly why employees are leaving their jobs so soon. For this project, we take a closer look at this issue to determine the following:
- Are employees with short tenures leaving their jobs due to some kind of dissatisfaction? Does this trend translate to employees with longer tenures as well?

### This project's main goal is to showcase my data cleaning skills. The overwhelming majority of any Data Scientist's time is spent in the data cleaning/preparation phase. As a result, having the toolkit to properly wrangle and munge data is crucial. 

## 13. [Star Wars Survey Project](https://github.com/musicmaster81/Star_Wars_Survey_Project/blob/main/Star_Wars_Survey_Project.ipynb)
#### Since the release of the recent "Obi-Wan" spinoff show on Disney+, what better way to celebrate than to perform data analysis on a Star Wars survey for a project? The data set was assembled by the company FiveThirtyEight, and throughout this project we look to answer the following questions:
- Which Episode to people enjoy the most?
- How many people have seen each episode?
- Is there a split in results between males and females?

### Similar to the Employee Exit Survey Project, this project is designed to showcase more of my data cleaning skills to generate important insights from unclean data. 

## 14. [CIA Factbook Project](https://github.com/musicmaster81/CIA_Factbook_Project/blob/main/CIA%20SQL%20Project.ipynb)
#### Standard Query Language (SQL) is one of the most quintessential tools to possess in order to begin to interact with RDBMS. In this project, we use a data set published by the CIA that contains data on many of the worlds countries. We leverage this data set in order to anser the following questions:
- What is the average population for each country on earth?
- What is the average size of each country on the planet?
- Which country is considered "overpopulated", that is, which country has an above average amount of people but below average land mass?

### Again, this project's main goal is to showcase my knowledge of SQL and my proficiency in writing complex queries.

## 15. [App Store Project](https://github.com/musicmaster81/App_Store_Project/blob/main/App%20Store%20Project.py)
#### This project analyzes apps on both the Google Playstore and the App Store. The analysis looks at the following features of apps on each respective appstore:
- The number of free apps on either store
- The most popular genres of apps
- The most popular apps based on installations or downloads

### The idea behind this project is, if I were approached by employers who were considering launching an app, what insights could I provide?
