# Airbnb project

### The aim of this project is to put in practice the CRISP-DM process for data analysis by creating a blog post on Medium related to Data Science.

# Installations

### The code in the project can be executed using Anaconda distribution of Python ver 3.x and does not require any additional scripts.

# Business and Data Understanding

### Business need is to answer these three questions:
### 1. On which month book an Airbnb to visit Seattle
### 2. On which weekday an Airbnb to visit Seattle
### 3. Which is the cheapest accomodation

### To do this the best way is to understand and analyze the datasets provided on Kaggle: they give information about bookings, reviews and listings.

# Data Preparation

### In order to work with clean data it has been necessary to remove some useless data from the datasets, for example the column "license" in the listing dataset that was all null and the bookings that didn't have the price info in the "calendar" dataset.

# Modeling

### In order to answer the questions it was necessary to wrangle data. To answer to first two question two plots based on months and days groups have been created to get evidence of the mean price by night of each booking during these periods. To answer the third question it has been necessary to join two datasets: calendar and listings. Once done, it was quite easy to sort the accomodation names by mean price by night.

# Evaluation

### These have been the results:
### January is the cheapest month in Seattle
### Wednesday is the cheapest day in Seattle
### "Cozy, cute, Queen Anne living" is the cheapest accomodation in Seattle

# Deployment

### We can use these results as a prediction of when and where we should book a room via Airbnb in Seattle. We got the info we were looking for in this project! 

# File descriptions and links to interact with them

### [Data sets](https://www.kaggle.com/airbnb/seattle/data) : at this link you can find the datasets used for this analysis (reviews, listings and bookings calendar)
### [Python Code](https://github.com/carini93/DataScienceBlogPost/blob/master/When%20and%20where%20do%20an%20holiday%20in%20Seattle.ipynb) : at this link you can find the python code created to get the insights explained in the post
### [Blog post on Medium](https://medium.com/@carini93luca/when-and-where-should-you-book-an-holiday-in-seattle-c08702998a6c?sk=9b2eb2fabcd0b74b23816745a689e0a7) : at this link you can find the blog post about this analysis

# Authors

### Luca Carini










