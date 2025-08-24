# Real Estate Sales Analysis – USA  

## About the Project  
This project analyzes **real estate sales trends** across different states and cities in the USA.  
It focuses on sales distribution, property characteristics, pricing trends, and seasonal variations, leveraging Power BI dashboards for visualization.  

## 📂 Project Name  
**Real Estate Sales Analysis – USA**  

## Domain  
**Real Estate | Data Analytics | Business Intelligence**  

## 🛠️ Tools Used  
- **Power BI Desktop** – Dashboard creation & visualization  
- **Excel** – Data cleaning & preprocessing  

## 📑 Methodology  
1. **Data Collection** – Aggregated property-level sales records  
2. **Data Cleaning & Preparation** – Removing inconsistencies, formatting columns  
3. **Exploratory Data Analysis (EDA)** – Identifying trends and patterns  
4. **Dashboard Development** – Creating interactive visualizations in Power BI  
5. **Insights & Reporting** – Summarizing results for research purposes  

---

## 📊 Data Description  

### Table 1 – Quered Data (Year and Month)  

| Column Name | Datatype | Description |
| :--- | :--- | :--- |
| state | Str | State of the property |
| city | Str | City of the property |
| year | Int | Year of record |
| month | Str | Month of record |
| bedrooms | Int | Number of bedrooms |
| bathrooms | Int | Number of bathrooms |
| num_of_prc | Int | Number of properties recorded |
| avg_price | Float | Average property price |
| min_price | Float | Minimum property price |
| max_price | Float | Maximum property price |
| avg_size | Float | Average size (m²) |
| min_size | Float | Minimum size (m²) |
| max_size | Float | Maximum size (m²) |
| avg_lot | Float | Average lot size (ha) |
| min_lot | Float | Minimum lot size (ha) |
| max_lot | Float | Maximum lot size (ha) |

---

### Table 2 – Quered Data (Property Sold)  

| Column Name | Datatype | Description |
| :--- | :--- | :--- |
| state | Str | State of the property |
| city | Str | City of the property |
| year | Int | Year of record |
| bedrooms | Int | Number of bedrooms |
| bathrooms | Int | Number of bathrooms |
| num_of_prc | Int | Number of properties recorded |
| market_size | Float | Market size in USD |
| avg_price | Float | Average property price |
| min_price | Float | Minimum property price |
| max_price | Float | Maximum property price |
| avg_size | Float | Average property size (m²) |
| min_size | Float | Minimum property size (m²) |
| max_size | Float | Maximum property size (m²) |
| avg_lot | Float | Average lot size (ha) |
| min_lot | Float | Minimum lot size (ha) |
| max_lot | Float | Maximum lot size (ha) |

---

## 📈 Metrics Used  
- **Number of properties sold**  
- **Average, minimum, and maximum prices**  
- **Average property size (m²)**  
- **Average lot size (ha)**  
- **Market size (USD)**  

---

## Dashboard Overview  

### Dashboard 1 – Sales Distribution & Market Size  
![Dashboard 1](Image_Asset/Real-Estate%20USA%20Dashboards_page-0001.jpg)  

### Dashboard 2 – Price Trends & Property Characteristics  
![Dashboard 2](Image_Asset/Real-Estate%20USA%20Dashboards_page-0002.jpg)  

### Dashboard 3 – Yearly & Monthly Sales Trends  
![Dashboard 3](Image_Asset/Real-Estate%20USA%20Dashboards_page-0003.jpg)    

---

## Key Insights  
- **New York & New Jersey** dominate property sales and market size.  
- Most properties sold fall within the **2–4 bedrooms** range.  
- Average property price is around **$790K–$811K**, with significant luxury outliers.  
- **Summer months (May–August)** see the highest property transactions.  
- Long-term trend shows peaks around **2005 and 2015**, with fluctuations in recent years.  

---

