# EV_Domain_PowerBI_Dashboard_Report
## Project Overview
AtliQ Motors is an automotive giant from the USA specializing in electric vehicles (EV). In the last 5 years, their market share rose to 25% in electric and hybrid vehicles segment in North America. As a part of their expansion plans, they wanted to launch their bestselling models in India where their market share is less than 2%. Bruce Haryali, the chief of AtliQ Motors India wanted to do a detailed market study of existing EV/Hybrid market in India before proceeding further. Bruce gave this task to the data analytics team of AtliQ motors and I am the data analyst working in this team. To study the Indian EV market I was provided with sample data and few research questions to work on the following tasks:
 1. Begin your analysis by referring to the ‘primary_and_secondary_questions.pdf’.
 2. Design a dashboard with your metrics and analysis. The dashboard should be self-explanatory and easy to understand.

I worked on this project by following the Codebasics Data Analyst Bootcamp, Link to the course is [here](https://codebasics.io/bootcamps/data-analytics-bootcamp-with-practical-job-assistance).

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiYmQ5MmQ1NTgtNGI0OS00ODllLWIwZDAtZjI5OGVkNTI0MjRkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=ba99e4a6e71afa037759)

Visit My Presentation Video on LinkedIn -> <a href="https://www.linkedin.com/posts/atharvasutar_datascience-powerbi-activity-7246149581787348993-kgyX?utm_source=share&utm_medium=member_desktop" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/posts/atharvasutar_datascience-powerbi-activity-7246149581787348993-kgyX?utm_source=share&utm_medium=member_desktop" height="30" width="40" /></a>

## Tech stacks
* Microsoft Power Bi Desktop
* Microsoft Excel
* ## PowerBI techniques Learnt
* What are all the questions that should be asked before starting the project
* Creating calculated columns
* Creating measures using the DAX language
* Data modeling
* Page navigation with buttons
* Using the divide function to prevent zero division errors
* Using KPI indicators
* Data validation techniques
* PowerBi services
* Publishing reports to PowerBi services
* And many more 😅
## Business related terms
* EV Sales
* Market Share
* Compounded Annual Growth Rate (CAGR)
* Market Learder
* Penetration Rate
* Projected Sales
* Penetration Rate Chage Over Years
## Company’s Background
AltiQ Grands is a hotel chain based in India that has grown vastly recently. It is a company that operates in the following categories:
* Luxury
* Business
AtliQ Motors is a major automotive company from the USA that specializes in electric vehicles (EVs). Over the past 5 years, their market share in the electric and hybrid vehicle segment in North America has increased to 25%.

Project kick-off session, where you should get clear of what and why this project is and all other questions you have with regards to the project

### Questions to ask before starting with the dashboard
* What is the objective of building this PowerBi dashboard?
* In what terms the success of this project will be measured?
* What will be the deadline for the project?
* Do the stakeholders expect a pre-view before the actual release?
* What are all the hopes stakeholders have out of this project?
* What are all the fears the stakeholders have in terms of building this dashboard?
* Who will be using this dashboard and for what purpose?
* What are all expectations the stakeholders have, by the completion of this project?
* What can go wrong while building this project?
* What are all the resources/ data needed to build this dashboard?
* Is there any input from stakeholders in terms of design and views of the dashboard?
After the project kick-off meetings, the data engineering team has given the data as per the request of the data analytics team, let’s explore them.

### Dataset Understanding
Understanding what data is available will be more helpful while doing analysis. Before jumping on to the analysis get a good understanding of what is the available data.

Dimension table: It will have static data like details of customers and products

Fact table: It will have the data about the transactions

Column Info for electric_vehicle_sales_by_state.csv:

- date: The date on which the data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- state: The name of the state where the sales data is recorded. This indicates the geographical location within India.
- vehicle_category: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- electric_vehicles_sold: The number of electric vehicles sold in the specified state and category on the given date.
- total_vehicles_sold: The total number of vehicles (including both electric and non-electric) sold in the specified state and category on the given date.

Column Info for electric_vehicle_sales_by_makers.csv:

- date: The date on which the sales data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- vehicle_category: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- maker: The name of the manufacturer or brand of the electric vehicle.
- electric_vehicles_sold: The number of electric vehicles sold by the specified maker in the given category on the given date.

Column Info for dim_date.csv:

- date: The specific date for which the data is relevant. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- fiscal_year: The fiscal year to which the date belongs. This is useful for financial and business analysis.
- quarter: The fiscal quarter to which the date belongs. Fiscal quarters are typically divided as Q1, Q2, Q3, and Q4.

## Importing Data into PowerBi
* As the data is in CSV files, we need to simply import the folder in Power BI and manipulate it in Power Query.
## Data Model
* Data modeling plays a vital role and is considered as the basement of the report. All the visuals will be built upon the data model.
* Poor data modeling affects the overall performance of the report.
* Following Good practices of data modeling is a must.
* In this project, we have followed the Snowflake data modeling schema.
![Database Model](https://github.com/user-attachments/assets/9fc6fac2-9275-43c7-8778-43bbb1a00baa)


Dashboard designing
I, have given an EV touch to the dashboard with the colour scheme of AtliQ Logo and created all the measures myself, no requirements were provided. 

Home Page
Home page is a view where all the buttons are provided to navigate to other views and a small description about the dashbooard.

* Competitor's Performance
* State's Performace

## Home Page
![Home Page](https://github.com/user-attachments/assets/53f84c55-89ee-47a8-9b5c-de5e663b0697)

## Competitor's Performance
![Competitor's Performance](https://github.com/user-attachments/assets/b903387d-3772-42c8-80a0-c640aeb61941)

## State's Performance
![State's Performance](https://github.com/user-attachments/assets/f10d34f1-f642-4aa0-a2f7-44c5da724ec8)

## Project Outcome
1. Penetration rate of EVs is only 3.6% among people.
2. The EV industry is growing very rapidly in India with stunning rate of 94% per year.
3. Almost 1.02 Million EVs are sold from FY 2022 to 2024.
4. Most of the EVs sold in the market are 2-Wheelers.
5. 2-Wheeler Market Leader is OLA Electric and 4-Wheeler is Tata Motors. 

## My Suggestions
1. Indian Market is price-sensitive, with electric two-wheelers priced between ₹80,000 to ₹1,20,000 and electric four-wheelers priced between ₹6.99 lakh to ₹15 lakh. So, AtliQ need to launch their vehicles between these price segments.
2. AtliQ should draw inspiration from industry leaders like OLA Electric, TVS, Ather, Tata Motors, and Mahindra & Mahindra to increase market share and make a substantial impact.
3. AtliQ should consider launching vehicles in tier-1 cities of Karnataka, Maharashtra, Delhi, Kerala, Gujarat, and Goa due to high EV adoption rates and well-established infrastructure.
