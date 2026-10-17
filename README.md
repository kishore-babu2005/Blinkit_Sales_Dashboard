# Blinkit Sales Dashboard (Power BI)

An interactive, single-page Power BI dashboard that analyzes Blinkit grocery sales across products and outlets, built to turn raw sales data into clear business insights.

[Blinkit Dashboard](images/dashboard.png.png)

## Objective

To understand what drives sales for a quick-commerce grocery business by answering questions such as:

- Which item types sell the most?
- Do outlet size, location tier and outlet type affect sales?
- Does fat content (Low Fat vs Regular) change sales?
- How have sales varied by outlet establishment year?

## Dashboard Features

- **KPI cards:** Total Sales, Average Sales, Number of Items, Average Rating
- **Metric slicer:** switch the charts between Total Sales, Avg Sales, No of Items and Avg Rating
- **Fat content analysis:** donut chart plus a Fat by Outlet Location chart
- **Item type analysis:** bar chart of sales for each item category
- **Outlet analysis:** donut chart by outlet size, funnel chart by location tier, and a summary table by outlet type
- **Trend analysis:** line chart of sales by outlet establishment year
- **Custom design:** Blinkit-themed layout with a branded background

## Key Insights

- Total sales were about **$1.20M** across roughly **9K items**, with an average sale of **$141** and an average rating of **3.9**.
- **Low Fat** items brought in about **$776K** against about **$425K** for Regular items, roughly two thirds of all sales.
- **Fruits and Vegetables** and **Snack Foods** were the top item categories, at about $0.18M each.
- **Tier 3** locations had the highest sales (about $472K), ahead of Tier 2 ($393K) and Tier 1 ($336K).
- **Supermarket Type1** outlets generated most of the sales (about $0.79M), while Grocery Stores contributed the least.
- Average sales and average rating stayed nearly flat across outlet types (about $140 and 4), so volume of items, not price per sale, explains the differences.
- Outlets established in **2018** show the sales peak, while **2012** is the lowest.

## Tools Used

- Power BI Desktop
- DAX (measures)
- Power Query (data cleaning and transformation)

## Dataset

BlinkIT Grocery sales data with fields such as Item Type, Item Fat Content, Item Visibility, Outlet Size, Outlet Location Type, Outlet Type, Outlet Establishment Year, Sales and Rating.

## Repository Structure

```
Blinkit-PowerBI-Dashboard/
├── blinkit.pbix        # Power BI report file
├── images/
│   └── dashboard.png   # Dashboard screenshot
└── README.md
```

## How to Use

1. Download `blinkit.pbix` from this repo.
2. Open it in Power BI Desktop (free to download from Microsoft).
3. Use the metric slicer at the top to explore the dashboard.

## Author

**Kishore Babu T**
[LinkedIn](https://www.linkedin.com/in/kishore-babu-5a29b83b5) | [GitHub](https://github.com/kishore-babu2005)
