# Project Goal
## Aggregate, clean, and analyze data to develop actionable insights to enhance business performance. Build out reusable classification machine learning model and integrate dashboard for future analysis of data.

## Here's the link to my [Jupyter Notebook](https://github.com/hismith142/Sales_Data_Analysis/blob/main/Financial_Data_Analysis.ipynb)

## Link to [Tableau Dashboard](https://public.tableau.com/app/profile/hayden.smith8882/viz/2019SalesDataDashboard/Dashboard1)

## Project Overview & Summary

### Step 1: Aggregate Data
Data was originally stored in 12 .csv files which I imported into a local databse using MySQL.
From there, I aggregated the data into a table using SQL queries and exported it as a .csv file for convenience.

### Step 2: Clean Data
I took the .csv file into a Jupyter environment and using Python's pandas library parsed down the data further.
Additionally, column datatypes were updated to reflect the needs of analysis later on in the project.

### Step 3: Develop Quesitons
I spent some time thinking about the questions a company might ask me to answer given the dataset. Some might include:
- The company is increasing its marketing budget; what is the optimal time of day to show advertisements to potential consumers?
- Given popular pairings of items, what would be an example of a promotional deal that would entice consumers to purchase from the company?
- And so on...

### Step 4: Analyze Data
Python's pandas library made light work of the questions I had thought up. To get a better idea of what I was seeing, however, I used the matplotlib library to visualize my findings.

### Step 5: Machine Learning Model
The goal of this model was to be able to identify what a user would purchase as soon as they logged on the site, no purchase history required. This way, the company could tailor specific promotional material to consumers without losing too much of their profit margin. To do this, I prepared the data for training using one-hot encoding. I assembled a data pipeline where I tested several popular classification models and measured their accuracy. After determining the highest performing model, I exported it using the pickles library in python such that the model could make predictions on future data without the need for retraining.

### Step 6: Tableau
To further visualize the data, I constructed a dashboard of my findings to Tableau which would in theory be updated with new data as the database grows in size. In order to do this, however, I would also need to create a data pipeline from the server to Tableau as reformatting was required.

