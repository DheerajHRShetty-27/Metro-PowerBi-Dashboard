# 🚇 Bengaluru Metro Ridership & Revenue Analysis (Jan–Oct 2025)

![Dashboard Preview](image.png)

This project presents an interactive **Power BI dashboard** analyzing **Namma Metro (Bengaluru)** ridership, occupancy, and revenue trends from **January to October 2025**.  
Using multiple datasets (ridership, stations, lines, fare matrix), it provides insights into passenger behavior and operational performance across metro lines.

---

## 📌 Key Metrics (From Dashboard)

### **📊 Total Passengers (Lakhs)**
**1.53K+ Lakhs** passengers across all lines

### **🏟 Operational Stations**
**83 stations** active

### **📈 Average Occupancy**
**60.33%**

### **💰 Revenue per Passenger**
Approx **₹32.96**

---

## 📍 Dashboard Features

### **1️⃣ Map View of Metro Stations**
- Interactive Bengaluru city map  
- Colored by line (Green, Purple, Yellow)  
- Bubble size = Ridership (Lakhs)  

### **2️⃣ Line Selector**
Filter dashboard by:

- Green Line  
- Purple Line  
- Yellow Line  

### **3️⃣ Monthly Ridership Trend**
Shows how ridership changed from January → October 2025.

### **4️⃣ Operational Status Filter**
- Operational  
- Not Operational  

### **5️⃣ Passengers vs Occupancy Scatter Plot**
Helps identify:

- High passenger but low occupancy stations  
- High occupancy but low passenger stations  

### **6️⃣ Detailed Station Table**
Includes:

- Station Name  
- Line  
- Passengers (Lakhs)  
- Occupancy %  
- Average Fare  
- Revenue (₹)  
- Status  

---

## 📁 Repository Structure

| File Name | Description |
|-----------|-------------|
| **namma metro bnglru.pbix** | Main Power BI dashboard |
| **ridership_bengaluru_metro_jan_oct_2025.csv** | Monthly ridership dataset |
| **stations_bengaluru_metro.csv** | Metro station details |
| **lines_bengaluru_metro.csv** | Line information (Green, Purple, Yellow) |
| **namma_metro_fare_matrix_83x83.csv** | Fare matrix between station pairs |
| **Bengaluru_Metro_Theme.json** | Custom Power BI theme |
| **image.png** | Dashboard preview image |

---

## 🛠 Tools & Skills Used

- **Power BI Desktop**
- DAX measures
- Power Query transformations
- Geo-spatial visualization (Map)
- KPI Cards
- Trend lines & scatter plots
- Data modeling (relationship between 5 datasets)

---

## 🎯 Objective of this Project

- Analyze ridership trends for Bengaluru Metro  
- Understand operational efficiency and occupancy  
- Compare station-level performance across lines  
- Visualize city-wide metro activity using maps  
- Provide data-driven revenue insights  

---

## 🚀 How to Use This Project

1. Download or clone the repository  
2. Open `namma metro bnglru.pbix` in **Power BI Desktop**  
3. If the data connections break, re-map to:
   - `ridership_bengaluru_metro_jan_oct_2025.csv`
   - `stations_bengaluru_metro.csv`
   - `lines_bengaluru_metro.csv`
   - `namma_metro_fare_matrix_83x83.csv`
4. Click **Refresh**  
5. Interact with slicers, filters, and map visuals  

---

