# Sales and Logistics Analysis Dashboard

## Project Overview

This project focuses on analyzing sales and logistics data. The dashboard, created in Power BI, showcases key metrics related to sales performance, logistics efficiency, payments, and customer feedback. The goal is to deliver a user-friendly and visually appealing interface that enables stakeholders to explore data and make informed decisions.

### Project Link
You can access the Power BI dashboard here:  
[Sales and Logistics Dashboard](https://drive.google.com/file/d/17aAbr6_N3lK5JODI2rCJ-b7Vuv10wTJ-/view?usp=drive_link)

---

## Project Concept

As a hired data analyst, I was tasked with creating interactive dashboards in Power BI using provided datasets. The project required a combination of data modeling, DAX calculations, and UX/UI design to deliver a comprehensive and intuitive tool for analyzing sales and logistics performance.

---

## Project Goals

The project aimed to demonstrate the following skills:
1. **Prototyping and UX/UI Design**: Creating a visually consistent and user-friendly interface.
2. **Data Visualization**: Selecting and formatting appropriate charts and graphs.
3. **DAX Calculations**: Implementing scalar and table-based DAX expressions, including iterative functions.
4. **Data Modeling**: Managing relationships, transforming data, and creating calculated columns.
5. **Power BI Features**: Utilizing groups, hierarchies, filters, cross-filtering, tooltips, drill-through pages, and content switching.

---

## Key Features of the Dashboard

### 1. **Interface**
- A cohesive theme with consistent colors and fonts.
- Logical organization of data into tabs and blocks.
- Interactive elements such as buttons, bookmarks, pop-ups, and navigation tools.
- Clear and concise titles and labels for all dashboard components.

### 2. **Metrics**
#### Sales Metrics:
- **Average Order Value**: The average amount spent per transaction.
- **Revenue**: Total income from completed deals.
- **Deals in Progress**: The value of ongoing transactions.
- **Conversion Rate**: Ratio of completed deals to potential leads.
- **Sales Geography**: Geographic distribution of sales.
- **Sales Rankings**: Performance rankings of sales teams or products.
- **Active Customer Base**: Number of unique customers who completed at least one transaction.

#### Logistics Metrics:
- **On-Time Delivery Rate**: Percentage of deliveries completed on time.
- **Shipping Cost per Unit**: Total shipping cost divided by the number of units shipped.
- **Average Order Processing Time**: Time taken to process an order from receipt to readiness for shipment.
- **Average Order Cycle Time**: Average time between order placement and delivery.

### 3. **Data Modeling and Transformation**
- Established relationships between tables.
- Denormalized the `olist_orders_dataset` table using Power Query to create a sales funnel.
- Removed unnecessary fields to streamline the dataset.
- Created a calculated column in the `olist_products_dataset` table to categorize products.

### 4. **Functionality**
- Dynamic date filter and two additional metric filters.
- Year-over-year comparison showing growth or decline.
- Content switching implemented using DAX.

### 5. **Visualizations**
- **Four Tabs**: Sales, Logistics, Payments, and Reviews.
- **Sales Funnel**: Visualizes the stages of the sales process (e.g., order created, order confirmed) with dynamic filtering by date.
- **Order Dynamics**: Tracks the growth or decline in order volume and value over time.
- **Geographic Map**: Displays sales or logistics metrics on a map.
- **Payments Tab**: Analyzes payment-related data.
- **Reviews Tab**: Provides insights into customer feedback.

---

## How to Use the Dashboard

1. Open the Power BI dashboard using the provided link.
2. Use the dynamic date filter and additional metric filters to customize the view.
3. Navigate between the Sales, Logistics, Payments, and Reviews tabs to explore different aspects of the data.
4. Hover over visualizations to view tooltips and additional details.
5. Utilize interactive elements such as buttons and bookmarks for a seamless experience.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

