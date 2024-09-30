Project Overview :
This project tackles the automation of data cleaning for US household income data using MySQL. The aim is to create a robust and efficient system to clean the dataset by eliminating duplicates, addressing data quality issues, and standardizing entries. This project emphasizes the power of stored procedures, events, and triggers to achieve automated data cleansing.

Objectives :
- Automated Data Cleaning: Implement a streamlined process to remove duplicates, rectify errors, and standardize data.
- Enhanced Efficiency: Ensure the data cleaning process is efficient and can seamlessly handle new data additions.

Automated data cleaning process : 
1. Stored Procedure:
   - Create Clean Table: Establish a new table to store cleaned data.
   - Data Transfer: Copy data from the original table to the cleaned table.
   - Duplicate Elimination: Identify and remove duplicates using the ROW_NUMBER() function.
   - Data Standardization: Correct inconsistencies and typos in the data.

2. Event Scheduling:
   Set up an event to automatically execute the stored procedure every 30 days.
   
3. Trigger Implementation:
   Create a trigger to automatically initiate the cleaning process when new data is added to the original table.
   
Conclusion : 
This project demonstrates the use of MySQL for automated data cleaning, showcasing skills in creating stored procedures, events, and triggers to ensure data consistency and efficiency.
