# 🏗️ AtliQ Hardware — Data Model

The AtliQ Hardware Power BI project uses a structured **multi-table analytical data model** to analyze sales, finance, marketing, supply chain, and business performance.

## 🎯 Objective

Build a scalable model that supports:

- Sales analysis
- Finance analysis
- Product analysis
- Customer & channel analysis
- Market / regional analysis
- Supply chain analysis
- Executive performance tracking

## 🗂️ Model Structure

```text id="v1k7rp"
                    ┌──────────┐
                    │  Date    │
                    └────┬─────┘
                         │
                         ▼
┌──────────┐       ┌───────────┐       ┌──────────┐
│ Customer │──────►│   Sales   │◄──────│ Product  │
└──────────┘       └─────┬─────┘       └──────────┘
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
      Finance        Marketing      Supply Chain
```

> **Note:** The diagram is a simplified representation. The actual model contains the project-specific fact and dimension tables.

## 🔗 Modeling Approach

- Used a **star/snowflake-style analytical model**.
- Separated transactional data from descriptive dimensions.
- Created relationships using appropriate business keys.
- Used a dedicated Date table for time-based analysis.
- Maintained consistent data types across relationship columns.
- Designed the model to support interactive filtering and DAX calculations.
- Structured the model to support multiple business functions.

## 🗃️ Key Business Tables

| Area | Purpose |
|---|---|
| **Sales** | Revenue, quantity, orders & sales performance |
| **Finance** | Gross margin, net sales & profitability |
| **Customer** | Customer and channel analysis |
| **Product** | Product and category performance |
| **Date** | Time-based analysis |
| **Market / Region** | Regional performance |
| **Supply Chain** | Forecast, inventory & operational analysis |

## 📊 Model Output

The data model provides the foundation for:

**DAX Measures → KPIs → Business Views → Interactive Dashboard → Business Insights**

### 🧠 Skills Demonstrated

**Data Modeling | Fact & Dimension Tables | Relationships | Star Schema | Power BI | DAX | Business Intelligence**