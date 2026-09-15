# 🛒 Retail Sales Analytics Dashboard — Power BI

## Project Overview
An interactive Power BI dashboard analyzing 341,068 
retail sales records across multiple suppliers, product 
categories and sales channels. This project demonstrates 
advanced Power BI skills including DAX measures, 
interactive slicers and multi-channel sales analysis.

## Tools Used
- **Power BI Desktop** — Dashboard development
- **Power BI Service** — Cloud publishing
- **DAX** — Calculated measures
- **Power Query** — Data cleaning and transformation

## Dataset
- **Rows:** 341,068 sales records
- **Columns:** 9 fields covering sales channels, 
  suppliers and product categories
- **Fields:** Year, Month, Supplier, Item Code, 
  Item Description, Item Type, Retail Sales, 
  Retail Transfers, Warehouse Sales

## DAX Measures Created

| Measure | Formula | Purpose |
|---|---|---|
| Total Retail Sales | SUM(RETAIL SALES) | Direct retail revenue |
| Total Warehouse Sales | SUM(WAREHOUSE SALES) | Warehouse channel revenue |
| Total Transfers | SUM(RETAIL TRANSFERS) | Inter-store transfers |
| Total Revenue | SUM all channels | Combined revenue — all channels |
| Avg Monthly Sales | AVERAGE(RETAIL SALES) | Monthly performance baseline |

## Dashboard Features

| Visual | Insight |
|---|---|
| 5 KPI Cards | Total Revenue, Retail Sales, Warehouse Sales, Transfers, Monthly Average |
| Bar Chart | Revenue by Item Type |
| Line Chart | Monthly Retail Sales Trend |
| Bar Chart | Top 10 Suppliers by Revenue |
| Donut Chart | Sales split by channel |
| Slicer — Year | Filter all visuals by year |
| Slicer — Item Type | Filter all visuals by product category |

## Key Business Insights
- **Total Retail Sales: 2.37M** across all periods
- **Top 10 suppliers** identified by revenue contribution
- **Sales channel breakdown** reveals distribution 
  between retail, warehouse and transfer activity
- **Monthly trends** show seasonal patterns 
  across product categories
- **Interactive slicers** enable dynamic filtering
