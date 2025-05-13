# EV-charging-forecasting-Project
Electric Vehicle Charging Demand Forecasting
Project Overview:
This project aims to forecast electric vehicle (EV) charging demand using time-series modeling and data visualization techniques. By leveraging datasets related to EV usage, weather, and traffic patterns, we predict the energy demand at EV charging stations across different zones and time intervals. The insights are visualized through interactive Tableau dashboards to support data-driven decisions for infrastructure planning and charging optimization.

Tools & Technologies  used:
Python (Pandas, Prophet, ARIMA, Matplotlib)
Excel (Initial data cleaning and merging)
Tableau (Dashboard creation and visualization)

Datasets Used:
EV charging session data (timestamp, location, energy consumed)

Weather data (temperature, humidity, wind speed, precipitation)

Traffic data (congestion levels, vehicle count per hour)

Methodology:
Data Merging & Preprocessing: Combined EV usage, weather, and traffic datasets using timestamp and location as keys.

Time-Series Forecasting: Developed demand prediction models using ARIMA and Prophet for each zone.

Visualization: Created interactive dashboards in Tableau to display:

Demand heatmaps

Zone-wise energy consumption

Peak and off-peak charging periods

Deliverables:
Forecasting Models (.pkl / .ipynb files)

Tableau Dashboards (.twbx file or screenshots)

Charging Optimization Strategy Report (optional .pdf or .docx)

Key Insights:
Peak charging demand occurs during weekday evenings and weekend afternoons

Weather and traffic significantly impact charging patterns

Forecasting helps identify optimal times for energy distribution and infrastructure load balancing
