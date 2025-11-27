#### BlinkIT Sales Analytics – Power BI Dashboard

<div align="justify">A fully interactive Power BI dashboard designed to analyze BlinkIT’s grocery sales performance, outlet characteristics, customer ratings, and product category distribution.</div>


<div align="justify">This project covers the complete BI lifecycle from data cleaning and modeling to visualization development, insights generation and delivery of a business-ready dashboard.</div>

#### Project Development Steps

The project follows a structured end-to-end Business Intelligence workflow:

✔ Requirement Gathering / Business Understanding

✔ Data Walkthrough

✔ Data Connection

✔ Data Cleaning & Quality Checks

✔ Data Modeling

✔ Data Processing

✔ DAX Calculations

✔ Dashboard Layout Planning

✔ Visualizations & Chart Development

✔ Report Formatting

✔ Insights Extraction & Validation

#### Business Requirement

The objective is to perform a comprehensive analysis of BlinkIT’s grocery sales operations by leveraging Power BI’s analytical capabilities.

This dashboard helps stakeholders answer:

- Which product categories drive maximum sales?

- How do outlet type, size, and location affect revenue?

- What does the customer rating distribution reveal about satisfaction?

- How do fat-content categories influence sales patterns?

The insights support strategic decisions in product planning, marketing, and store operations.

#### Key Performance Indicators (KPIs)

- Total Sales – Total revenue generated

- Average Sales – Average revenue per item

- Number of Items – Unique products counted

- Average Rating – Customer satisfaction score

Visualization Requirements

1. Total Sales by Fat Content

- Objective: Compare revenue from Low Fat vs Regular items

- Chart Type: Donut Chart

2. Total Sales by Item Type

- Objective: Identify top-performing product categories

- Chart Type: Bar Chart

3. Fat Content by Outlet (Total Sales)

- Objective: Analyze sales contribution by outlet considering fat content

- Chart Type: Stacked Column Chart

4. Sales by Outlet Establishment Year

- Objective: Understand how outlet age impacts performance

- Chart Type: Line Chart

5. Sales by Outlet Size

- Objective: Compare revenue across Small, Medium, and Large outlets

- Chart Type: Donut/Pie Chart

6. Sales by Outlet Location

- Objective: Show revenue split across Tier 1, Tier 2, and Tier 3

- Chart Type: Funnel or Bar Chart

7. Metrics by Outlet Type

- Objective: Display KPIs grouped by outlet category

- Chart Type: Matrix / KPI Card Grid

#### Dashboard Output

![BlinkIT Dashboard](Outcomes/blinKit%20analysis%20dashboard%20outcome%20image.png)

#### Project Structure

BlinkIT Analysis/

├── Data/

│   └── BlinkIT Grocery Data.xlsx

├── Outcomes/

│   └── blinKit analysis dashboard outcome image.png

├── Resources/

│   ├── Average Rating Image.png

│   ├── Average Sales Image.png

│   ├── Background Blinkit.png

│   ├── Home Button Image.png

│   ├── Information Button Image.png

│   ├── Numbers of Items Image.png

│   ├── Reset Button Image.png

│   ├── Selected Data Button Image.png

│   └── Total Sales Images.png

└── BlinKit Analysis Dashboard.pbix

#### Insights Summary

📌 Sales Insights

- Regular-fat items account for the highest share of revenue.

- Snack foods, fruits, and household supplies are the top-performing categories.

- Medium-sized outlets generate the highest sales volume.

📌 Outlet Insights

- Tier 2 and Tier 3 locations outperform Tier 1 due to broader customer reach.

- Outlets established after 2015 show strong and consistent growth.

📌 Customer Insights

- The average rating remains around 3.9, indicating stable customer satisfaction.

- Higher-rated outlets consistently show stronger sales performance.

#### How to Use This Project

1. Download or clone the repository

2. Open the .pbix file in Power BI Desktop

3. Ensure the dataset path is valid

4. Click Refresh to load latest data

5. Interact using slicers:

- Outlet Size

- Item Type

- Location

- Fat Content

#### Dataset

The dataset is included inside the repository:

/Data/BlinkIT Grocery Data.xlsx

#### Contributing

Contributions are welcome!

You may enhance:

- DAX formulas

- Visual aesthetics

- Additional KPIs

- Page navigation

- UI/UX improvements

Steps:

- Fork the repo

- Create a new branch

- Commit changes

- Submit a PR
