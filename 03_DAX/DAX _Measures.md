# 📐 AtliQ Hardware — DAX Measures

DAX was used to create **reusable business measures and KPIs** for the AtliQ Hardware Business Insights 360 dashboard.

## 🎯 Objective

Create measures to evaluate:

- Net Sales
- Gross Margin
- Net Profit
- Gross Margin %
- Net Profit %
- Forecast Accuracy
- Sales Performance
- Year-over-Year Growth
- Target vs Actual Performance

## 📊 Core Measures

### 💰 Net Sales

```DAX id="8d5n2s"
Net Sales =
SUM(fact_sales_monthly[net_sales_amount])
```

### 📈 Gross Margin

```DAX id="t7zq4a"
Gross Margin =
[Net Sales] - [Total COGS]
```

### 📊 Gross Margin %

```DAX id="5j8m0c"
Gross Margin % =
DIVIDE(
    [Gross Margin],
    [Net Sales],
    0
)
```

### 💵 Net Profit

```DAX id="x1s6k9"
Net Profit =
[Gross Margin] - [Total Operational Expenses]
```

### 📉 Net Profit %

```DAX id="r4h2py"
Net Profit % =
DIVIDE(
    [Net Profit],
    [Net Sales],
    0
)
```

## 🎯 Performance Analysis

DAX measures were also used to compare actual performance with targets and benchmarks.

### Variance

```DAX id="j6v3qa"
Variance =
[Actual] - [Target]
```

### Variance %

```DAX id="n2x8cw"
Variance % =
DIVIDE(
    [Actual] - [Target],
    [Target],
    0
)
```

## 📅 Time Intelligence

Time-based calculations were created for:

- Year-over-Year growth
- Previous-year performance
- Monthly trends
- Year-to-date analysis
- Period comparisons

Example:

```DAX id="p9k4tx"
Net Sales LY =
CALCULATE(
    [Net Sales],
    SAMEPERIODLASTYEAR('Date'[Date])
)
```

```DAX id="m3w7bf"
Net Sales YoY % =
DIVIDE(
    [Net Sales] - [Net Sales LY],
    [Net Sales LY],
    0
)
```

## 🚚 Supply Chain Metrics

DAX was used to support supply chain performance analysis, including:

- Forecast accuracy
- Forecast quantity
- Actual sales quantity
- Net error
- Absolute error
- Out-of-stock analysis

Example:

```DAX id="c8r5hz"
Forecast Accuracy % =
1 -
DIVIDE(
    [Absolute Error],
    [Forecast Quantity],
    0
)
```

## 🧠 DAX Concepts Demonstrated

- `SUM`
- `DIVIDE`
- `CALCULATE`
- `SAMEPERIODLASTYEAR`
- Filter Context
- Time Intelligence
- KPI Measures
- Variance Analysis
- Percentage Calculations
- Business Metrics

## 📊 DAX Output

These measures power the project's major business views:

**Finance → Sales → Marketing → Supply Chain → Executive Summary**

### 🛠️ Skills Demonstrated

**DAX | Power BI | KPI Development | Time Intelligence | Financial Analysis | Sales Analytics | Supply Chain Analytics**