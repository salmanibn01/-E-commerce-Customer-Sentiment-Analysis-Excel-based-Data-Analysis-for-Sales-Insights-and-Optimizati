## Excel_-Data_Analysis-Project
-- E-comerce Customer Sentiment Analysis Using Microsoft Excel  

## Data Cleaning  
-- Changing the 'M' to 'Men' and 'W' to 'Women' in the 'Gender' column
Press Ctrl+F, Find and Repalce box appears, Find 'M' and Replace it with 'Men'  
# Important: Tick 'Match the Entire Cell Content' to change only the desired columns 
Follow the same procedure to change 'W' to 'Women'
-- Cleaned the cells from the QTY (quantity) column using the same proceudre
'One' to 1 and 'Two' to 2

## Data Processing
-- Defining the relationship between gender and age using IF formula (We are creating an age bucket)
First create a new clomun called Age Group
Use of IF function 
=IF(E2>=50, "Senior", IF(E2 >=30, "Adult","Teenager"))

-- Determining the month with highest sales 
Add a new table called Month
-- Extracting the months from the dates using TEXT function
=TEXT(G2,"mmm")

## Data Analysis
Showing Sales and Orders in the same chart Using pivot table
Drag amount to Values for total sales
Drag Order ID to Values for total number of orders
Drag Month to rows as we want it on the basis of months



