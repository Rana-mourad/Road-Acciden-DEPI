<h1>Road Car Accident Data Analysis and Reporting</h1>

<h2>Overview</h2>
<p>This project involves the analysis and reporting of a road accident dataset, focusing on accident severity, contributing factors, environmental conditions, and trends over time. The goal is to derive actionable insights that can support road safety improvements and better traffic management strategies.</p>

<h2>Dataset Description</h2>
<p>The dataset includes detailed records of road accidents with the following features:</p>
<ul>
  <li>Accident location and time</li>
  <li>Severity (slight, serious, fatal)</li>
  <li>Environmental conditions (weather, lighting, road surface)</li>
  <li>Vehicle involvement and casualty statistics</li>
  <li>Road types and junction details</li>
</ul>
<p>There are 21 columns in total, and each row represents a unique accident.</p>

<h2>Project Objectives</h2>
<ul>
  <li>Identify accident-prone areas</li>
  <li>Examine the impact of environmental factors on accident severity</li>
  <li>Analyze vehicle types and casualty counts</li>
  <li>Assess the impact of road conditions and junction types</li>
  <li>Support decision-making to enhance road safety policies</li>
</ul>

<h2>Data Preparation and Cleaning</h2>
<ul>
  <li>Handled missing values (e.g., "Unknown", "Not Available")</li>
  <li>Removed duplicate entries</li>
  <li>Standardized formats (dates, numbers)</li>
  <li>Modeled the data into a <strong>star schema</strong> for efficient analysis</li>
  <li>Merged related fields (e.g., location and road attributes) and corrected typos</li>
  <li>Created additional fields like "Accident Hour" and "Rush Hour" for deeper analysis</li>
</ul>

<h2>Data Modeling</h2>

<h3>Fact Table:</h3>
<ul>
  <li><strong>FactAccidents</strong></li>
</ul>

<h3>Dimension Tables:</h3>
<ul>
  <li><strong>DimDate</strong></li>
  <li><strong>DimLocation</strong></li>
  <li><strong>DimRoad</strong></li>
  <li><strong>DimWeather</strong></li>
  <li><strong>DimLightCondition</strong></li>
  <li><strong>DimSurfaceCondition</strong></li>
  <li><strong>DimHazard</strong></li>
  <li><strong>DimVehicleType</strong></li>
</ul>

<p><em>Relationships follow a standard <strong>star schema</strong> with one-to-many relationships from dimensions to the fact table.</em></p>

<h2>Analysis and Key Findings</h2>
<ul>
  <li><strong>Total accidents:</strong> 308K</li>
  <li><strong>Total casualties:</strong> 417.9K</li>
  <li><strong>Seasonal trends:</strong> Most accidents occur in autumn; least in winter</li>
  <li><strong>Light conditions:</strong> Darkness without street lighting increases fatality risk by <strong>3.24×</strong></li>
  <li><strong>Weather impacts:</strong> Flooded roads and windy weather increase accident severity</li>
  <li><strong>Peak times:</strong> Most accidents happen between <strong>8 AM–5 PM</strong>, with a peak at <strong>3 PM</strong></li>
  <li><strong>Junctions:</strong> <strong>T-junctions</strong> are the riskiest</li>
  <li><strong>Surface conditions:</strong> Dry surfaces recorded the highest number of casualties</li>
</ul>
<p><em>More detailed findings are presented in the final report.</em></p>

<h2>Visualizations</h2>
<p>Visualizations were developed using <strong>Power BI</strong>, including:</p>
<ul>
  <li>Accident trends over time</li>
  <li>Casualty statistics by vehicle type</li>
  <li>Impact of environmental conditions on accident severity</li>
  <li>Peak accident times and rush hour analysis</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Power BI</strong>: Data cleaning, modeling, and visualization</li>
  <li><strong>DAX</strong>: Development of advanced measures and KPIs</li>
</ul>
