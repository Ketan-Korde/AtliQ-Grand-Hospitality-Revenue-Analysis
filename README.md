# AtliQ Grands Hospitality-Revenue Analysis
Generating revenue insights by building dashboard in hosptality domain

# Problem Statement
Provide Insights to Revenue Team in Hospitality Domain. 

# Task
You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task.

  1. Create the metrics according to metrics lists.
  2. Create a Dashboard according to the mock-up provided by stakeholders.
  3. Create relevant Insights that are not provided the metric list/mock-up Dashboard.
  
# Data Model Building
![App Screenshot](https://github.com/Ketan-Korde/AtliQ-Grand-Hospitality-Revenue-Analysis/blob/d4cd56a89cf8410659b8bc7dad6418d6b76f6583/Model.PNG)

# Data Cleaning
Each Property_id has a Unique Code. If we take first two digits of id it specifies city name.

For Example :

           16 - Delhi
           17 - Mumbai
           18 - Hyderabad
           19 - Banglore 
           
![App Screenshot](https://github.com/Ketan-Korde/AtliQ-Grand-Hospitality-Revenue-Analysis/blob/d4cd56a89cf8410659b8bc7dad6418d6b76f6583/Capture.PNG)

As shown in figure there were two Atliq Exotica based in Mumbai but in actualityone of the belonged to Delhi according to Property_id.
So it needed to be corrected for further Analysis.

# Dashboard
![App Screenshot](https://github.com/Ketan-Korde/AtliQ-Grand-Hospitality-Revenue-Analysis/blob/bb7932620572335ff946d885ce842d3b43424c6c/Dashboard.PNG)


# Insights Generated
- Mumbai is generating major revenue and Hyderabad is generating low revenue. 

- Instead of generating low revenue Delhi & Hyderabad have more ratings and occupancy rate.

- Majority of bookings coming from source called others. Needs to identify what source it is.

- Occupancy rate is higher in Weekends and Presidential Class compare to Weekdays.

- Highest revenue was generated in month of May and then it dropped in June but somewhat recovered in July so needs to identify what was done differently in July compare to June to generate more revenue. 

- Luxury category have more bookings than Business category.

# Lessons Learned

- How to builld Data Model.
- Creating basic formulas using DAX.
- Creating Dashboards in PowerBI.
           

