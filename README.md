#  Airline Data Management and Analysis Using Power BI ✈️ 

## 📷 Dashboard Preview
---

<img width="1330" height="745" alt="Airline_dashboard" src="https://github.com/user-attachments/assets/83d3b8dd-10b4-4fea-854e-d559fb249267" />

<img width="1313" height="737" alt="Screenshot 2026-01-17 000452" src="https://github.com/user-attachments/assets/fc94e92d-20bf-443b-90a7-442adcc7596f" />


## 📌 Project Overview
The airline industry manages complex operational data related to flight schedules, passenger movement, and ticket bookings. Efficient analysis of this data is essential for improving operational efficiency, monitoring performance, and enhancing customer satisfaction.

This project focuses on analyzing airline operational data using **Power BI** to build an interactive dashboard that provides clear business insights. Multiple datasets were integrated, cleaned, and modeled to deliver a consolidated view of airline performance, passenger distribution, and ticket booking trends.

---

## 🎯 Project Objectives
The primary objective of this project is to demonstrate how airline data can be transformed into meaningful insights through effective data analytics and visualization. The project aims to analyze flight performance, track passenger movement, monitor booking statuses, and identify operational areas that require improvement.

Another important goal is to showcase end-to-end Power BI skills, including data preparation, data modeling, DAX calculations, and dashboard storytelling for business decision-making.

---

## 📂 Data Source Description
The analysis is based on three structured datasets representing different aspects of airline operations. The **Flight Information** dataset contains details such as flight numbers, airlines, destinations, and flight status. The **Passenger Information** dataset includes passenger identifiers linked to flights, along with seating details. The **Ticket Information** dataset captures ticket bookings and their respective statuses.

These datasets were linked using a common key, **FlightID**, enabling a unified view of airline operations.

---

## 🔄 Data Preparation and Cleaning
All datasets were imported into Power BI and processed using **Power Query**. During this phase, duplicate records were removed, missing values were handled, and column formats were standardized to ensure consistency across datasets.

Careful data cleaning was performed to maintain accuracy and reliability, ensuring that the final analysis was based on high-quality data.

---

## 🧩 Data Modeling
A relational data model was created by establishing relationships between the flight, passenger, and ticket datasets using **FlightID** as the primary key. Proper cardinality was applied to maintain data integrity and enable accurate aggregations across tables.

The data model was optimized to support efficient reporting and smooth dashboard performance.

---

## 📊 Data Transformation and Enrichment
To enhance analytical capabilities, additional transformations were applied to the data. Flights were classified into performance categories such as **Best** and **To Be Improved** based on their operational status. This classification helped in identifying high-performing flights as well as those requiring optimization.

Flight numbers were also extracted and standardized using Power BI’s transformation features to improve readability and reporting clarity.

---

## 🧮 DAX Calculations and Measures
Custom **DAX measures** were created to calculate key metrics such as total passengers, total tickets booked, and passenger distribution by airline. Additional measures were used to analyze booking status trends and evaluate flight performance.

These calculations enabled dynamic analysis and allowed users to interact with the dashboard to explore insights at different levels.

---

## 📈 Dashboard Design and Features
The final Power BI dashboard presents a comprehensive view of airline operations through a clean and interactive layout. Key performance indicators highlight passenger counts, available flights, and ticket bookings. Visualizations display passenger distribution by airline, booking status breakdowns, and flight performance across destinations.

Interactive slicers allow users to filter the analysis by airline and destination, making the dashboard suitable for both high-level overviews and focused analysis.

---

## 🔐 Power BI Service Implementation
To simulate real-world business scenarios, **Row-Level Security (RLS)** was implemented to restrict data access based on airline-specific roles. The dashboard was published to **Power BI Service**, and a scheduled data refresh was configured to ensure up-to-date reporting.

---

## 📌 Key Insights
The analysis reveals that Airline D has the highest passenger volume, along with a higher number of booking cancellations. Certain destinations, such as Phoenix, show consistently high passenger traffic, indicating potential route congestion. A significant number of flights fall under the “To Be Improved” category, highlighting opportunities for operational enhancement.

These insights demonstrate how airline data can be used to identify performance gaps and support data-driven decision-making.

---



## 🚀 Conclusion
This project demonstrates an end-to-end **business intelligence and data analytics workflow** using Power BI. It highlights practical skills in data cleaning, modeling, DAX calculations, dashboard design, and insight generation. The project reflects real-world airline operational analysis and emphasizes the value of data-driven decision-making.

---

## 👤 Author
**Devina M Vasudevan**  
Aspiring Data Analyst | Power BI | Data Visualization | Business Intelligence  

---

## 🔗 How to Use This Project
Download the `.pbix` file and open it in **Power BI Desktop**. Use the interactive filters and visuals to explore airline performance, passenger trends, and booking patterns.


## 🔗 How to Use This Project
1. Download the `.pbix` file  
2. Open it in **Power BI Desktop**  
3. Refresh the data (if source files are available)  
4. Explore the dashboard using slicers and filters  
