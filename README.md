# Myntra Sales Analytics Dashboard

An interactive **Power BI sales analytics dashboard** built to explore
e-commerce performance across orders, products, brands, categories,
discounts, time periods, and customer locations.

The report is designed to turn sales data into business-facing views
that support performance monitoring and merchandising decisions.

## Dashboard Preview

![Myntra Sales Analytics Dashboard]()

## Dashboard at a glance

The report includes six headline KPI cards and interactive visual
analysis.

  KPI                      Value shown in dashboard
  ---------------------- --------------------------
  Total Orders                                3,500
  Average Sales Amount                       538.24
  Total Sales Amount                          1.88M
  Total Revenue                                  3M
  Average Discount                            35.51
  Product Count                                  40

*These are the values visible in the supplied dashboard view. KPI values
can change when report filters or slicers are applied.*

## Business questions explored

-   How are sales distributed across brands?
-   How do sales and average discounts move month by month?
-   How does sales performance vary by weekday?
-   How do product categories contribute to sales over time?
-   Which brands and products contribute most to the selected sales
    metric?
-   How is revenue distributed across customer states?
-   How do order and sales KPIs change when filtering by year, category,
    brand, or sub-category?

## Dashboard features

### KPI monitoring

A compact KPI section surfaces order volume, average sales amount, total
sales amount, revenue, average discount, and product count.

### Brand performance

Brand-level visuals compare sales across brands, including Puma, H&M,
Roadster, Here&Now, Adidas, HRX, and Allen Solly.

### Time-based sales analysis

Monthly and weekday views help inspect sales patterns and the
relationship between sales and average discount.

### Category and product analysis

Category-based visuals compare sales across product categories and
years. Additional visuals show product and brand distribution.

### Geographic analysis

State-level visuals compare sales/revenue across customer states.

### Interactive filtering

The report includes slicers for: - Year - Product category - Brand
name - Sub-category

Use the slicers to explore the same metrics for a selected segment.

## Data model

The Power BI model contains the following tables:

-   `fact_orders` --- order-level fact table
-   `dim_customers` --- customer attributes
-   `dim_products` --- product, brand, and category attributes
-   `date_table` --- date and calendar attributes

The report uses measures grouped under `Key Measures`, including
measures for total orders, average sales amount, total sales amount,
average discount, and original price.

## Tools and concepts

-   **Power BI Desktop**
-   **DAX measures**
-   **Data modelling** with fact and dimension tables
-   **Interactive dashboards and slicers**
-   **KPI reporting**
-   **Sales, brand, category, product, time, and geographic analysis**

## Key analytical takeaways

The dashboard is structured to help a business user:

1.  Monitor overall order and sales performance through headline KPIs.
2.  Compare brand-level sales to identify leading brands in the selected
    filter context.
3.  Review monthly sales alongside average discount to investigate
    discount and sales patterns.
4.  Compare category performance across years.
5.  Explore weekday and state-level sales distribution.
6.  Narrow analysis by year, category, brand, and sub-category.

**Note:** The report layout exposes the analyses and measures above, but
a defensible claim about growth, causation, profitability, or a specific
best-performing segment requires validating the underlying filtered
data. This README therefore describes the available analysis rather than
asserting unsupported business conclusions.

## How to use

1.  Download or clone this repository.
2.  Keep `Myntra Data Analysis.pbix`, `Myntra dataset.xlsx`, and
    `Myntra_dashboard.png` in the repository root.
3.  Open `Myntra Data Analysis.pbix` in Power BI Desktop.
4.  Use the Year, Category, Brand Name, and Sub-category slicers to
    filter the report.
5.  Hover over charts to inspect the available data-point details.
6.  Compare KPI cards and charts as you change the filter context.

## Project structure

``` text
.
├── Myntra Data Analysis.pbix
├── Myntra dataset.xlsx
├── Myntra_dashboard.png
└── README.md
```

## Suggested extensions

-   Add year-over-year and month-over-month growth measures.
-   Add gross margin, net revenue, return rate, and average order value
    where the source data supports them.
-   Add inventory availability and sell-through analysis if inventory
    data is available.
-   Add customer cohort, repeat-purchase, and retention analysis if
    customer order history is available.
-   Add drill-through pages for brand, category, and state-level
    investigation.

------------------------------------------------------------------------

**Project:** Myntra Sales Analytics\
**Artifact:** Power BI interactive dashboard
