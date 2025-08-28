# crime-analysis-dashboard (Tableau)
Tableau project analyzing crime data to uncover patterns, trends, and insights. Includes interactive dashboards for law enforcement decision-making and public communication.

## Project Overview  ???
Crime analysis plays a vital role in supporting law enforcement agencies by identifying crime patterns and enabling data-driven decision-making. This project focuses on building **interactive Tableau dashboards** to analyze crime statistics, detect trends, and provide actionable insights for the police department.  

The dashboards help in:  
- Monitoring crime hotspots  
- Understanding temporal crime patterns  
- Studying arrest vs. non-arrest incidents  
- Supporting preventive strategies for crime reduction  

---

## Problem Objective  
As a data scientist, the goal was to:  
- Prepare a dashboard in Tableau to keep the police department and city updated on crime statistics.  
- Enable data storytelling by presenting clear, interactive, and insightful visualizations.  


---

## Tools & Techniques Used  ???
As a data scientist, the goal was to:  
 

---

## Dataset & Variables  
The dataset was provided at the of the course and includes detailed crime records as a table named **Crime_data** with below varaibles.

- ID –--------------------------- Unique identifier for each record  
- Case Number –------------------ Police department’s unique case ID  
- Date –------------------------- Date of incident occurrence  
- Block –------------------------ Partially redacted address of incident  
- UCR Code –--------------------- Uniform Crime Reporting code, directly linked to the Primary Type and Description  
- Primary Type ------------------ primary description of the UCR code
- Description ------------------- secondary description of the UCR code, a subcategory of the primary description  
- Location Description –--------- Place where incident occurred  
- Arrest ------------------------ Whether an arrest was made
- Domestic ------------–--------- Whether the incident was domestic  
- Beat -------------------------- Beat where the incident occurred, and the beat is the smallest police geographic area
- District ---------------------- Indicates the police district where the incident occurred
- Ward -------------------------- Indicates the ward (city council district) where the incident occurred
- Community Area ---------------- The community area where the incident occurred
- NIC Code ---------------------- Crime classification as National Incident Code  
- X Coordinate ------------------ X coordinate of the location, where the incident occurred in the state plane
- Y Coordinate ------------------ Y coordinate of the location, where the incident occurred in state plane 
- Year -------------------------- Year the incident occurred
- Updated On –------------------- Date and time the record was last updated
- Latitude ---------------------- Latitude of the location, where the incident occurred
- Longitude --------------------- Longitude of the location, where the incident occurred
- Location ---------------------- The location, where the incident occurred in a format that allows for
                                    the creation of maps and other geographic operations on this data portal

---

## Steps & Dashboards Created  ??

### 1️⃣ Overall Crime Statistics Dashboard  
- Displayed **total count and types of crimes** reported.  
- Highlighted **crime locations on a geo-map** (hotspots).  
- Added **live crime feed**: total crimes reported in the current year + most recent crime (time & location).  

### 2️⃣ Time Period Analysis Dashboard  
- Distribution of crime incidents by **day of the week** and **hour of the day**.  
- Percentage of crimes by **time blocks** (e.g., early morning, afternoon, evening).  

### 3️⃣ Trend Analysis Dashboard  
- Studied changes in **crime rate across years**.  
- Compared **incident reporting trends** for the same date/time across years.  

### 4️⃣ Comparative Analysis Dashboard  
- Analyzed incidents with **arrest vs. no arrest**.  
- Percentage of **domestic-related incidents** by crime category.  

### 5️⃣ Interactivity  
- Added **filters** for incident type and location for granular exploration.  

---

## Repository Structure  ???
```
Crime-Analysis-/
│── data/
│ └── Crime_data.xlsx
│── tableau/ # Tableau workbook (.twb/.twbx)
│ ├── Aggregation_Grouping.xlsx
│ ├── Aggregation_Grouping.xlsx
│── outputs/
│ ├── Aggregation_Grouping.xlsx
│ ├── Aggregation_Grouping.xlsx
│ ├── Aggregation_Grouping.xlsx
│ ├── Aggregation_Grouping.xlsx
│── README.md
```




---

## Dashboard Snapshots (Samples)  ??????
_Add exported PNGs or PDFs of your Tableau dashboards here for recruiters to see._  

---

## Tools & Technologies  
- **Tableau** – Dashboard creation & visualization  
- **Excel/CSV** – Data source format  
- **GitHub** – Project hosting & documentation  

---

## Key Learnings  
- Gained hands-on experience in **data storytelling** with Tableau.  
- Learned how to create **interactive dashboards** for real-world use cases.  
- Improved skills in ** data analysis & visualization**.  

---

## 📌 Future Work  
- Incorporate **real-time data feeds** (if available).  
- Extend analysis with **predictive modeling** using Python.  
- Build **automated Tableau dashboards** for scheduled updates.  

---

