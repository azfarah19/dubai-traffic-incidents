# 🚦 Dubai Traffic Incidents – Portfolio Project

## 🎯 Objective
Analyze traffic incidents in Dubai (77K+ records between November 2024 and September 2025.) to identify patterns in **causes**, **timing**, and **severity**, and provide recommendations to improve road safety and traffic flow.

## Data
- **Source:** [Dubai Pulse – Traffic Incidents](https://www.dubaipulse.gov.ae)
- **Size:** 77,084 records 
- **Columns:**  
  - `acci_id`: Unique incident ID  
  - `acci_time`: Date and time of incident  
  - `acci_name`: Type of incident (e.g., breakdown, collision)  
  - `acci_x`, `acci_y`: Coordinates (Latitude, Longitude)

## Methodology
1. **Data Cleaning & Preprocessing** (Python/Pandas):  
   - Converted timestamps → year, month, hour.  
   - Removed duplicates & filtered valid coordinates.  
   - Saved clean dataset for further use.

2. **Exploratory Data Analysis (EDA):**  
   - KPIs: total incidents, top causes, peak hour.  
   - Visualizations:  
     - Barh → Top 10 causes.  
     - Line → Incidents by hour.  
     - Line → Incidents by month.  
     - Folium Map → Geographic distribution.

3. **Dashboard in Power BI:**  
   - **row 1 – Overview:** Total incidents, peak hour, map.  
   - **row 2 – Causes:** Top 10 accident types, distribution pie chart.  
   - **row 3 – Time Analysis:** Incidents by hour, card for peak hour.  

4. **Executive Report (PDF):**  
   - Background, KPIs, 3 visuals.  
   - Insights + Recommendations (both Arabic & English).  

##  Key Findings
- **The most dangerous hour is 2 PM (14:00), with 4,574 incidents.**  
- **Most common incident type:** Light vehicle breakdown (≈10K cases).  
- **Minor incidents:** 83% of the total but still cause traffic disruptions.  

## 🛠 Tools & Technologies
- Python: Pandas, Matplotlib, Folium  
- Power BI  
- GitHub for portfolio  

## 📈 Deliverables
-  [Jupyter Notebook (EDA)](dubai_Acci_traffic.ipynb)  
- [Power BI Dashboard](dashboard_acci.pbix)  
- [Executive Report (PDF)](reports/Executive Summary.pdf)  

## 🌍 Author
Farah Azema  
[LinkedIn](https://www.linkedin.com/in/farah-azema-490a691b9/) | [GitHub](https://github.com/azfarah19/dubai-traffic-incidents/) 

---


