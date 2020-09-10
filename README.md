# Pandas-Data-Science-Tasks
Disclaimer: This project is done with the assistant of 'Solving real world data science tasks with Python Pandas!' under this youtube link: https://www.youtube.com/watch?v=eMOA1pPVUc4. The data are created by author, not from real world data. Some additional features and amendments are made beside the video.

## Setup

The dataset can be found in file Sales_Data. It contains information of 12 months worth of sales data, including quantity, price, and date etc. 

## Background Information:

There will be 3 main parts in our project. 

### Part 0: Importing the Dataset and Cleaning data 
We start by cleaning our data. Task of this part includes:
- Drop rows with NaN values from DataFrame
- Drop rows based on certain condition (e.g. meaningless data)

We will change the type of columns (to_numeric etc.) in the later parts. It is recommended to change the types in this part for smoother analysis.

### Part 1 : Data Analysis
After cleaning our data, we will move to data analysis part. We will mainly focus on these 5 questions:
- What is the best month for sales? How much was earned in that month?
- Which city had the highest number of sales
- What time should we display advertisements to maximize likelihood of customer's buying product?
- What products are often sold together?
- Which products are bestseller? Why do you think it did?

To answer these question, we will apply Pandas dataframe and related functions.

### Part 2: Data Staging 
In the last part, we will migrate our data to mysql database and save the dataframe as csv file. The user will need to enter the  name of database, user and password for their own database. Set up in the database will not be covered. 

We will generate better visualized our findings with graphs in Tableau. 
Please read my analysis In Tableau through the link below:
https://public.tableau.com/views/Sales_Analysis_15985115650620/SalesforeachMonth?:language=en-GB&:display_count=y&:origin=viz_share_link

