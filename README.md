### **Project Summary: Interactive Power BI Dashboard for Traffic Data Analysis**

#### **Objective**  
The goal of this project is to clean, transform, and visualize traffic data enabling stakeholders to derive actionable insights. The data includes columns such as Time, Date, Day of the week, CarCount, BikeCount, BusCount, TruckCount, Total, and Traffic Situation.

Developed an interactive Power BI dashboard to visualize real-time traffic predictions, including traffic volume, congestion, and travel time. It provided actionable insights for optimizing routes and improving traffic management.

#### **Scope**  
This project involved creating an interactive Power BI dashboard to analyze traffic trends, focusing on vehicle counts, total traffic, and traffic situations across time and categories.

#### **Data Retrieval**  
- **Source:** Created dummy Traffic data with Chat GPT with intentional errors in a CSV file for cleaning and transformation.  

#### **Data Transformation**  
- **Cleaning:** Missing values were replaced with medians, and negative values in numerical columns were corrected.  
- **Formatting:** `Date` column was transformed into a proper date format, and a new `DayPart` column was added to classify time into Morning, Afternoon, Evening, and Night.  
- **Calculations:** A `TotalTraffic` column was created to sum vehicle counts using DAX.  

#### **Traffic Data Analysis Report**  

| **Aspect**          | **Details**                                                                                  |  
|----------------------|----------------------------------------------------------------------------------------------|  
| **Scope**           | Analysis of vehicle counts, traffic situations, and time-based patterns.                     |  
| **Key Metrics**     | Vehicle types (Cars, Bikes, Buses, Trucks), total traffic, and traffic situation distribution.|  
| **Time Analysis**   | Day parts (Morning, Afternoon, Evening, Night) and trends by day of the week.                |  
| **Visual Insights** | Bar charts, line charts, and pie charts highlighting traffic trends and situations.           |  
| **Purpose**         | To identify patterns and optimize traffic flow during peak times.                             |  

#### **Workflow in Power BI**  
1. **Data Cleaning:** Handled null values, fixed formatting issues, and created new calculated columns in Power Query.  
2. **Visualization:** Built an interactive dashboard with visuals for traffic trends, peak hours, and traffic situations.  

#### **Tools**  
- **Power BI:** For data transformation and dashboard creation.  
- **DAX:** For custom calculations and advanced insights.  

#### **Outcome**  
The dashboard provided actionable insights into traffic patterns, enabling better understanding of vehicle distribution, peak traffic times, and overall traffic conditions, supporting data-driven traffic management decisions.  
