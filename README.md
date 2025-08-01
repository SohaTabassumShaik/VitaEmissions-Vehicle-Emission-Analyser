**VitaEmissions: Vehicle Emission Analyzer**

**VitaEmissions** is a real-time vehicle emission analysis system designed to promote environmental compliance and reduce pollution. This smart dashboard classifies vehicle emissions, generates fine reports, issues voice alerts, and maps pollution hotspots — all using Python.

**Overview**

Many vehicles contribute significantly to air pollution due to poor maintenance and lack of real-time emission tracking. VitaEmissions addresses this issue by:

- Analyzing CO, NOx, and PM2.5 levels
- Classifying vehicles based on their pollution status
- Generating PDF fine reports for high-emission vehicles
- Mapping emission hotspots with geospatial visualization
- Issuing real-time voice alerts

**Objectives**

- ✅ Detect high-emission vehicles in real time
- ✅ Provide digital emission classification
- ✅ Support smart city and eco-policy enforcement
- ✅ Encourage regular self-checks via digital tools

**Tech Stack & Tools**

1. Python – Core logic and backend programming
2. Pandas – Data manipulation and dataset creation
3. Streamlit – Web-based dashboard and user interface
4. Plotly – Interactive visualizations and charts
5. Seaborn – Statistical data visualization
6. Folium – Geo-mapping of emission hotspots
7. pyttsx3 – Text-to-speech voice alerts
8. ReportLab – PDF fine report generation

**Features**

✅ Classify Emissions
- Accepts real-time values of **CO, NOx, PM2.5**
- Flags emissions as *Safe*, *Moderate*, or *Danger*
- Triggers voice alerts
- Logs data with timestamps and simulated locations

📄 Fine Report Generation
- Automatically generates a PDF report if pollution is in *Danger* range
- Includes pollutant levels, time, and simulated location

📊 Dataset Visualization
- Shows logged vehicle records
- Displays pollutant averages by vehicle type
- Shows emission status distribution via pie chart

🗺️ Geo-Emission Map
- Plots vehicle emissions on an interactive map
- Color-coded markers based on emission status
- Popups display full emission details


**Results**

- Classified over 100 sample emission records across 4 vehicle types
- Generated real-time fine reports
- Visualized emission hotspots and patterns using charts and maps


**Sustainability & Impact**

- Enables real-time pollution monitoring for smart cities
- Helps authorities identify and penalize non-compliant vehicles
- Encourages citizens to stay environmentally responsible
- A step toward **green mobility** and **cleaner cities**

**Future Scope**

- Integrate **number plate detection** using OpenCV
- Connect with **real sensor APIs or IoT devices**
- Deploy for **traffic departments** and **eco-governance platforms**

**Contribution**
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change or improve.


