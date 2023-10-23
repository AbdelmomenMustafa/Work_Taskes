# Data Reshaping Project

In this project, I worked with a client's Excel sheet that needed to be reshaped to match the structure of their SQL server database. Here are the steps I followed:

## Step 1: SQL View
I created an Excel file that contains a sample of the SQL database. This file is referred to as `SQLView`.

## Step 2: Client View
I performed some cleaning and analysis on the client's Excel sheet and named it `ClientView`.

## Step 3: Reshaping Process
The reshaping process began with the `unit` table, followed by the `class` and `store` tables.

## Step 4: Store Item Table
The most challenging part of the process was reshaping the `store item` table, which contains the sales items in the store. 

To accomplish this, I used the `VLOOKUP` function to create a new column named `unit id`. This column serves as the link between the `sales items` table and the `unit` table.

This project was a great exercise in data manipulation and provided valuable insights into the power of Excel functions for data reshaping.
