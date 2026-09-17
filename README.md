# 📊 AtliQ Hardware — Business Insights 360 | Power BI

An interactive **Power BI Business Intelligence dashboard** built for **AtliQ Hardware** to analyze business performance across **Sales, Finance, Marketing, Supply Chain, and Executive** functions.

The project transforms business data into interactive dashboards and KPIs to help stakeholders understand **revenue performance, profitability, product trends, customer channels, regional performance, and forecast accuracy**.

---

## 🎯 Business Problem

AtliQ Hardware operates across multiple markets and sales channels, generating large volumes of business data.

The objective of this project was to build a centralized **Business Insights 360 dashboard** that enables stakeholders to:

- Monitor overall business performance
- Analyze sales and profitability
- Understand customer and product performance
- Track regional and channel contribution
- Evaluate forecast accuracy
- Identify business performance gaps
- Support data-driven decision-making

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development & visualization |
| **MySQL** | Data extraction & querying |
| **Microsoft Excel** | Data analysis & supporting data |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Measures, KPIs & business calculations |
| **DAX Studio** | Model optimization & performance analysis |
| **Power BI Service** | Report publishing & sharing |

---

## 📁 Dashboard Views

### 🏠 Home
Provides an overall navigation and business performance overview.

### 💰 Finance View
Analyzes:
- Net Sales
- Gross Margin
- Net Profit
- Net Profit %
- Cost & expense trends
- Profitability performance

### 📈 Sales View
Analyzes:
- Revenue performance
- Customer contribution
- Product performance
- Sales channels
- Regional performance
- Gross margin trends

### 📢 Marketing View
Analyzes:
- Product/category performance
- Customer segments
- Market contribution
- Profitability trends

### 🚚 Supply Chain View
Analyzes:
- Forecast accuracy
- Forecast error
- Supply performance
- Product-level operational metrics

### 👔 Executive View
Provides a high-level summary of:
- Revenue
- Profitability
- Market performance
- Channel contribution
- Product performance
- Key business KPIs

---

## 📌 Key KPIs

| KPI | Result |
|---|---:|
| **Net Sales** | **$3.74B** |
| **Gross Margin %** | **38.08%** |
| **Net Profit Margin %** | **-13.98%** |
| **Forecast Accuracy** | **81.17%** |
| **Net Error** | **-$3.47M** |
| **PC Division Revenue Share** | **61%** |
| **Retail Channel Contribution** | **~72%** |
| **LATAM Sales Contribution** | **0.42%** |
| **PC Market Share** | **7.63% → 5.87%** |


---

## 🔍 Key Business Insights

### 💻 Product Performance
- The **PC division contributes approximately 61% of revenue**.
- PC market share declined from **7.63% to 5.87%**, highlighting an area requiring further analysis.

### 🛒 Sales Channels
- The **Retailer channel contributes approximately 72% of revenue**.
- This indicates a significant dependence on the retailer channel for overall sales.

### 🌎 Regional Performance
- **LATAM contributes approximately 0.42% of sales**, making it an area worth investigating for growth opportunities.

### 📦 Supply Chain
- Overall **forecast accuracy is 81.17%**.
- The **-$3.47M net error** highlights a gap between forecasted and actual demand.

### 💰 Profitability
- Gross Margin stands at **38.08%**.
- Net Profit Margin is **-13.98%**, indicating that revenue growth needs to be evaluated alongside operating costs and overall profitability.

---

## 🧹 Data Preparation

The data preparation process included:

1. Connecting multiple data sources
2. Extracting data using **MySQL and Excel**
3. Cleaning inconsistent and incomplete data
4. Removing unnecessary fields
5. Transforming tables using **Power Query**
6. Creating calculated columns where required
7. Validating data before loading into Power BI
8. Preparing the data for analytical modeling

Detailed documentation:

- [Data Model](02_Data_Model/Data_Model.md)
- [DAX Measures](03_DAX/DAX_Measures.md)

---

## 🧩 Data Model

A **multi-table analytical model** was created using a structured schema to support reporting across different business functions.

The model contains **10+ tables** covering areas such as:

- Customers
- Products
- Sales
- Forecast
- Markets
- Regions
- Channels
- Supporting dimensions

The model was designed to improve:

- Data organization
- Relationship management
- DAX calculations
- Report performance
- Cross-functional analysis

📄 **[View Data Model →](02_Data_Model/Data_Model.md)**

---

## 📐 DAX & Measures

DAX was used to create business measures and analytical KPIs including:

- Net Sales
- Gross Margin
- Gross Margin %
- Net Profit
- Net Profit %
- Forecast Accuracy
- Forecast Error
- Revenue Contribution
- Year-over-Year Analysis
- Channel & Regional Metrics

📄 **[View DAX Documentation →](03_DAX/DAX_Measures.md)**

---

## ⚡ Performance Optimization

**DAX Studio** was used during development to analyze and optimize the Power BI model.

The optimization process focused on:

- Model efficiency
- DAX performance
- Reducing unnecessary data
- Improving report responsiveness
- Optimizing the Power BI file size

---

## 📊 Dashboard Preview

### Executive View
![Executive View](04_Dashboard_Screenshots/Executive_View.png)

### Finance View
![Finance View](04_Dashboard_Screenshots/Finance_View.png)

### Sales View
![Sales View](04_Dashboard_Screenshots/Sales_View.png)

### Marketing View
![Marketing View](04_Dashboard_Screenshots/Marketing_View.png)

### Supply Chain View
![Supply Chain View](04_Dashboard_Screenshots/Supply_Chain_View.png)

> Replace the image paths above with the actual screenshot filenames in your repository.

---

## 📂 Repository Structure

```text
AtliQ-Hardware-Business-360-Power-BI-Project/
│
├── 01_Data_Cleaning/
│   └── Power_Query_Data_Cleaning.md
│
├── 02_Data_Model/
│   └── Data_Model.md
│
├── 03_DAX/
│   └── DAX_Measures.md
│
├── 04_Dashboard_Screenshots/
│   ├── Executive_View.png
│   ├── Finance_View.png
│   ├── Sales_View.png
│   ├── Marketing_View.png
│   └── Supply_Chain_View.png
│
├── 05_Power_BI_Report/
│   └── AtliQ_Business_Insights_360.pbix
│
└── README.md
```

---

## 📈 Skills Demonstrated

- **Business Intelligence**
- **Power BI**
- **Data Cleaning**
- **Data Transformation**
- **Power Query**
- **Data Modeling**
- **Star/Snowflake Schema Concepts**
- **DAX**
- **KPI Development**
- **Business Analysis**
- **Dashboard Design**
- **Data Visualization**
- **Performance Optimization**
- **Business Storytelling**

---

## 💡 Business Questions Addressed

- What is the overall revenue and profitability?
- Which products generate the most revenue?
- Which customers and channels contribute most to sales?
- Which regions are performing well?
- How is the PC division performing?
- How accurate are the forecasts?
- Where are the largest forecast errors?
- Which business areas require further investigation?
- How does performance change across different business functions?

---

## ⚠️ Limitations

- The analysis is based on the available project dataset.
- Results depend on the data period and business assumptions used in the dataset.
- The dashboard should be interpreted alongside business context and additional operational information.
- Some metrics represent analytical calculations rather than official company KPIs.

---

## 🚀 Project Outcome

This project demonstrates an end-to-end **Business Intelligence workflow**:

**Raw Data → Data Cleaning → Data Transformation → Data Modeling → DAX → KPI Development → Dashboard → Business Insights**

The final dashboard provides a centralized view of business performance across multiple functions and demonstrates how Power BI can transform complex business data into an interactive analytical solution.

---

## 📚 Documentation

| Documentation | Link |
|---|---|
| 🧩 Data Model |  |
| 📐 DAX | [DAX Measures](03_DAX/DAX_Measures.md) |
| 📊 Dashboard | [Dashboard Screenshots](04_Dashboard_Screenshots/) |

---

## 👨‍💻 Author

**Vipul Gour**  
**Data Analyst | SQL | Power BI | Python | Excel**

🔗 **LinkedIn:** https://shorturl.at/D7tjF  
🌐 **Portfolio:** https://shorturl.at/zIUwQ  
💻 **GitHub:** https://shorturl.at/Fgkqr

---

## ⭐ Project

If you found this project useful, feel free to **star ⭐ the repository** and explore the other projects in my data analytics portfolio.

---

### 📌 Disclaimer

This project is created for **learning, portfolio, and analytical demonstration purposes** using the AtliQ Hardware dataset. The analysis and insights should not be interpreted as official information about AtliQ Hardware.
