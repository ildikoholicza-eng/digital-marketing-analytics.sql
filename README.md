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

   1, Design & Integration
      Before writing any code, I mapped the ecosystem to ensure all platforms could be 
      joined effectively:
      
        Data Flow Chart: Visualising the movement from local flat files to the visualisation layer.

        Star Schema: Developed a central fact_sales tablű        
