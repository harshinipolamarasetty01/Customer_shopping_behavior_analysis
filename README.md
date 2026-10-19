
📊 Customer Behavior Analysis Project


🎯 Project Overview

This project focuses on building an end-to-end data analytics workflow to analyze retail transaction data, understand consumer purchasing patterns, and extract actionable business insights. The project utilizes Python (Pandas) for data cleaning and feature engineering, MySQL Workbench for relational data warehousing, and Power BI for creating interactive business intelligence dashboards.

🚀 Key Tasks & Contributions


1. Data Cleaning & Feature Engineering (Python Pandas)

• Handled Missing Values: Imputed missing product review ratings by calculating and applying the median rating of their specific product categories.
• Created Categorical Features: Grouped continuous age values into logical demographic segments (Young Adult, Adult, Middle-Aged, Senior) to simplify target audience analysis.
• Standardized Schema: Standardized all data columns to lowercase and snake_case formatting for clean, structured database integration.
• Removed Feature Redundancy: Dropped duplicate and highly correlated columns to optimize processing speed and storage size.

2. Database Management & Warehousing (MySQL)

• Automated Data Migration: Connected the Python pipeline directly to a local MySQL instance using SQLAlchemy to securely migrate data frames into structured relational tables.
• Ranked Category Performance: Developed advanced SQL queries utilizing window functions to dynamically rank and identify the top 3 most purchased items within every category.
• Customer Segmentation: Wrote Common Table Expressions (CTEs) to automatically segment shoppers into New, Returning, and Loyal cohorts based on purchase history.
• Metric Extraction: Wrote targeted queries to evaluate macro-metrics, including total revenue by gender, discount program usage, and high-value subscriber spending habits.

3. Business Intelligence & Dashboarding (Power BI)

• Data Modeling: Structured flat transactional database records into an analytical Star Schema model within Power BI.
• Dynamic Calculations: Utilized Data Analysis Expressions (DAX) to program metrics tracking total sales, customer distribution profiles, and category ratings over time.
• Stakeholder Reports
