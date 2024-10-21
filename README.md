# Coffee Sales Dashboard Project

<div align="center"> <img src="Coffee Sales Dashboard.png" alt="Dashboard Overview" width="80 /> </div>

### Overview
This project involves building an interactive sales dashboard in Excel to analyze coffee sales across different regions. The dashboard allows users to visualize key sales metrics, filter data dynamically, and gain actionable insights into sales trends, top-performing customers, and product performance.

### Objectives
- Analyze coffee sales data to provide key business insights.
- Visualize total sales, sales by country, and top customers.
- Enable interactive data exploration through filters and slicers.
  
### Tools and Techniques
- Excel (Pivot Tables, Pivot Charts, Slicers)
- XLOOKUP, INDEX MATCH for data enrichment.
- Data cleaning and transformation techniques (e.g., removing duplicates, formatting columns).
  
### Data Preparation
1. Imported data from three Excel sheets:

- Orders: Contains order details (ID, date, customer ID, product ID, quantity).
- Customers: Contains customer information (name, email, country, loyalty card status).
- Products: Contains product details (coffee type, size, unit price, profit).
  
2. Data Enrichment:

- Applied XLOOKUP and INDEX MATCH to bring in additional customer and product information.
- Calculated total sales per order using basic arithmetic operations.
  
3. Data Cleaning:

- Reformatted dates for clarity.
- Added units (e.g., "kilo") for better data understanding.
- Removed duplicates and converted the data into a manageable table format.
  
### Dashboard Features
#### KPIs:

- Total sales over time.
- Sales by region (US, UK, Ireland).
- Top five customers based on sales.

#### Charts:

- Line chart showing total sales trends over time.
- Bar chart visualizing sales by region.
- Top 5/Bottom 5 customers displayed in bar charts for quick insights into performance.
  
#### Interactive Elements:

- Timeline filter for date-based exploration.
- Slicers for filtering data by roast type, package size, and customer loyalty status.
- Interactive filtering to dynamically explore sales metrics.
  
### Key Insights
- Sales Trends: Sales fluctuated based on region and time, with peak sales periods easily identifiable through the dashboard.
- Top Performers: Certain customers and coffee types consistently ranked as top performers.
- Business Impacts: The dashboard provides valuable insights into underperforming products and customer segments, helping inform business decisions.
  
### How to Use
1. Open the Excel dashboard file.
2. Use the slicers and timeline filter to dynamically filter data based on regions, dates, and product details.
3. View insights through the interactive pivot charts and tables.
