README – Budget Management App
Overview
This budgeting app was built using Glide, a platform that links directly to Google Sheets. It allows users to track their expenses, view how much they’ve spent in different categories, and manage their monthly budget limit.
The goal of this project was to create a working prototype that demonstrates key app functionality without writing traditional code, while still meeting user requirements, usability, and data handling criteria.
Main Features
Add Expense
 Users can add new expenses by entering a title, amount, date, and category through a simple form. All entries are saved directly to a connected Google Sheet.


View Expenses
 A list screen shows all recorded expenses with category labels, amounts, and dates.


Spending Summary 
 A bar chart shows how much the user has spent in each category, making it easy to spot where the most money is going.


Monthly Budget Screen
 Displays a static monthly budget (default = £1000) that can be updated manually. Helps users see how their total spending compares to their budget goal.

User System
Predefines users with names, roles and profile pictures and simulates multi-user functionality



Tools Used
Glide 
 Used to build and design the app interface, connect forms, display data, and create visual components like the bar chart.


Google Sheets
 Serves as the data backend. Expenses and budget values are stored and synced in real time between the sheet and the app.



Navigation Structure
Tab Name
Purpose
Expenses
View list of submitted expenses
Add Expense
Submit new expense via form
Spending Summary
View total spending by category (chart)
Budget
See monthly budget and current limit


Example Data Used
Title
Amount
Date
Category
Rent
600
2025-07-01
Housing
Coffee
3.5
2025-07-30
Food
Transport
20
2025-07-10
Travel
Gym Membership
25
2025-07-15
Health
Netflix
10
2025-07-08
Entertainment


Live App Link
https://budget-app-refferal.glide.page
Demo Video Download
https://github.com/upstudent987/Budget-App-Refferal/raw/refs/heads/main/Budget%20Management%20App%20Demo.mov



Limitations
Currently designed as a prototype, no user login or authentication


Budget and expenses are updated manually


Does not include recurring logic or advanced filtering yet




