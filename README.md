# Airline-Data-Management-and-Analysis-Using-Power-BI
To analyze and visualize airline data for operational insights, passenger management, and ticket booking trends using Power BI.

<img width="1330" height="745" alt="Airline_dashboard" src="https://github.com/user-attachments/assets/83d3b8dd-10b4-4fea-854e-d559fb249267" />

<img width="1313" height="737" alt="Screenshot 2026-01-17 000452" src="https://github.com/user-attachments/assets/fc94e92d-20bf-443b-90a7-442adcc7596f" />

# ✈️ Airline Data Management and Analysis Using Power BI

## 📌 Project Overview
The airline industry handles large volumes of operational data related to flights, passengers, and ticket bookings. Efficient analysis of this data is essential for improving operational performance, passenger management, and customer satisfaction.

This project uses **Power BI** to analyze airline operations by integrating multiple datasets, performing data cleaning and modeling, creating DAX calculations, and building an interactive business intelligence dashboard that provides actionable insights.

---

## 🎯 Objectives
- Analyze airline flight performance and operational status  
- Understand passenger distribution across airlines and destinations  
- Monitor ticket booking trends and cancellations  
- Identify performance gaps and optimization opportunities  
- Build an interactive dashboard for data-driven decision making  

---

## 📂 Datasets Used
The project uses three structured datasets:

### 1️⃣ Flight Information
- FlightID  
- FlightNumber  
- Airline  
- Destination  
- Flight Status (On Time / Cancelled / Delayed)

### 2️⃣ Passenger Information
- PassengerID  
- FlightID  
- Seat Number  

### 3️⃣ Ticket Information
- TicketID  
- FlightID  
- Booking Status (Confirmed / Cancelled / Pending)

---

## 🛠️ Tools & Technologies
- Power BI  
- Power Query (ETL & Data Transformation)  
- DAX (Data Analysis Expressions)  
- Data Modeling  
- Power BI Service  

---

## 🔄 Data Preparation and Cleaning
- Imported all datasets into Power BI  
- Cleaned data using Power Query:
  - Removed duplicate records  
  - Handled missing values  
  - Standardized column formats  
- Verified data consistency across all tables  

---

## 🧩 Data Modeling
- Created relationships between datasets using **FlightID** as the primary key  
- Applied correct one-to-many cardinality  
- Optimized the data model for performance and accurate reporting  

---

## 📊 Data Transformation and Enrichment
- Created a conditional column to classify flights as:
  - **Best**
  - **To Be Improved**
- Extracted flight numbers using **Column from Examples**  
- Enhanced dataset structure for reporting and visualization  

---

## 🧮 DAX Calculations
Developed DAX measures to calculate:
- Total passengers  
- Total tickets booked  
- Passenger count by airline  
- Ticket count by booking status  
- Flight performance metrics  
- Filtered views for “Best” flights  

---

## 📈 Dashboard and Visualizations
The Power BI dashboard includes:
- KPI cards for total passengers, flights available, and tickets sold  
- Passenger count by airline  
- Flight performance analysis (Best vs To Be Improved)  
- Booking status distribution  
- Flights by airline and destination  
- Interactive slicers for airline and destination  

---

## 🔐 Power BI Service Features
- Implemented **Row-Level Security (RLS)** for airline-specific access  
- Configured scheduled data refresh at **5:00 PM daily**  
- Published the dashboard to Power BI Service  

---

## 📌 Key Insights
- Airline D has the highest passenger count along with higher cancellations  
- Phoenix destination shows high passenger traffic, indicating possible route oversaturation  
- Majority of flights fall under the “To Be Improved” category  
- Ticket cancellations significantly impact operational efficiency  

---

## 📷 Project Deliverables
- Cleaned datasets  
- Data model screenshots  
- DAX calculations  
- Interactive Power BI dashboard  
- Business insights summary  

---

## 🚀 Conclusion
This project demonstrates end-to-end data analytics and business intelligence skills, including data cleaning, modeling, DAX calculations, dashboard design, and insight generation. It reflects real-world airline operational analysis and highlights how data can support informed decision-making.

---

## 👤 Author
**Devina M Vasudevan**  
Aspiring Data Analyst | Power BI | Data Visualization | Business Intelligence  

---

## 🔗 How to Use This Project
1. Download the `.pbix` file  
2. Open it in **Power BI Desktop**  
3. Refresh the data (if source files are available)  
4. Explore the dashboard using slicers and filters  
