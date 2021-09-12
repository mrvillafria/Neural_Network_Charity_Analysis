# Neural Network Charity Analysis

## Overview of Project
For this week's project, we will be implementing Neural Networks using the TensorFlow platform in Python. Neural Network is a machine learning technique that is modeled after the neurons in the brain. With Neural Networks, we can combine multiple statistical and machine learning models with little effort. This model helps evaluate all types of input data and produce a decision-making result.

### Purpose
The purpose of this week's project is to design and train a Neural Network model so Alphabet Soup can predict which organizations are worth donating and which are too high risk. Alphabet Soup is a non-profit foundation dedicated to helping organizations that project the environment, improve people's well-being, and unify the world.

## Results

The Alphabet Soup provided us a dataset containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Here are the columns that captured metadaata about each organization:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

Data Preprocessing
- The target variable for the data set was IS_SUCCESFUL.
- The variables we considered features were APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
- The EIN and NAME columns were dropped since they were not target variables or features needed for the analysis

Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?

## Summary

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.