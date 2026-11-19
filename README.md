# Superstore Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing Superstore sales data using Python to identify sales patterns, understand business performance, and generate meaningful insights through Exploratory Data Analysis (EDA).

The project involves data cleaning, preprocessing, statistical analysis, and data visualization to explore sales performance across different product categories, regions, customer segments, and shipping modes.

## 🎯 Project Objectives

- Understand and explore the Superstore dataset.
- Clean and preprocess the raw data.
- Analyze sales performance across different categories and regions.
- Identify top-performing product sub-categories and states.
- Analyze shipping duration across different shipping modes.
- Examine monthly sales trends across different years.
- Visualize important patterns and business insights.

## 🛠️ Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 📂 Dataset Description

The dataset contains 9,800 records and 18 original columns.

Important attributes include:

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer Name
- Segment
- City
- State
- Region
- Category
- Sub-Category
- Product Name
- Sales

## 🔄 Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Loaded the data into a DataFrame.

### 2. Data Understanding
- Examined the first and last records.
- Checked dataset shape, column names, and data types.
- Generated descriptive statistics.
- Identified missing values and duplicate records.

### 3. Data Cleaning and Preprocessing
- Converted Order Date and Ship Date into datetime format.
- Handled missing Postal Code values using city-wise median values.
- Converted Postal Code into a five-character string format.
- Converted selected categorical columns into category data types.
- Calculated shipping duration in days.
- Extracted order year, month, and day of the week.
- Removed unnecessary columns for analysis.
- Cleaned text columns by removing extra spaces.

### 4. Exploratory Data Analysis (EDA)

Performed analysis on:

- Sales distribution.
- Total sales by product category.
- Sales by region.
- Sales by product sub-category.
- State-wise revenue performance.
- Monthly sales trends across years.
- Revenue by customer segment.
- Average order value by shipping mode.
- Shipping duration by shipping mode.

### 5. Data Visualization

Used Matplotlib and Seaborn to create:

- Histograms.
- Bar charts.
- Count plots.
- Line charts.
- Sales distribution visualizations.

## 📊 Key Analysis Areas

| Analysis | Purpose |
|---|---|
| Category Analysis | Compare sales across product categories |
| Regional Analysis | Understand regional sales performance |
| State Analysis | Identify high-performing states |
| Sub-Category Analysis | Compare product sub-category sales |
| Shipping Analysis | Understand delivery duration |
| Monthly Sales Analysis | Examine sales trends over time |
| Segment Analysis | Compare revenue across customer segments |

## 💡 Key Findings

- Technology generated the highest total sales among the three product categories.
- Standard Class had the highest average shipping duration.
- Same Day shipping had the lowest average shipping duration.
- Sales performance was analyzed across regions, states, and product sub-categories.
- Monthly sales trends were visualized across different years.

## 📁 Project Structure

```text
superstore_data_analysis_project/
│
├── project1_superstore_dataanalysis(1).ipynb
├── train.csv
└── README.md
```



## 🚀 Conclusion

This project demonstrates the use of Python for data cleaning, exploratory data analysis, and data visualization.

Through this analysis, I gained practical experience in working with real-world datasets, identifying patterns, and presenting meaningful insights using Python libraries.

## 👩‍💻 Author

**Nandana R**

GitHub: https://github.com/nandanar2004

