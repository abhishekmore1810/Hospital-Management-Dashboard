# Hospital Management Dashboard

# Project Overview

The Hospital Management Dashboard is a complete Data Analytics project built using Excel, SQL Server, and Power BI to analyze hospital operations, patient records, doctor specialization, billing details, and payment performance.

This project helps hospital management track important KPIs such as total patients, doctor distribution, payment collection, pending payments, disease trends, and state-wise financial performance for better decision-making.

# Project Objective

The main objective of this project is to analyze hospital management data and create an interactive dashboard that helps:

- Monitor patient and doctor records efficiently
- Track hospital revenue and pending payments
- Analyze doctor specialization and department workload
- Understand patient disease patterns
- Compare payment methods and billing performance
- Identify top-performing states financially

This dashboard helps management make faster, data-driven decisions and improve operational efficiency.

# Business Problem
Hospitals manage a large amount of patient, doctor, billing, and treatment data daily.

Without proper analysis:

- Patient records become difficult to manage
- Pending payments increase
- Revenue tracking becomes unclear
- Doctor workload distribution is hard to monitor
- Disease trends remain unnoticed
- Management cannot make quick strategic decisions

Manual reporting is time-consuming and often leads to errors.

# Solution

To solve these problems, a centralized Hospital Management Dashboard was created using Power BI by integrating cleaned Excel data with SQL Server.

This solution provides:

- Real-time visual insights
- Automated KPI monitoring
- Easy filtering using slicers
- Better payment tracking
- Doctor specialization analysis
- Disease and treatment trend analysis
- State-wise financial comparison

This improves reporting accuracy and saves management time.

# Tools Used
- Microsoft Excel → Data Cleaning
CSV Files → Data Import Format
- SQL Server Management Studio (SSMS) → Database Creation & Querying
- Power BI → Dashboard Development & Visualization

# Step-by-Step Project Workflow
# Step 1: Excel Data Cleaning
# Tasks Performed
1. Checked Duplicates and Blank Cells
Removed duplicate records
Identified missing values
Ensured data consistency
2. Verified Column Formats

3. Converted Excel Files into CSV Format
Saved cleaned Excel sheets as .csv files
CSV format improves compatibility with SQL Server import

# Step 2: SQL Server Database Creation
# Tasks Performed
1. Created Hospital Database
2. CREATE DATABASE hospital;
3. USE hospital;
4. Imported CSV Files into SQL Server
Used SQL Server Import Wizard
Imported cleaned CSV files into database tables
3. Performed SQL Validation
Verified successful data import
Checked row counts
Validated relationships between tables

This created a structured database for Power BI connection.

# Step 3: Power BI Dashboard Development
# Dashboard Creation Process
1. Connected SQL Server Database to Power BI
Imported hospital database tables from SQL Server
2. Add Dashboard Title

Created a text box:
Hospital Management Dashboard

3. Inserted Doctor Logo
Added doctor logo on the top-left corner for professional design

4. Add Interactive Slicers

 Created slicers for:
- Doctor Name
- State
- City
- Treatment Given
- Registration Date

These allow dynamic filtering of the dashboard.

5. Create KPI Cards

Built KPI visuals for:

- Total Patients
- Average Age of Patients
- Total Doctors
- Total Amount
- Amount Paid
- Amount Pending

These KPIs provide quick business insights.

# Doctors by Specialization
Visualization Used:

Stacked Column Chart

Data Used:
Specialization and 
Doctor Name (Distinct Count)

Purpose:

To identify the number of doctors available in each specialization.

# Payment Mode Analysis
Visualization Used:

Donut Chart

Data Used:
Payment Mode and 
Total Bill Amount
Purpose:

To analyze how patients make payments:

- UPI
- Cash
- Card
- Insurance

# Disease-wise Patient Analysis
Visualization Used:

Stacked Bar Chart

Data Used:
Disease and 
Patient ID Count

Purpose:
To identify the most common diseases among patients.

# State-wise Financial Analysis
Visualization Used:

Stacked Bar Chart

Data Used:
State,
Total Bill Amount,
Amount Paid,
Pending Amount

Purpose:

To analyze top 10 states by:

- Revenue generation
- Payment received
- Pending collections


# Created Home Page Navigation
# Tasks Performed
- Added a new page
- Inserted hospital room image
- Added page navigation buttons
- Created Home Tab for better dashboard experience

This improves dashboard usability and presentation.

# Key Insights from Dashboard Analysis
1. Financial Insights
- Total hospital billing exceeds expected collection efficiency
- Pending payments are significantly high
- Some states have strong revenue but also high pending collections

2. Operational Insights
- General Medicine has the highest number of doctors
- Certain specializations may need better staffing balance

3. Patient Insights
- Fracture, Flu, and Diabetes are among the most common diseases
- Disease trends help in resource planning

4. Payment Insights
- UPI and Cash are major payment modes
- Insurance-based payments can be improved for better coverage

5. Final Business Impact
This dashboard helps hospital administrators:

- Improve revenue collection
- Reduce pending payments
- Optimize doctor allocation
- Improve patient service planning
- Monitor hospital performance effectively
- Make faster strategic decisions using data

# Conclusion

The Hospital Management Dashboard transforms raw hospital data into actionable business insights using Excel, SQL, and Power BI.

It demonstrates strong skills in:

- Data Cleaning
- SQL Database Management
- Business Intelligence
- Dashboard Design
- Data Storytelling
