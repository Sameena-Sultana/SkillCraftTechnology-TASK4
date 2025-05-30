# SkillCraftTechnology-TASK4
# TASK-4:🚦 Traffic Accident Analysis with Visual Insights
A data visualization and pattern discovery project based on real-world traffic accident conditions. This notebook uncovers insights about accident causes and severity using clean visual analytics.
---
## 📝 Task Overview
The goal is to analyze a dataset of traffic accidents to identify significant patterns related to:
- Road type
- Environmental conditions
- Driver behavior
- Accident severity
We use diverse visualizations (bar plots, pie charts, heatmaps, clustering, etc.) to present accident patterns that can inform public safety decisions and urban planning.
---
## 🎯 Objective
- Discover patterns behind traffic accidents using visual analytics.
- Determine how road, weather, traffic, and human factors contribute to accident severity.
- Visualize relationships and trends using expressive and interactive charts.
- Build a visual story to support data-driven decisions for traffic safety.
---
## 📋 Features Used in Dataset
| Column Name              | Description                                          |
|--------------------------|------------------------------------------------------|
| `Weather`                | Weather condition at the time of accident            |
| `Road_Type`              | Type of road (e.g., Highway, Urban)                  |
| `Time_of_Day`            | Time segment when accident occurred                  |
| `Traffic_Density`        | Level of traffic (Low, Medium, High)                 |
| `Speed_Limit`            | Speed limit at the location (in km/h or mph)         |
| `Number_of_Vehicles`     | Number of vehicles involved                          |
| `Driver_Alcohol`         | Alcohol consumption status of driver                 |
| `Accident_Severity`      | Categorical severity of the accident                 |
| `Road_Condition`         | Surface condition of the road                        |
| `Vehicle_Type`           | Vehicle type involved in the accident                |
| `Driver_Age`             | Age of the driver                                    |
| `Driver_Experience`      | Driving experience of the driver                     |
| `Road_Light_Condition`   | Lighting condition on the road at time of accident   |
| `Accident`               | Binary outcome indicating whether an accident occurred |
---
## ✅  What I Analysed through this task 
-🌧️ Weather and lighting conditions were key contributors to accidents.
-🛣️ Highways showed more severe accidents compared to urban roads.
-🚦 High traffic density combined with higher speed limits led to more serious outcomes.
-🚗 Driver alcohol involvement significantly increased accident occurrence.
-📈 A clear trend was found: higher speed limits correlate with more severe accidents.
-🎨 Successfully used heatmaps, line plots, bar charts, pie charts, and cluster plots to explain accident patterns.
-🤖 Cluster analysis revealed 3–4 major patterns of accident conditions (e.g., young drunk drivers on highways at night).
-📊 All insights were presented through visually rich, non-repetitive charts.

## ⚙️ Requirements
-Python
-Jupyter notebook
-Libraries Used:
-pandas & numpy: Data manipulation
-matplotlib & seaborn: Bar plots, pie charts, line graphs, heatmaps
-plotly: Interactive scatter plots and cluster visualization
-folium: Map-based accident heatmaps (optional if lat-long is present)
