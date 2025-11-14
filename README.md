# 🏎️ Formula 1 Power BI Dashboard Analysis

## Project Description

This project presents an interactive **Formula 1 analytics dashboard** created using Power BI.
By leveraging historical F1 data—including drivers, teams, circuits, races, and championship statistics—the dashboard provides an intuitive view of performance trends and racing patterns across seasons and countries.
It aims to simplify the exploration of F1 history and highlight key insights about team dominance, driver achievements, and track distribution across the globe.

---

## Objective

The primary objective of this project is to create a visually rich, data-driven dashboard that helps users:

* Understand team and driver performance over time
* Analyze the geographical distribution of Formula 1 circuits
* Study race trends, win patterns, and seasonal performance
* Explore data interactively using dynamic filtering and DAX-based measures

---

## Methodology

### **1. Data Collection**

* Source: **Jolpica F1 API**, an open-source dataset containing complete details about drivers, teams, races, circuits, and championships.

### **2. Data Preprocessing**

* Cleaned and structured raw tables
* Established relationships between drivers, races, teams, and circuits
* Removed duplicates and standardized fields for seamless model integration

### **3. Data Modeling**

* Built a star-schema-based model in Power BI
* Created relationships using primary and foreign keys
* Added calculated columns and measures for points, wins, races, and consistency trends

### **4. Visualization Development**

* Developed a **multi-page interactive dashboard** including:

  * Main Overview
  * Geographic Circuit Participation
  * Driver Stats
  * Team Stats

### **5. DAX Measures**

* Implemented DAX for:

  * Total Wins
  * Total Points
  * Average Points
  * Race Count
  * Season-wise performance trends

---

## Dashboard Features

### **1️⃣ Main Dashboard Overview**

* KPIs for total drivers, races, seasons, teams
* Leaderboard for top-performing teams
* Bar chart showing drivers with highest career wins

### **2️⃣ Circuit Participation Map**

* World map visualization of countries hosting F1 races
* Highlights regional dominance (Europe leading)
* Region-specific filtering through slicers

### **3️⃣ Driver Stats Dashboard**

* KPIs reflecting driver details and performance
* Matrix for comparing all drivers
* Area charts showing win patterns across years

### **4️⃣ Team Stats Dashboard**

* KPIs for team performance
* Season-wise performance line charts
* Wins by country (bar chart)
* Donut chart showing nationality distribution of teams

---

## Results

* **Ferrari emerged as the most dominant team**, leading race wins and overall points
* **Europe hosts the majority of circuits**, with the UK and Italy being top contributors
* **Lewis Hamilton and Michael Schumacher** lead in career wins
* **Performance trends indicate rising competitiveness** post-2010
* Driver and team performance shows strong dependence on race location

---

## Conclusion

This project demonstrates the power of **interactive visualization** in understanding complex sports data.
The dashboard delivers a comprehensive view of Formula 1 history while offering valuable insights into driver achievements, team dominance, and global racing patterns.

It serves as a dynamic exploration tool for fans, analysts, and stakeholders interested in performance evaluation and trend monitoring.

---

## Future Directions

* Integrate **fastest lap** and **pit stop analytics**
* Add **starting grid vs finishing position** comparison
* Include **driver vs team performance benchmarking**
* Combine Python predictive analytics for **race outcome forecasting**
* Enhance visuals with more granular season-wise interaction

---

## Tools & Technologies

* **Software:** Power BI Desktop
* **Language:** DAX (for calculations)
* **Data Source:** Jolpica F1 API
* **Modules Used:** Data Modeling, KPIs, Maps, Bar/Line Charts, Slicers

---

## Author

**Abdul Majid**
Power BI | Data Analytics | SQL | Python
*https://github.com/majid0608*

---


