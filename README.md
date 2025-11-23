#Uber Bussiness Analysis Using Power BI
  
##Agenda :
•	Project Overview
•	Data Source
•	Data Preparation
•	Dashboard Visualization

##Project Overview :
This project aims to analyze Uber ride data to understand various aspects of ride usage, such as the distribution of rides across different categories, purposes, months, days, and times. The analysis is visualized using a dashboard to provide insights into ride patterns and help make data-driven decisions.

##Data Source :
•	Dataset Name:	 Uber Dataset
•	Source: 		Kaggle
•	File Type:		Excel File
•	Total Records:	150000
•	Total Columns:	19

##Data Preparation:
•	Imported dataset into Power BI Desktop from Excel file.
•	Performed data cleaning using Power Query Editor to ensure accuracy and consistency.
•	Checked and removed null values in columns.
•	Created calculated columns and DAX measures for :
  Customer count, Booking value, Total Distance, Avg Distance, Regular_rides, Lost_Bookings, Return_rides, Completed_Bookings etc..
•	Validated the dataset to ensure no duplicates or mismatched entries.
•	Loaded the cleaned data into the Power BI Model for visualization and data analysis.

##Dashboard Visualizations :
##1. Overview Page Dashboard:
     • KPI’s (Key Performance Indicators) :
       Completed Bookings
       Lost Bookings
       Revenue
       Total Distance
       Average Distance
    •	Visuals Used :
       Area Chart 	:DataAxis(Amount,Monthly) vs Completed Bookings.
       Clustered Column Chart :   DataAxis(Amount,Monthly) vs Booking value.
       Clustered bar Chart: Vehicle Type vs Revenue.
       Cards : Top Drop and Pickup Location based on booking count.
    
##2. Ratings :
     Avg Rider Ratings.
     Avg Driver Ratings.

##3. Vehicle Page Dashboard: 
   • Visuals Used:
     Table : Detailed Information by Vehicle.
     Image, Vehicle, Customer_count, Revenue, Completed Bookings, Cont%, Bookings by Month.

##4. Revenue Page Dashboard:
   • Visuals Used :
     Clustered bar Chart: Vehicle Type vs Revenue.
     Clustered bar Chart: Customer ID vs Revenue.
     Clustered Column Chart :   Payment method vs Revenue.
     Area Chart 	:Amount &Monthly Revenue  vs Completed Bookings.

##5. Rider Page Dashboard:
  •	Visuals Used :
    Multi-row Card : Cancel Rides by Reasons.
    Clustered bar Chart: Count of Customer ID vs Payment method.
    Table : Detailed Information by Vehicle.(Cust_Id, Revenue, Lost&Completd Bookings, Total&Avg distance, First rider, Return rider, Regular rider.
    Area Chart 	:Amount&Quaterly Customer vs Customer Count.

##6. Location Page:
  •	Visuals Used :
    Clustered bar Chart: Vehicle Type vs Total Distance.
    Clustered bar Chart: Booking Count  vs Pickup Location.
    Matrix : Busy time slots ( rows : Time_slots, Columns: weekdays, values: Booking count ).
    Area Chart 	:Monthly  vs Total Distance.


 
 
 
 

 
 












