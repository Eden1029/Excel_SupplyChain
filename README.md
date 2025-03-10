# 🚛 Supply Chain and Freight Analytics Dashboard - Excel

## 📌 Overview
This **Excel-based Supply Chain and Freight Analytics Dashboard** analyzes key logistics and transportation performance indicators. The dataset includes **freight loads, shipment destinations, truck types, costs, and profit metrics** across multiple regions.

The dashboard provides insights into:
- **Shipment Costs & Profitability**
- **Freight Load Trends**
- **Customer Segmentation & Retention**
- **Truck Performance & Operational Expenses**

---

## 📂 Dataset Details
- **Source:** Internal Supply Chain Data  
- **Time Period:** Covers multiple months  
- **Total Records:** **61 shipments**  
- **Key Columns:**
  - **Freight Details:** Load Type, Tonnage, Destination, Truck Type  
  - **Cost & Expenses:** Fuel, Insurance, Repairs, Toll Fees, Shipment Costs  
  - **Operational Data:** Rate per Mile, Driver Costs, Total Expenses  

---

## 🧹 Data Cleaning Process
1. **Handling Missing Values:**  
   - 22 missing values found in the **Repairs** column.
   - Missing values were filled using the **median repair cost**.
   
2. **Standardizing Categorical Data:**  
   - **Destination names were corrected** (e.g., "Nunavut." → "Nunavut").
   - **Truck types were categorized** into **4 main vehicle groups**.

3. **Numeric Data Cleaning:**  
   - **Rates per mile and total expenses were checked** for consistency.
   - **Fuel costs and insurance values were verified** for outliers.

---

## 🔍 Key Insights & Trends

### 1️⃣ **Freight Load & Shipment Trends**
✅ **Top Freight Types Shipped:**  
- **Wood** and **Sand** are the most frequently shipped materials.
- **Tonnage ranges from 11 to 23 per shipment**.

✅ **Regional Shipment Insights:**  
- **Most Common Destinations:** British Columbia, Alberta, Manitoba.
- **Nunavut had the lowest shipment volume**, likely due to remote access challenges.

✅ **Seasonal Trends:**  
- **Freight volume peaks in Q1 and Q3**.
- **Tonnage fluctuation suggests seasonal demand cycles**.

---

### 2️⃣ **Cost & Profitability Analysis**
✅ **Average Shipping Cost Per Load:**  
- **$1,554 per shipment**, with fluctuations based on **distance and fuel prices**.

✅ **Major Cost Drivers:**  
| Expense Type      | Avg Cost ($) | Impact |
|------------------|-------------|--------|
| **Fuel**         | 388.85       | 🔥 High Impact |
| **Insurance**    | 132.00       | 🛡️ Fixed |
| **Repairs**      | 56.79        | ⚙️ Variable |
| **Toll Fees**    | 120.85       | 🚧 Regional |

✅ **Rate Per Mile Analysis:**  
- **Highest Rate Per Mile:** $279.3  
- **Lowest Rate Per Mile:** $163.8  
- **Standardized Pricing:** Most shipments operate around **$245 per mile**.

---

### 3️⃣ **Customer & Truck Performance Analysis**
✅ **Customer Types:**  
- **68% of shipments are from Retaining Customers**, meaning the company has strong **customer loyalty**.  
- **New customers account for only 32%**, suggesting an **opportunity for expansion**.

✅ **Truck Performance:**  
| Truck Model              | Usage %  | Avg Load (Tons) |  
|-------------------------|---------|-----------------|  
| Freightliner Sprinter   | 40%     | **16.5**        |  
| Chevrolet Express       | 25%     | **14.2**        |  
| RAM ProMaster           | 20%     | **18.1**        |  
| Nissan NV2500           | 15%     | **19.5**        |  

**Observation:**  
- **Nissan NV2500 carries the heaviest loads**, but is **used the least**.
- **Freightliner Sprinter is the most commonly used truck** despite having a **medium load capacity**.

✅ **Cost Efficiency by Truck Model:**
- **RAM ProMaster has the lowest operating cost per shipment.**
- **Freightliner Sprinter has higher maintenance costs** but is widely used.
- **Nissan NV2500 is underutilized** despite being capable of carrying **larger loads**.

---

## 📊 Excel Dashboard Features
The **interactive Excel dashboard** allows users to:  
✅ Filter shipments by **Month, Truck Type, and Destination**  
✅ Analyze **cost trends** and **profitability metrics**  
✅ Compare **customer retention vs new customer shipments**  
✅ Visualize **operational efficiency by truck model**  

🔗 **Download the Excel file**: [Excel Supply Chain Dashboard.xlsx](https://github.com/Eden1029/Excel_SupplyChain/blob/main/Excel%20Supply%20Chain%20and%20Freight%20Analytics%20Dashboard.xlsx)  

---

## 🚀 Future Improvements
🔹 Integrate **real-time shipment tracking**  
🔹 Implement **predictive cost analysis** using **Excel forecasting tools**  
🔹 Optimize **truck allocation strategies** to reduce underutilization  

---

## 🤝 Connect with Me
- 🔗 **LinkedIn**: www.linkedin.com/in/eden-nguyen  
- 📧 **Email**: your.email@example.com  

