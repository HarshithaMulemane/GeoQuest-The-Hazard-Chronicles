# Story Map Report: Tracking Wildfires in Real Time – A Data-Driven Perspective

## 1. Environmental Hazard & Problem Statement

### Hazard: Wildfires  
Wildfires have emerged as one of the most destructive environmental hazards globally. Their increasing frequency and severity are fueled by rising temperatures, long-term droughts, and human activity expanding into natural landscapes. The western United States, in particular, faces year-round fire threats.

### Problem Statement  
Wildfires not only ravage ecosystems but also threaten lives, infrastructure, and public health through air pollution and forced evacuations. Their unpredictable behavior makes rapid response challenging. This project aims to demonstrate how real-time wildfire perimeter data can enhance situational awareness and aid in public education through interactive mapping and visual storytelling.

---

## 2. Dataset Justification & Processing

### Primary Dataset  
- Name: WFIGS Interagency Wildfire Perimeters (Current)  
- Source: National Interagency Fire Center (NIFC)  
- URL: https://data-nifc.opendata.arcgis.com

### Key Attributes Used  
- Fire incident name  
- Acres burned  
- Mapping method  
- Incident complexity level (Type 1–5)  
- Feature status and mapping source  

### Why This Dataset?  
This dataset provides a real-time, spatial view of active wildfires in the U.S., making it ideal for visual analysis using ArcGIS StoryMaps. It supports meaningful comparisons across incidents and offers data-backed insight for emergency response and public awareness.

### Data Cleaning & Preprocessing  
- Removed null and incomplete records  
- Selected key fields for mapping and pop-up display  
- Added mock latitude and longitude coordinates to enable location mapping in public ArcGIS accounts  
- Projected to WGS 84 (EPSG:4326) for web map compatibility  
- Final dataset used: Mock_Wildfire_Perimeters_with_Coordinates.csv

---

## 3. Visual Storytelling with Real-Time Simulation

### Interactive Map Component  
The ArcGIS Map Tour displays wildfire incidents as clickable points. Each point contains information about the fire name, acres burned, complexity, and mapping method.

### Real-Time Simulation  
Due to ArcGIS Online free account limitations:
- Mock coordinates are used with near real-time wildfire data
- Reference to live dashboards such as NASA FIRMS and NIFC is included for additional context
- The map mimics real-time trends using updated perimeters

---

## 4. Data Analysis & Visualization

### Key Findings  
- Average fire size: 170 acres  
- Most common fire complexity: Type 4  
- 80% of incidents were mapped using “Mixed Methods”

### Visual Elements Used  
- Map with symbology (size and color coded by attributes)  
- Bar chart: Acres burned per fire  
- Pie chart: Distribution of complexity levels  
- Satellite image comparisons and educational video on wildfire spread

---

## 5. Call to Action: Reducing Wildfire Risk

### Recommendations  
- Encourage use of prescribed burns and fuel reduction  
- Invest in early warning systems and satellite-based detection  
- Apply stricter zoning regulations in wildland-urban interface areas  
- Promote public education on fire prevention and evacuation readiness

---

## 6. Usability & Accessibility

- High-contrast color scheme for readability  
- Clear labels, titles, and legends included  
- Descriptive pop-ups with organized layout  
- Alt text and clear formatting used for all media

---

## 7. Citations & Attribution

- Dataset Source: National Interagency Fire Center (NIFC), WFIGS perimeter data. Accessed April 2025  
- Image Credits: NASA Earth Observatory, Unsplash (used for fire-related visuals)  
- Mapping Tools: ArcGIS Online, ArcGIS StoryMaps  
- Software Tools: Python (data preprocessing), Microsoft Excel (field filtering)

---

## 8. Innovation & Creativity

### Unique Elements  
- HTML-enhanced custom pop-ups with well-structured fire data  
- Simulated live mapping through current data and mock coordinates  
- Integration of narrative elements, visual comparisons, and external resources  
- Story-driven design with interactive user engagement

---

## Summary

This Story Map delivers a data-rich, interactive experience that raises awareness about the growing threat of wildfires. By turning real-time wildfire data into a visual narrative, the project supports public education and promotes proactive approaches to fire preparedness and risk reduction.


<img width="1470" alt="Screenshot 2025-04-12 at 6 10 32 PM" src="https://github.com/user-attachments/assets/dc85c96b-d41a-4112-bb58-fe21c7dadac0" />

<img width="1470" alt="Screenshot 2025-04-12 at 6 10 59 PM" src="https://github.com/user-attachments/assets/ede9fe7a-b38f-4b73-a0c2-81d865e7d676" />


