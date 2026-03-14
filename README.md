# digital-marketing-analytics.sql
# Omni-Channel Marketing Intelligence Platform 

## End-to-End Data Engineering & Analytics Pipeline

#### This project demonstrates a complete data lifecycle, from fragmented marketing sources to a centralised Star Schema in Microsoft SQL Server. Using the Medallion Architecture, I turned raw CSV data into high-value "Gold" layer views to support business intelligence, predictive forecasting, and strategic decision-making.


### Project Architecture

#### The project follows a structured flow to ensure data integrity and scalability: 

  1, Data Generation: 6 months of synthetic marketing data (Web, Google Ads, TikTok, Instagram, Email, and E-commerce)
    generated via LLM.
  
  2, Schema Design: Mapping relationships using Draw.io to create an Integration Model and Star Schema.

  3, Data Engineering: Orchestrating a Medallion System (Bronze, Silver, Gold) within SQL Server.

  4, Analytics: Executing exploratory, explanatory analysis, and sales forecasting reports.
  5, Visualisation: Dashboard connected to the SQL Gold Layer and a final executive presentation.

  #### Technical Stack 

   Database: Microsoft SQL Server (T-SQL)
   Modelling: Star Schema/ Dimensional Modelling
   Architecture: Medallion System (Raw-> Cleansed-> Curated)
   Design Tools: Draw.io and Notion
   Visualisation: Tableau
   Reporting: PowerPoint (Executive Summary & Suggestions)

 #### Data Pipeline Stages

  ##### 1, Design & Integration
      Before writing any code, I mapped the ecosystem to ensure all platforms could be 
      joined effectively:
      
        Data Flow Chart: Visualising the movement from local flat files to the visualisation layer.

        Star Schema: Developed a central fact_sales table connected to dimensions, including dim_table, dim_channel, and dim_campaign.

   2, The Medallion System (SQL)
      To maintain a high standard of data quality, the pipeline is split into three distinct layers:
        Bronze (Raw): Direct ingestion of local CSV files into staging tables.
        Silver (Cleansed): Data type standardisation, handling of NULLs, and deduplication across different marketing platforms.
        Gold (Curated): Business-ready Views. This layer aggregates KPIs such as ROAS (Return on Ad Spend), CAC (Customer Acquisition Cost),
                        and Conversion Rates.

   3, Analysis & Insights
      Using the Gold Layer, I performed a deep dive into the 180-day data history:
       Exploratory Data Analysis (EDA):
       Performed initial investigations to discover patterns, spot anomalies, and check assumptions using SQL-based statistical summaries.

       Explanatory Data Analysis: Synthesised the "why" behind the numbers. I translated complex data patterns into clear, actionable insights 
             for stakeholders, focusing on the drivers of marketing performance.
       Forecasting Report: Developed a trend-based forecast for the upcoming month to assist in data-driven budget allocation.
       Executive Presentation: A comprehensive slideshow transalation technical findings into strategic business suggestions.

#### Key Deliverables

####   /Documentation: Draw.io diagrams (Data Flow & ERD).
      /SQL_Scripts: DDL for Star Schema and DML for Medallion transformations.
      /Reports: The Final Forecasting Report and the PowerPoint Presentation.
      /Data: Sample CSV files used for the project.

#### How to Navigate This Repository

    1, Review the Architecture Diagrams in the /Documentation folder.
    2, Execute the SQL Scripts to recreate the Medallion environment. 
    3, View the PowerPoint Presentation for the summary of the marketing insights and the strategic recommendations. 



    ## About Me
    

I am an HND Marketing graduate with a growing focus on marketing data analytics and data-driven decision making.

During my digital marketing studies, I developed a strong interest in how data can improve marketing performance, optimise campaigns, and reveal customer insights.

I am currently building practical skills in:

• Marketing Analytics • Google Analytics 4 (GA4) • SQL for data analysis • Power BI & Power Query • Excel & Google Sheets for marketing reporting • SEO and search performance analysis • PPC and campaign performance tracking

Alongside my marketing education, I previously ran and managed my own business, where I used booking system analytics, social media insights, and customer behaviour data to improve client retention and revenue.

This experience taught me how data can drive real business decisions, even in small companies with limited marketing budgets.

I am now focused on developing my career in marketing analytics, growth marketing, and digital marketing performance analysis.

Currently learning: • Tableau • Advanced SQL for marketing data • Marketing KPI dashboards

I’m particularly interested in opportunities where I can contribute to data-driven marketing teams, e-commerce growth, and marketing performance analysis.
