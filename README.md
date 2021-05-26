# Academic-Assignments
Assignments done as part of the curriculum

# DIGI405: Texts, Discourses and Data
These are the Lab exercises and assignments done as part of the course curriculum.

Lab exercise 1 is all about concordance analysis for finding patterns. The Clinton-Trump Corpus (Retrieved from http://www.thegrammarlab.com/?nor-portfolio=corpus-of-presidential-speeches-cops-and-a-clintontrump-corpus) consists of speeches by Hillary Clinton and Donald Trump at events during the 2016 US presidential election campaign. The speeches for each speaker are stored in two separate directories. Toolkit used for concordancing and analysis is Laurence Anthony's AntConc Software. We created a concordance of the word people to identify distinct pattern of usage.

Lab exercise 2a is on web scrapping using Python, BeautifulSoup and CSS selectors. We scrapped content from a site specifically setup for this task: Scraping Garden Party. Python libraries used are Requests and BeautifulSoup.

Lab exercise 2b demonstrates the functionality of regular expressions. Regular expressions are useful for data clean up, text normalization and feature extraction for analysis or modeling. Python libraries used are Requests and Re.

Lab exercise 2c is about detecting the named entities (Named Entity Recognition). Our named entity recogniser will attempt to detect the names of 'iwi'. Iwi are a fundamental social grouping in Māori society, both before and after British colonisation. Python libraries used are Spacy and Random. Data model is trained successfully with iwi as an entity label.

Lab exercise 3 is an assessment on the competence in applying Topic Modelling as a recommendation engine to Ted.com. Topic modelling is a statistical model to discover topics from a large collection of text. Topic model: Latent Drichlet Allocation (LDA) Software tool: Topic Modelling Tool (TMT). Top 3 recommendations for 2 specific videos are evaluated.

Corpus analysis on the representation of subcultures: fanfiction communities

Corpora analysis is a part of decision making to resolve many of the real-world issues.For this assessment I have explored the corpus of Harry Potter books communities.The fanfiction corpus that I have built up consists of 20 text files with almost 30,000 words. . I used Laurence Anthony’s antconc, which is an effective tool to identify patterns and keyword frequencies. To scrap the data I used web scraper tool from google chrome.

For the final assessment I build a Naive Bayes text classification model to detect fake/legit celebrity news, using Orange data mining tool. F1 score: 0.58 Precision: 0.62 Model accuracy: 60%

# STAT455: Data Collection and Sampling Methods
These are the assignments done as part of the course curriculum.
Data collection process and the sampling methods are extemely important. Analytics on a wrong data is completely worthless.

Assignment1 is a discussion on framing appropriate questionnaire for the data collection and demonstration of simple random sampling using R package sampling. dataset: Ass1data

Assignment2 assess stratified sampling method & systematic sampling method with its descriptive statistics and a comparitative study with simple random sampling method. dataset: Ass2data

Assignment3 is an assessment of the random sampling survey design and adaptive cluster sampling process.

Final assessment checks on the important aspects of the survey process and the appropriate sampling methods.

Project: This is a group project. We were supposed to do the data collection manually. But we were not able to collect the data after the changed circumstances and complete lockdown. We went though all the stages of data collection survey. First we decided on survey goal and the objectives. On the next stage we designed the survey questionnnaire. We designed an app for the data collection project which is located at http://fbot.nz/covid-19/. We also considered the attire, bodylanguage and the script to be used when approaching the respondents, quality checking of the data and the final deliverables.

# STAT448: Big Data 
These are the assignments as part of the course curriculum.

Analytical tool: R studio
Programming language: R

Assignment 1 is a comaritative study on Ordinary Least Square Estimate(OLS) 1. By using Linear algebra calculations 2. By manual model fitting method in R 3. by using lm() function in R

Assignment 2 fits different regression models to predict the actual sales price. Dataset used is Residential-Building-Data-Set.xlsx. A comparitative study of stepwise selection, ridge,lasso models etc. are applied. Lasso regression model has the least RMSE value.

Assignment 3 is 1. demonstration of nodes/neurons and hidden layers in neural networks 2. application of filters on a convolutional neural network.

Final assessment is 1. on the understanding of different deep level machine learning concepts 2. Fitting a regression model to predict the percent of successful field goals based on 4 different predictors. The dataset ”mlr09” is about physical measurements and performances of 54 players in the NBA.

# DATA423: Data science in Industry
These are the assignments done as part of the course curriculum.

This is one of my favourite course that is focused on the applied side of data science rather than the theoretical side. 

Assignment1 is a demonstration on the usage of shiny R package to build interactive web apps. Dataset:Ass1Data is interactively explored using shiny app.

Assignment2 is a study on different outlier detection methodology and is presented on a shiny app. Dataset: data imported from github, klucar/tidycseeCOVID19

Assignment3 is the usage of Caret package from R for model selection and evaluation of the best model that is presented on the shiny app. 17 models from diverse sets are trained of which 4 models failed. An empty folder is used to save training results. The top models based on least RMSE value are trained again with the upsized traindata. Dataset:Ass3Data, Best model: Bayesian Regularized Neural Networks, RMSE value on the test data: 20.12. Multicollinearity in the data is effectively handled by the brnn model. 
The best transparent model is cubist with RMSE value on the test data 22.05. Even if the RMSE on resampled data was way too high(77.11), it performed well on the test data.

Assignment4 is 1. a comparitative study on R packages R, mlr3 and the python library scikit-learn. The linear regression model built on CARET and sciki-learn at the same time does not show much difference in terms of the results Scikit learn result: R2 = 0.93, RMSE = 4.5 CARET: R2 = 0.93, RMSE = 4.48 2. the best strategies for a fine report 3. an assesstment on variables control charts. This is useful for evaluating variations in a process. R packages used: qicharts2, dplyr

To handle similar file names for the shiny app, I have created separate branches for each assignments, keeping assignment4 in the master.

# DATA422: Data Wrangling for Data Science
These are the assignments done as part of the course curriculum.

Analytical tools: Ubuntu, Jupyter lab
Programming languages: R, Julia

For the assignment1 I have cleaned up the messy data, merged the datasets and produced the visual plots.

For the assignment2 we scrapped the data from the web, wrangled it, automated it and then produced some visual plots. Also we explored with certaine web services that offer data through APIs that can be converted into a dataframe.

# STAT462: Data Mining
Assignments done as part of the course curriculum.
This is one of the area that I look forward to learn more.

Assignment1 is a 1. discussion on flexible and less flexible regression methods, 2. Density plot of a binary classification problem with their prior probabilities 3. Fitting knn regression model on the data. Best model withvalue of k=30 MSE=17.95

Assignment2 1. Fitted a logistic regression model to predict the probability of a bank note being forged. Prediction accuracy = 88.6%, 2. Fitted the same data with LDA and QDA models. These models improved the accuracy rate, 3. Comparison of test errors.

Assignment3 1. Applied k-means clustering and hierarchial clustering on the data with and without rescaling. dataset:A3data2 2. Support vector classifier is fitted to predict the probability of a bank note being forged. 2. Fitted the data with Support Vector Machine using Radial kernel and compared the results. Model accuracy = 91.26%

# DATA401: Statistics
These are the assignments done as part of the course curriculum. 

Assignment1: we considered 1. a study on area of the states in united states, with histograms and the summary statistics, 2. Total number of Tornados in the US states & territories using boxplot, 3. Exploration on a dataset by using visual methods.

Assignment2: 1. regression using excel. Problem: Family planning effect on fertility rate in 27 developing countries, 2. assessment on probability, random variables and the probability distribution models.

Assignment3: 1. assessment on hypothesis testing to generate confidence intervals, 2. study on cell phone radiation using descriptive statistics , usage of confidence interval on a survey: paid employment while studying at the university. 3. Hypothesis testing on the nutritional contents in packaged food and hypothesis test for university student's habit of watching TV genderwise. 

Project: Part 1 Critical appraising of a report. Report: Research and Development in New Zealand: 2018, Part 2 Analysis report on self sourced data. Title: Melbourne Housing Market. Analysis and regression done using excel spreadsheet.
