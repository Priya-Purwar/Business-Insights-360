
# Business Insights 360

Problem Statement

This is a project-based learning course. We will use an imaginary company called AtliQ Hardware and discuss its business model. It is a consumer goods electronics company having operations in various countries. Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights. Also due to the lack of effective analytics the company faced a major loss in Latin America.

Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work.




## Started with these Tasks By Reviewing Mockups

Finance View: Show Profit and Loss Statement to understand financial performance across Markets, Products, Customers etc

Sales View: Show Top/Bottom Customers along with Key Metrics. A matrix would be preferable to understand their performance

Marketing View: Same as Sales View but for Products

Supply Chain View: Reliability, Forecast Accuracy in a view to understand Supply Chain Performance

Executive View: Integrated view of key insights for executives

✒ and then a few requirements came based on Stakeholders' needs!

## My Learnings

•	Created Calculated Columns in Power Query & DAX 

•	Created Different Measures using DAX functions required for visualization

•	Data Modelling 

•	Dashboarding designing techniques

•	End-to-end Power BI project process (Scoping to Deployment)

•	Effective Communication techniques to Business Stakeholders

•	Advanced Power BI tricks

•	Business Function Fundamentals (Finance, Sales, Marketing & Supply chain)

•	Consumer goods business domain knowledge

•	Problem solving mindset

•	Using Bookmarks to switch between two visuals

•	Page navigation with buttons

•	Creating a tooltip for monthly trends

•	Using divide function to prevent zero division errors

•	Creating date table using m language

•	Dynamic titles based on the applied filters

•	Using KPI indicators

•	Conditional formatting the values in visuals using icons or background colour

•	Data validation techniques

•	Publishing reports to PowerBI services

•	Setting up personal gateway to set up the auto refresh of data

•	PowerBI App creation

## Business related terms

•	Fiscal Year

•	Gross price

•	Pre-invoice deductions

•	Post-Invoice deductions

•	Net Invoice sales

•	Gross Margin

•	Net sales

•	Net profit

•	COGS - cost of goods sold

•	YTD - Year to Date

•	YTG - Year to Go

•	Direct

•	Retailer

•	Distributors

•	Consumer


## Company’s back ground

AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

•	Retailers

•	Direct

•	Distributors

Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decisions. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.

## Dataset Understanding

1)	gdb041:

a.	dim_customer

i.	27 distinct markets (ex India, USA, spain)

ii.	75 distinct customers thorough out the market

iii.2 types of platforms

1.	Brick & Motors - Physical/offline store
2.	E-commerce - Online Store (Amazon, flipkart)

iv.	Three channels
1.	Retailer
2.	Direct
3.	Distributors


b.	dim_market

i.	27 distinct markets (ex India, USA, spain)

ii.	7 sub-zones

iii.4 regions
1.	APAC
2.	EU
3.	nan
4.	LATAM

c.	dim_product

i.	Divisions

1.	P & A
a.	Peripherals
b.	Accessories
2.	PC
a.	Notebook
b.	Desktop
3.	N & S
a.	Networking
b.	Storage
ii.	There are 14 different categories, Like Internal HDD, keyboard
iii.	There are different variants available for the same product
d.	fact_forecast_monthly
i.	This table is used to forecast the customer’s need in advance, which can help in
1.	Higher customer satisfaction
2.	Reduced cost in warehouses for storage purpose
ii.	The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
iii.	All the date of the month will be replaced by the start date of the month
iv.	It will have all the column names and in the end it will have the forecast quantity need of the customer
e.	fact_sales_monthly
i.	This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.
2)	gdb056
a.	freight_cost
i.	This table has details of travel cost and other cost for each market with fiscal year
b.	gross_price
i.	Has the details of gross prices with product code
c.	manufacturing_cost
i.	Has the details of manufacturing cost with product code with year
d.	Pre_invoice_dedutions
i.	Has the details of pre invoice deductions percentage for each cutomer with year
e.	Post_invoice_deductions
i.	Post invoice deductions and other deductions details

## Importing Data into Power BI

•	As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential
## Data Modelling

•	Data modelling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.

•	Poor data modelling affects the over all performance of the report.

•	In this project, we have followed Snowfall data modelling method.

## Dashboard Designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

Home view

In Home view, all the views button will be available. User will land on specific view page by clicking the button
•	Info
•	Finance View
•	Sales View
•	Marketing View
•	Supply chain View
•	Executive View
•	Products
•	Support

Info Page

Finance View

Sales View

Marketing View

Supply chain View

Executive View

## Project Outcome

By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.
