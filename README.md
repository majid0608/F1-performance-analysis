 Formula 1 Power BI Dashboard
By Abdul Majid
A fully interactive multi-page Power BI dashboard analyzing Formula 1 racing data, including drivers, teams, circuits, championships, and geographic trends.
Built using Jolpica F1 API, advanced data modeling, and DAX measures to uncover actionable insights.

📌 Table of Contents
Project Overview

Dataset Source

Objective

Approach

Dashboard Pages

Key Insights

Business Impact

Future Improvements

Files in this Repository

How to Use

Author

📊 Project Overview
This project focuses on analyzing Formula 1 racing data using Power BI to extract insights about:

Driver performance

Team dominance

Race locations & global circuit participation

Season-wise championship trends

Geographic distribution of races

The dashboard helps users explore F1’s history and performance trends in a dynamic, visually appealing way.

🗂️ Dataset Source
Data is collected from:
Jolpica F1 API — an open-source API providing detailed Formula 1 records such as:

Drivers

Teams

Races

Circuits

Championships

Historical season data

🎯 Objective
Analyze Formula 1 data to extract meaningful insights.

Build a multi-page interactive Power BI dashboard using relationships, slicers, and advanced visuals.

Create DAX measures for accurate KPIs such as wins, points, race count, and trends.

Identify top-performing drivers and teams across seasons and countries.

Visualize global circuit participation using maps.

🛠️ Approach
Data Collection

Imported Formula 1 data from the Jolpica F1 API.

Data Modeling

Cleaned, structured, and related all tables for smooth drill-down analysis.

Created primary and foreign key relationships across teams, drivers, races, and circuits.

DAX Implementation

Developed measures for wins, points, total races, average points, season-wise trends, etc.

Dashboard Design

Designed 4 interactive pages including KPIs, maps, charts, and slicers.

Ensured dynamic filtering for team, driver, season, and geography.

📌 Dashboard Pages
1️⃣ Main Dashboard Overview
KPIs: total drivers, teams, races, seasons, leading team by points.

Matrix of Top 10 Teams by wins, points, and ranking.

Bar chart showing Top Drivers by Wins.

2️⃣ Map of Circuit Participation
World map showing number of races hosted by each country.

Region slicer for Europe, Asia, North America, etc.

Insight: Europe hosts the highest number of races historically.

3️⃣ Driver Stats Overview
KPIs: nationality, DOB, races, wins, average points, etc.

Matrix of all drivers with total wins & points.

Area chart showing driver wins per year.

4️⃣ Team Stats Overview
KPIs: total wins, total points, avg points, races.

Line chart: season-wise team performance.

Bar chart: team wins by country.

Donut chart: team nationality distribution.

🔍 Key Insights
Ferrari is the most consistent and dominant team with 240 wins.

Most races occur in Europe (UK, Italy, Germany).

Lewis Hamilton and Michael Schumacher lead in historical wins.

Global participation has expanded to Asia & Middle East in recent years.

Teams show strong geographical bias — European teams dominate championships.

💼 Business Impact
Helps teams benchmark performance and identify competitive gaps.

Shows long-term racing trends to support strategic decisions.

Highlights growth regions for potential race expansion.

Provides a clear picture of team and driver strengths over time.

🚀 Future Improvements
Fastest lap analysis per driver/team.

Driver vs Team comparison visuals.

Start grid vs finish position analysis (overtake skill insights).

Championship prediction model using Python.

