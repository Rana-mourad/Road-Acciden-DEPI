Road Car Accident Data Analysis and Reporting

Overview

This project involves the analysis and reporting of a road accident dataset, focusing on accident severity, contributing factors, environmental conditions, and trends over time. The goal is to derive actionable insights that can support road safety improvements and better traffic management strategies.

Dataset Description

The dataset includes detailed records of road accidents with the following features:

1-Accident location and time
2-Severity (slight, serious, fatal)
3-Environmental conditions (weather, lighting, road surface)
4-Vehicle involvement and casualty statistics
5-Road types and junction details
There are 21 columns in total, and each row represents a unique accident.

Project Objectives

1-Identify accident-prone areas.
2-Examine the impact of environmental factors on accident severity.
3-Analyze vehicle types and casualty counts.
4-Assess the impact of road conditions and junction types.
5-Support decision-making to enhance road safety policies.

Data Preparation and Cleaning

1-Handling missing values (e.g., "Unknown", "Not Available").
2-Removing duplicate entries.
3-Standardizing formats (dates, numbers).
4-Normalizing and modeling the data into a star schema for efficient analysis.
5-Merging fields (e.g., location and road attributes) and correcting typos.
6-Creating additional fields like "Accident Hour" and "Rush Hour."

Data Modeling

Fact Table:

1-FactAccidents

Dimension Tables:

1-DimDate
2-DimLocation
3-DimRoad
4-DimWeather
5-DimLightCondition
6-DimSurfaceCondition
7-DimHazard
8-DimVehicleType
Relationships follow a standard star schema with one-to-many relationships from dimensions to the fact table.

Analysis and Key Findings

1-Total accidents: 308K
2-Total casualties: 417.9K
3-Seasonal trends: Most accidents in autumn, least in winter.
4-Light conditions: Darkness without street lighting increases fatality risk by 3.24×.
5-Weather impacts: Flooded roads and windy weather increase severity.
6-Peak times: Most accidents between 8 AM–5 PM, especially 3 PM.
7-Junctions: T-junctions are the riskiest junction type.
8-Surface conditions: Dry surfaces recorded the highest casualties.
More detailed findings are presented in the final report.

Visualizations

Visualizations were implemented using Power BI, including:

1-Accident trends over time
2-Casualty statistics by vehicle type
3-Impact of environmental conditions on accident severity
4-Peak accident times and rush hour analysis

Technologies Used

Power BI (for cleaning , data modeling and visualization)
DAX (for advanced measures and KPIs)
