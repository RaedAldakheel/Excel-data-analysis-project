
Fleet Equipment Inventory Data Analysis

Project Overview

This project demonstrates data cleaning and analysis using government fleet inventory data.

The project is divided into two main stages:
	1.	Cleaning raw data to prepare it for analysis
	2.	Analyzing a prepared dataset using pivot tables to extract insights

⸻

Dataset

Part 1 — Raw Dataset (Cleaning)
	•	Source: Montgomery County public dataset
	•	Format: CSV → converted to Excel (.xlsx)
	•	Purpose: Data cleaning and preparation

Part 2 — Analysis Dataset
	•	Provided as part of the assignment
	•	Used as input for pivot table analysis

⸻

Tools Used
	•	Microsoft Excel (Excel for Web)
	•	Data Cleaning Techniques
	•	Pivot Tables

⸻

Part 1 — Data Cleaning

The raw dataset contained multiple data quality issues that were resolved through the following steps:
	•	Converted CSV file to Excel format (.xlsx)
	•	Adjusted column widths for readability
	•	Removed empty rows
	•	Removed duplicate records
	•	Corrected spelling errors
	•	Removed extra whitespace (double spaces)
	•	Merged incorrectly split department names using Flash Fill
	•	Removed unnecessary columns

⸻

Part 2 — Data Analysis

The analysis was performed using pivot tables on a prepared dataset:
	•	Calculated summary statistics:
	•	Sum
	•	Average
	•	Minimum
	•	Maximum
	•	Count
	•	Created pivot tables to analyze:
	•	Equipment count by department
	•	Equipment class distribution within departments
	•	Department distribution across equipment types

⸻

Key Insights
	•	The Transportation department dominates the fleet, with 1221 out of 1582 vehicles (~77%), indicating a highly centralized fleet management structure.
	•	The fleet is heavily focused on large-scale operational vehicles, with Transit Buses (379 units), Heavy Duty (~290), and Off-Road equipment (~280) being the most common types.
	•	Several departments such as Human Rights, Homeland Security, and Public Information Office have minimal vehicle counts (1–2 units), suggesting they rely on shared transportation resources rather than maintaining independent fleets.
	•	Mid-sized departments like Permitting Services (109) and Sheriff’s Office (85) maintain moderate fleet sizes, reflecting different levels of operational demand.

⸻

Files in This Repository
	•	data/raw_data.xlsx → original uncleaned dataset
	•	data/cleaned_data.xlsx → cleaned dataset
	•	analysis/before_analysis.xlsx → dataset used as input for pivot table analysis
	•	analysis/pivot_tables.xlsx → pivot table analysis results

⸻

Conclusion

This project demonstrates the full data analysis workflow, from cleaning raw data to generating insights using pivot tables. It highlights the importance of data preparation and shows how structured data can reveal patterns in resource allocation and operational priorities.
