Road Car Accident Data Analysis and Reporting

Overview

This project involves the analysis and reporting of a road accident dataset, focusing on accident severity, contributing factors, environmental conditions, and trends over time. The goal is to derive actionable insights that can support road safety improvements and better traffic management strategies.

Dataset Description

The dataset includes detailed records of road accidents with the following features:

-Accident location and time
-Severity (slight, serious, fatal)
-Environmental conditions (weather, lighting, road surface)
-Vehicle involvement and casualty statistics
-Road types and junction details
There are 21 columns in total, and each row represents a unique accident.

Project Objectives

-Identify accident-prone areas.
-Examine the impact of environmental factors on accident severity.
-Analyze vehicle types and casualty counts.
-Assess the impact of road conditions and junction types.
-Support decision-making to enhance road safety policies.

Data Preparation and Cleaning

-Handling missing values (e.g., "Unknown", "Not Available").
-Removing duplicate entries.
-Standardizing formats (dates, numbers).
-Normalizing and modeling the data into a star schema for efficient analysis.
-Merging fields (e.g., location and road attributes) and correcting typos.
-Creating additional fields like "Accident Hour" and "Rush Hour."

Data Modeling

Fact Table:

-FactAccidents

Dimension Tables:

-DimDate
-DimLocation
-DimRoad
-DimWeather
-DimLightCondition
-DimSurfaceCondition
-DimHazard
-DimVehicleType
Relationships follow a standard star schema with one-to-many relationships from dimensions to the fact table.

Analysis and Key Findings

-Total accidents: 308K
-Total casualties: 417.9K
-Seasonal trends: Most accidents in autumn, least in winter.
-Light conditions: Darkness without street lighting increases fatality risk by 3.24×.
-Weather impacts: Flooded roads and windy weather increase severity.
-Peak times: Most accidents between 8 AM–5 PM, especially 3 PM.
-Junctions: T-junctions are the riskiest junction type.
-Surface conditions: Dry surfaces recorded the highest casualties.
More detailed findings are presented in the final report.

Visualizations

Visualizations were implemented using Power BI, including:

-Accident trends over time
-Casualty statistics by vehicle type
-Impact of environmental conditions on accident severity
-Peak accident times and rush hour analysis

Technologies Used

Power BI (for cleaning , data modeling and visualization)
DAX (for advanced measures and KPIs)
