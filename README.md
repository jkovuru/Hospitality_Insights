# Hospitality_Insights

## Project Overview

AtliQ hotels have experienced significant growth in recent years and have made the strategic decision to introduce Power BI-based data analytics within their organization. The objective is to outperform competitors in the market and enable data-driven decision-making. This initiative aims to address stakeholder inquiries across various domains including finance, sales, marketing, and supply chain management.

[Live Report Link](https://app.powerbi.com/groups/me/reports/4c01b90d-02ed-4496-bc78-542a97b6c39b/ReportSection8b3607d3a9eb5c7e678f?experience=power-bi)
## Technology used

- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)
- Project charter file

## PowerBI techniques Learnt


- What inquiries should be addressed prior to initiating the project?
- Formulating calculated columns
- Crafting measures using DAX language
- Data modeling strategies
- Utilizing Bookmarks for toggling between two visuals
- Implementing page navigation through buttons
- Employing the divide function to prevent division errors by zero
- Generating date tables using the M language
- Implementing dynamic titles based on applied filters
- Incorporating KPI indicators
- Applying conditional formatting to visualize values using icons or background colors
- Implementing data validation techniques
- Utilizing Power BI services
- Deploying reports to Power BI services
- Establishing a personal gateway for automated data refresh
- Creating Power BI apps
- Managing collaboration, workspaces, and access permissions in Power BI services
- And many more 

## Business terms
- Total Revenue
- Total bookings
- Cancellation rate
- Revenue Per Available Room (RevPAR)
- Daily Sellable Room Nights (DSRN)
- Average Daily Rate (ADR)
- Daily Utilized Room Nights (DURN)
- Daily Booked Room Nights (DBRN)


### Questions to ask before starting with dashboard

- What is the primary goal behind developing this Power BI dashboard?
- How will the success of this project be gauged?
- What is the projected timeline for the project's completion?
- Are stakeholders anticipating a preview before the official release?
- What are the expectations of stakeholders regarding the outcomes of this project?
- What concerns do stakeholders harbour regarding the development of this dashboard?
- Who will utilize this dashboard and for what purposes?
- What are the stakeholders' expectations upon the project's completion?
- What potential challenges might arise during the project's development?
- What data and resources are necessary for constructing this dashboard?
- Have stakeholders provided any input regarding the design and layout of the dashboard?
- Following the kickoff meetings, the data engineering team has provided the requested data to the data analytics team. Let's delve into it.

### Dataset **Understanding.**

Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions  



## Importing data into PowerBi

- As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential

## Data Model

- Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
- Poor data modeling affects the over all performance of the report.
- Following Good practices of data modeling is must. 
- In this project, we have followed Snowflake data modeling method.

<img src="(https://github.com/jkovuru/Hospitality_Insights/blob/main/Report/data%20model.png)" class="center">

### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

## Home view

In Home view, all the views button will be available. User will land on specific view page by clicking the button 

- Executive View
- Products
- Customers
- Map

## Overall Report

![Overall Report](https://app.powerbi.com/groups/me/reports/4c01b90d-02ed-4496-bc78-542a97b6c39b/ReportSection8b3607d3a9eb5c7e678f?experience=power-bi)


## Project Outcome

By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.
