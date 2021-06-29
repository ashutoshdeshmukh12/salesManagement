# Sales Management Project
Created a sales management dashboard, which visualizes sales over time, per customer, and per product using Power BI and cleaned the data using SSMS(SQL Server Managment System).

Can view the dashboard here https://bit.ly/3dn8IVu 

## Business Request & User Stories
The business request for this data analyst project was an executive sales report for sales managers. Based on the request that was made from the business we following user stories were defined to fulfill delivery and ensure that acceptance criteria were maintained throughout the project.

| As a (role)  | I want (request / demand) | So that I (user value)  | Acceptance Criteria |
| ------------- | ------------- | ------------- | ------------- |
| Sales Manage  |  To get a dashboard overview of internet sales  | Can follow better which customers and products sells the best  | A Power BI dashboard which updates data once a day  |
| Sales Representative  |A detailed overview of Internet Sales per Customers  | Can follow up my customers that buys the most and who we can sell more to. | A Power BI dashboard which allows me to filter data for each customer  |
| Sales Representative  | A detailed overview of Internet Sales per Products  |  Can follow up my Products that sells the most. | A Power BI dashboard which allows me to filter data for each Produc  |
|Sales Manage  | A dashboard overview of internet sales  | Can Follow sales over time against budget  | A Power Bi dashboard with graphs and KPIs comparing against budget.  |
 

  
## Data Cleansing & Transformation (SQL)
To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using SQL.
One data source (sales budgets) were provided in Excel format and were connected in the data model in a later step of the process.

- DIM_Calendar
- DIM_Customers
- DIM_Products
- FACT_InternetSales

## Data Model
Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.
This data model also shows how FACT_Budget has been connected to FACT_InternetSales and other necessary DIM tables.

![Sales_Model](https://user-images.githubusercontent.com/62536586/123759220-53c93780-d8dd-11eb-9bf2-33a939236730.jpg)

## Sales Management Dashboard
The finished sales management dashboard with one page works as a dashboard and overview, with focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.

![Sales_Dashboard](https://user-images.githubusercontent.com/62536586/123759528-9be85a00-d8dd-11eb-93f1-8c464c2180c3.jpg)
