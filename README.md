# SpaceX-Falcon-9-Landing-Prediction

### Overview

This project focuses on predicting the successful landing of the Falcon 9 first stage during SpaceX rocket launches. Given the significant cost savings associated with reusing the first stage, determining the likelihood of a successful landing is crucial for estimating the overall launch cost.  
You can get a comprehensive overview and delve deeper into the concepts, methodologies, and code implementations by referring to the associated PowerPoint presentation.  
Additionally, detailed explanations and code snippets are available in the Jupyter Notebook files provided.

### Project Scope

The main goal is to create an accurate prediction model based on processed data.
To achieve this, the project includes access to the SpaceX API as well as web scraping from Wikipedia to extract relevant data and information. Furthermore, during data cleaning and exploratory analysis (EDA), we will focus on improving the quality and relevance of the information present in the data, through feature engineering. This approach not only aims to remove any anomalies and ensure data consistency, but also to model the variables more effectively, thus optimizing the performance of the future predictive model.
The project will end with the development and evaluation of a predictive model, with the aim of maximizing the accuracy of predictions.

## Contents

### Request to SpaceX API and Data Cleaning
* Make a GET request to the SpaceX API.
* Clean and format the obtained data.

### Web Scraping with BeautifulSoup
* Extract Falcon 9 launch records HTML table from Wikipedia.
* Parse the table and convert it into a Pandas data frame.

### Exploratory Data Analysis and Training Labels
* Perform exploratory data analysis on the SpaceX dataset.
* Determine training labels for the predictive model.

### Execute SQL Queries on SpaceX DataSet
* Understand the SpaceX DataSet.
* Execute SQL queries to answer assignment questions.

### Exploratory Data Analysis and Feature Engineering
* Conduct exploratory data analysis using Pandas and Matplotlib.
* Prepare data for feature engineering.

### Geographical Analysis of Launch Sites
* Mark all launch sites on a map.
* Mark success/failed launches for each site on the map.
* Calculate distances between a launch site and its proximities.

### Creating Interactive Plots with Dash
* Utilize Dash to create interactive plots.

### Final Data Analysis and Model Training
* Create a column for the class in the dataset.
* Standardize the data.
* Split the data into training and test sets.
* Find the best hyperparameters for SVM, Classification Trees, and Logistic Regression.
* Determine the best-performing method using test data.
