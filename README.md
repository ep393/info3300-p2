# project2-info3300
Introduction
Project Aim: Interactive data visualization using the "Daily Temperature of Major Cities" dataset from Kaggle.
Purpose: To present the continuous rise in Earth's average temperature as a narrative on global warming.
Method: Utilizing color to represent temperature trends over time, making climate change comprehensible and accessible.

Data Description
Source: Kaggle's “Daily Temperature of Major Cities” dataset (https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities/data)
Variables: Region, Country, City, Month, Day, Year, AvgTemperature.
Data Processing: Monthly and yearly average temperatures calculated, ‘Day’ column removed, ‘YearMonth’ column added for concise representation.
Additional Data: A topoJSON file for geographic mapping (https://geojson-maps.ash.ms/)

Visual Design Rationale
Geographic Representation: Cities located using latitude and longitude on a Mercator map projection.
Color Usage: Temperature variation shown using a color scale – warmer temperatures in red, cooler in blue.
Data Aggregation: Country-level averages from city data to improve readability.
Dynamic Elements: Date display and global average temperature indicators, sliders for temporal navigation, radio buttons for view switching.

Interactive Elements
Sliders and Radio Buttons: For navigating through months and years and switching between views.
Modal Window: Detailed city-level temperature information on country selection.
Tooltips: Show average temperature for a country on hover.

The Story
Narrative Focus: Earth's rising average temperature from 1995 to 2019.
Visual Impact: Color shifts intuitively convey the warming trend.
Objective: Engaging viewers in the reality of global warming at different geographical scales.

Team Contributions
Team Members: Julius Enarsson Enestrom, Bradley Paliska, Karim Pareja, Emir Polat.
Roles: Included brainstorming, dataset exploration, data preprocessing, coding, presentation, and report writing.

Project Timeline
Duration: Over 3 weeks, averaging 7 hours per week.
Activities: Included organization, brainstorming, visualization creation and improvement, analysis, and report writing.
