# Carbon-Footprint-Dashboard-Remote-IT-Teams
-------------------------------------------------------------------------------------------------
# Project Overview
This Power BI dashboard visualizes the environmental benefits of remote work by tracking CO₂ emissions saved across different departments and cities in an IT organization. The goal is to help companies monitor sustainability efforts and make informed decisions to reduce their carbon footprint.

# Key Objectives
--------------------
Analyze CO₂ savings from remote teams by department, city, and month.

Highlight positive or negative emission trends using conditional formatting (Green = positive savings, Red = increased emissions).

Support data-driven environmental strategy through intuitive dashboards.

# Data Cleaning & Preparation
---------------------------------------
1.Removed duplicate and blank rows in Power Query.

2.Converted date fields to proper formats.

3.Ensured numerical fields like Distance, EmissionFactor, and CO2 Saved are in the correct data type.

# Created calculated columns for:

CO2 Saved = Distance × Emission Factor

Trend analysis (Month-over-month)

# DAX Measures & Calculations
--------------------------------------
Total CO2 Saved

Avg CO2 Saved per City

CO2 Trend (to highlight increase/decrease)

Conditional coloring rules (Red if emissions increased, Green if reduced)

# Dashboard Features
------------------------------
KPI Cards for total CO₂ saved, average savings, and monthly targets

Bar Chart: CO₂ saved per department

Donut Chart: Emission source breakdown (e.g., commute, equipment)

Line Chart: Monthly emission trends

Slicers: Department, City, Month

Footer and Branding with developer’s name

Eco-friendly color theme (green, blue, earthy tones)

# Tools & Skills Used
----------------------
Power BI Desktop

Power Query for data transformation

DAX for advanced calculations

Data modeling

Visualization & storytelling

#  File Structure
text
Copy
Edit
 Carbon_Footprint_Dashboard_Remote_Teams
│
├── Remote_CO2_Data.xlsx       # Cleaned dataset
├── CarbonFootprintDashboard.pbix   # Power BI dashboard file
└── README.md                  # Project overview and usage

 # Key Takeaways
 ----------------------------
Remote work has led to significant CO₂ emission reductions in IT departments.

Teams like DevOps and Infrastructure have higher environmental impact due to heavier equipment usage.

Dashboard helps organizations identify where to improve and track progress toward sustainability goals.

