 Power BI Superstore Sales Analysis Dashboard
 Project Overview

This project focuses on analyzing Superstore sales data to uncover insights about sales performance, profitability, customer segments, and regional performance.
The dashboard was created using Power BI, starting from data extraction from Kaggle to data cleaning, transformation, modeling, and visualization.

 Step-by-Step Project Process
 
1️⃣ Data Extraction from Kaggle

Visited Kaggle website and searched for Superstore Sales Dataset.

Downloaded the dataset in CSV format.

Extracted the ZIP file into a local system.

Verified dataset columns such as:

Order Date

Sales

Profit

Category

Sub-Category

Region

Segment

2️⃣ Loading Data into Power BI

Opened Power BI Desktop.

Clicked Home → Get Data → Text/CSV.

Selected the downloaded Superstore CSV file.

Clicked Transform Data to open Power Query Editor for preprocessing.

3️⃣ Data Cleaning Using Power Query

Several transformation steps were performed:

Remove Unnecessary Columns

Deleted columns not required for the analysis.

Handle Missing Values

Checked columns for null values and handled them accordingly.

Remove Duplicate Records

Steps:

Selected the entire dataset.

Clicked Remove Rows → Remove Duplicates.

Ensured each transaction is unique.

Change Data Types

Converted columns to appropriate data types:

Order Date → Date

Sales → Decimal Number

Profit → Decimal Number

Order ID → Text

Rename Columns

Renamed columns for better readability and analysis.

Apply Changes

Clicked Close & Apply to load the cleaned dataset into Power BI.

4️⃣ Data Modeling (Model View)

Opened Model View.

Checked table relationships.

Verified proper connections between tables.

Ensured correct one-to-many relationships for accurate calculations.

5️⃣ Date Formatting

Selected Order Date column.

Changed format to Date format.

Created Year and Month hierarchy.

Used this hierarchy for time trend analysis in line charts.

📊 Dashboard KPI Cards

The dashboard contains four key performance indicator (KPI) cards:

🟧 Total Sales

Shows the overall revenue generated.

Helps track overall business performance.

🟧 Total Orders

Displays the total number of orders placed.

Helps measure customer purchase activity.

🟧 Profit Margin

Indicates percentage of profit earned from total sales.

Helps measure profitability efficiency.

🟧 Total Profit

Shows the net profit generated from sales.

Helps evaluate financial success.

📈 Data Visualizations and Insights
6️⃣ Line Chart – Sales Trend by Month/Year

Used to track sales performance over time.

Insights:

Sales fluctuate across months indicating seasonal demand patterns.

Significant sales growth observed in 2016 compared to other years.

Helps businesses forecast future sales trends.

7️⃣ Clustered Column Chart – Sales by Region

Used to compare sales performance across regions.

Insights:

West region generated the highest sales.

East region also shows strong performance.

South region recorded the lowest sales performance.

8️⃣ Clustered Bar Chart – Sales by Category

Used to analyze product category contribution.

Insights:

Technology category generated the highest revenue.

Furniture contributed moderate sales.

Office Supplies maintained steady but lower revenue.

9️⃣ Bar Chart – Sales by Sub-Category

Used to identify top performing products.

Insights:

Chairs and Phones were top selling products.

Storage and Machines contributed moderate sales.

Tables generated comparatively lower revenue.

🔟 Pie Chart – Sales by Customer Segment

Used to visualize sales distribution among customer groups.

Segments:

Consumer

Corporate

Home Office

Insights:

Consumer segment contributes the largest share of total sales.

Corporate segment also generates significant revenue.

Home Office segment has the smallest contribution.

📊 Key Business Insights

Technology products are the major drivers of sales revenue.

West region shows strong market dominance.

Consumer customers contribute maximum revenue share.

Sales significantly increased in 2016 compared to previous years.

🛠 Tools Used

Power BI Desktop

Power Query

Kaggle Dataset

Data Modeling

Data Visualization

📁 Project Files

Power BI Dashboard (.pbix)

Superstore Dataset (.csv)

Project Documentation (README.md)
