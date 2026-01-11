# CODTECH Data Analysis Internship – Task 1

## Big Data Analysis Using Dask

### Description
This task demonstrates scalable big data analysis using a large dataset of 20,000 sales records.  
The dataset contains information about orders, categories, regions, sales, and profits.

### Dataset
- Format: JSON
- Records: 20,000
- Columns:
  - `Order_ID` : Unique order identifier
  - `Category` : Product category (Electronics, Furniture, Clothing, Food, Books)
  - `Region` : Region of sale (North, South, East, West, Central)
  - `Sales` : Sales amount in USD
  - `Profit` : Profit amount in USD

### Tools Used
- Python
- Dask (for scalable data processing)
- Matplotlib (for visualization)
- Pandas (for data manipulation)

### Analysis Performed
1. Loaded JSON dataset using Dask.
2. Calculated total rows to demonstrate dataset size.
3. Performed category-wise aggregation of sales.
4. Visualized total sales per category using a bar chart.

### Insights
- The analysis revealed the highest-performing product categories.  
- Electronics and Furniture categories generated the most sales.  
- Using Dask ensures scalable processing even for large datasets.

### Note
- The dataset was provided in JSON format to avoid CSV upload errors in Google Colab.
