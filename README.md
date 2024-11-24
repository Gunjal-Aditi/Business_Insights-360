# 📊Business Insights 360📈

## [Live Dashboard](https://bit.ly/3OqCHy5)

## 📑Project Overview

AtliQ Hardware has grown rapidly in recent years, and they have decided to implement Data Analytics using Power BI in their company for the first time to surpass their competitors in the market and make data-driven decisions. This project hopes to answer stakeholders' questions about all aspects, such as Finance, Sales, Marketing, and Supply Chain.

## 👨‍💻Tech Stacks

- SQL
- Power BI Desktop
- Excel
- DAX language
- DAX Studio (for optimizing the report)
- Project charter file

## 🎓Power BI Techniques Learnt

- What all questions should be asked before staring the Project
- Creating calculated columns
- creating measures using DAX language
- Data modeling
- Using Bookmarks to switch between visuals
- Page navigation with buttons
- Using divide function to prevent zero division errors
- creating date table using m language
- Dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting the values in visuals using icons or background color
- Data validation techniques
- Power BI Services
- Publishing reports to Power BI Services
- Setting up Personal Gateway to set up the auto refresh of data
- Power BI App creation
- Collaboration, workspace, access permissions in Power BI Services
- And more 😅

## 💼Business Related Terms

- Gross Price
- Pre-Invoice Deductions
- Post-Invoice Deductions
- Net Invoice Sale
- Gross Margin
- Net Sales
- Net Profit
- COGS - Cost Of Goods Sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## 🏬Company’s Background

AltiQ Hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells computer and computer accessories through three mediums/channel

- Retailers
- Direct
- Distributors

Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis. The company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ Hardware has no option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry. 

<br />Project Kick Off Session, where you should get clear picture of this project and all other questions you have with regards to the project:

### 🧐Dataset **Understanding**

Understanding what data is available will be more helpful while doing analysis. Before jumping on to the analysis get good understanding of what data are available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions  

- gdb041:
    - dim_customer
        - **27** distinct markets (ex India, USA, Spain)
        - **75** distinct customers thorough out the market
        - **2** types of platforms
            - Brick & Motors - Physical/offline store
            - E-commerce - Online Store (Amazon, flipkart)
        - Three channels
            - Retailer
            - Direct
            - Distributors
    - dim_market
        - **27** distinct markets (ex India, USA, spain)
        - 7 sub-zones
        - 4 regions
            - APAC
            - EU
            - nan
            - LATAM
    - dim_product
        - Divisions
            - P & A
                - Peripherals
                - Accessories
            - PC
                - Notebook
                - Desktop
            - N & S
                - Networking
                - Storage
        - There are 14 different categories, Like Internal HDD, Keyboard
        - There are different variants available for the same product
    - fact_forecast_monthly
        - This table is used to forecast the customer’s needs in advance, which can help in
            - Higher customer satisfaction
            - Reduced cost in warehouses for storage purposes
        The table is denormalized by the data engineering team, as it is a data warehouse intended for analytical work.
        - All the date of the month will be replaced by the start date of the month
        - It will have all the column names and in the end, it will have the forecast quantity need of the customer
    - fact_sales_monthly
        - This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of the forecast value.
- gdb056
    - freight_cost
        - This table has details of travel cost and other cost for each market with fiscal year
    - gross_price
        - Has the details of gross prices with product code
    - manufacturing_cost
        - Has the details of manufacturing cost with product code and year
    - Pre_invoice_dedutions
        - Has the details of pre-invoice deductions percentage for each cutomer and year
    - Post_invoice_deductions
        - Post invoice deductions and other deductions details

## 📥Importing Data Into Power BI

- As the database is MySQL in this project, we need to import the datasets from Mysql database to Power BI by providing the Database access credential

## ✨Data Model

- Data modeling plays a vital role and is considered as the basement of the report. All the visuals will be built upon the data model.
-  In this project, we have followed Snowfall data modeling method.

### 🎨Dashboard designing

Based on the mock-ups received as a requirement, the team will start designing the visuals and create measures as and when required

## 🏡Home view

In-Home view, all the views button will be available. Users will land on a specific view page by clicking the button 

- Info
- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View
- Support

## 🎯Project Outcome

This report can be used to make decisions based on the data. Further, it will help answer a number of why questions based on the situation.
