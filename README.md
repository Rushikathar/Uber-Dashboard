# 🚖 Uber Rides Analysis Dashboard (Power BI)

## 📌 Project Overview
This project presents an interactive **Uber Rides Analysis Dashboard** built using **Microsoft Power BI**.  
The dashboard provides key insights into **ride performance, revenue trends, booking status, vehicle type analysis, and customer ratings**.

The objective of this project is to analyze Uber ride data and help stakeholders make **data-driven decisions** related to operations, revenue optimization, and customer experience.

---

## 🎯 Problem Statement
Uber wants to understand:
- Ride completion vs cancellation trends
- Revenue contribution by vehicle type
- Monthly booking performance
- Customer preference based on ratings
- Operational issues such as driver cancellations and no-driver-found cases

---

## 🧹 Data Cleaning & Transformation
The following steps were performed using **Power Query**:

- Removed duplicate records
- Handled missing values (e.g., replaced null booking values with 0)
- Converted date-time columns into proper formats
- Extracted **Time** from datetime column (`31-12-1899 17:04:47 → 17:04:47`)
- Standardized booking status values
- Created calculated columns and measures using **DAX**

---

## 📊 Key KPIs
- ✅ **Total Completed Rides**: 93K  
- ❌ **Lost Bookings**: 57K  
- 💰 **Total Revenue**: 52M  
- 🛣️ **Total Distance Covered**: 3M  
- 📏 **Average Distance per Ride**: 24.64  

---

## 📈 Dashboard Insights

### 1️⃣ Revenue by Vehicle Type
- Auto generates the highest revenue
- Uber XL contributes the least
- Go Mini and Go Sedan show strong demand

### 2️⃣ Booking Status Analysis
- Majority of rides are **Completed**
- Significant cancellations by **Drivers**
- Smaller portion cancelled by **Customers**
- Some rides failed due to **No Driver Found**

### 3️⃣ Monthly Booking Trend
- Peak ride completion observed in **January**
- Drop in February
- Stable performance during mid-year
- Slight decline towards year-end

### 4️⃣ Customer Rating by Vehicle Type
- Auto and Go Mini receive the highest ratings
- eBike has the lowest rating share
- Premium vehicles show moderate satisfaction

---

## 🛠️ Tools & Technologies Used
- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **MS Excel (for initial data handling)**

---

## 📂 Project Structure
Uber-Rides-Analysis/
│
├── Dataset/
│ └── uber_data.xlsx
│
├── Dashboard/
│ └── Uber_Dashboard.pbix
│
├── Screenshots/
│ └── uber_dashboard.png
│
└── README.md

yaml
Copy code

---

## 🖼️ Dashboard Preview
![Uber Dashboard](Screenshots/uber_dashboard.png)

---

## 🚀 Key Learnings
- Hands-on experience with **Power BI dashboard design**
- Practical use of **DAX measures**
- Real-world data cleaning techniques
- Business-oriented insight generation

---

## 📌 Future Enhancements
- Add city-wise and driver-wise analysis
- Include surge pricing impact
- Implement predictive analysis for ride demand

---

## 👤 Author
**Rushikesh Kathar**  
📊 Aspiring Data Analyst | Power BI | SQL | Excel | Python  
