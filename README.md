# Global-Payroll-Vendor-Cost-Analysis-Dashboard

# Overview:
This project aims to streamline and automate the process of analyzing payroll vendor costs and generating a global dashboard for ABC Company. The current setup involves multiple analysts collecting data from various regions, which is then manually consolidated and reported on a monthly basis. The project seeks to create a centralized and automated solution that provides real-time global metrics for better cost management.

# Steps:
Task 1: Data Connection from Google Sheet

1.) Share the Google Sheets document with "Anyone with the link can view" permissions.

2.) Navigate to 'File' => 'Publish to the web' in Google Sheets.

3.) Choose 'Entire document' and 'Web page,' then click 'Publish.

4.) In Power BI Desktop, create a new file. Click 'Get data' and select 'Web' as the source. Paste the Google Sheets URL in the data source dialogue box. Choose the required tables from the navigation pane (e.g., 1, 2, 3, 4, & 5) and click 'Load.

5.) Rename the tables in the Power Query Editor to match the Dataset worksheet names. Remove blank rows from the tables. Remove the first column. Set the first row as headers. Repeat these steps for all imported tables.
Click 'Close and apply' in the editor window.

Task 2: Combine Regional Invoice Details Tables

1.) In Power Query view, combine Regional Invoice details tables into one 'Main Table' using Append Query.

2.) Replace all blank/null values in numeric fields with 0.

3.) Perform basic cleaning steps, such as fixing numeric fields to 2 decimal points and replacing null values. Remove '$' signs or replace nulls with 0's only in cost-related columns, if applicable.

Task 3: Data Modelling

Task 4: Visuals

1.) Create slicers for the report

2.) Build a table to show countries by invoice count and the corresponding total Invoice amount.

3.) Create a Donut chart to show invoices by Total amount in the same page

4.) Create a Funnel/Bar chart to show the invoice Total amount by Region in the same page.

5.) Create (Key Performance Indicator) KPI Cards and Table visuals to show the Overall as well as country-wise total amount and total payslips for the latest month and base month 

6.) Create a pie/donut chart to show the vendors by PPC:

# Dashboard
![image](https://github.com/ManikantaBN/Global-Payroll-Vendor-Cost-Analysis-Dashboard/assets/141845485/e9dbf6a3-fbf1-4fe8-a2ae-53648919c088)
