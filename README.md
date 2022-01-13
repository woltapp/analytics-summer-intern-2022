# Assignment for BI Developer Internship 2022

We are delighted to see you applying. Now is your time to shine. We’ve prepared a task for you so that you can show your skills and allow us to understand how you approach problems in general. 

In this exercise you get to work on our customer data and build insights-telling visualizations based on the datasets provided.

Good luck! 

## About the data
The data consists of two csv files:  
- first_purchases.csv
- purchases.csv

The data is an artificial dataset that could be produced by our purchase process, where a user makes their first and possibly following purchases from Wolt. We have separated these purchases into two files, the first one containing only the users’ first ever purchases from Wolt, and the second one containing all purchases from these users.

## Fields
In the **first_purchases.csv** file we have the following fields:
- **First Purchase Date**: Date (UTC) when a user did their first Wolt purchase. 
- **First Purchase Product Line**: Product line of the first purchase. This can be either ‘Restaurant’ or ‘Retail store’.
- **User ID**: Unique ID of the user who made the first purchase.
- **Purchase ID**: Unique ID of the purchase.
- **Venue ID**: Unique ID of the venue where the purchase was made.

In the  **purchases.csv** file we have mostly these same fields:
- **Purchases Date**: Date (UTC) of the purchase. 
- **Product Line**: Product line of the first purchase. This can be either ‘Restaurant’ or ‘Retail store’.
- **User ID**: Unique ID of the user who made the first purchase.
- **Purchase ID**: Unique ID of the purchase.
- **Venue ID**: Unique ID of the venue where the purchase was made.

## Your Task
Customer retention can be described as a way to look at how engaged and loyal customers are, that is, whether they continue using the service after their first purchase. In this task we want to see how well Wolt manages to retain its customers month after month based on when users made their first ever purchase.

### Technical assessment
Create visualizations showing the monthly customer retention per product line to communicate the following:
- Cohort based monthly retention for **Retail** product line
- Cohort based monthly retention for **Restaurant** product line

As we’d like to see some of your SQL skills in action, **please solve this task using SQL**. You are free to use any additional tools, for example, SQL package in a Jupyter Notebook, or you can go with PostgreSQL with pgAdmin. Please also share your code, specifying the SQL dialect you’ve used. 

Regarding the visualizations, opt for any tool you wish to use in order to visualize your results in a suitable way. Choose chart types, color palettes and layouts that convey the messages best. 

### Thinking about the next steps
In addition, answer the following:
- What assumptions about the data did you make when creating your retention charts?
- Did you encounter any problems in the data?
- Which additional data sources or business information do you think could be used to improve your solution?

### Deliverables to share with us
1. Put together your visualizations and answers together in English into a presentation,  Jupyter Notebook or similar format.
2. Share your SQL script (mention the dialect used),  which you used to arrive at your results

When your solution is ready, put it as a zip file to Google Drive, Dropbox, OneDrive (or similar). Remember to check permissions! If we cannot access the file, we cannot review your solution. Please don’t store your solution in a public GitHub repository during the application period.
