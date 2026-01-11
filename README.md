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


## Task 2: Predictive Analysis Using Machine Learning

### Objective
- Predict sales using product category, region, and profit as features.

### Model
- Linear Regression

### Steps
1. Load JSON dataset.
2. Encode categorical variables using one-hot encoding.
3. Split dataset into training and testing sets (80%-20%).
4. Train Linear Regression model.
5. Evaluate model performance using MSE and R2 score.
6. Visualize actual vs predicted sales.

### Insights
- Model performance can be improved with more features or advanced regression algorithms.

## Task 3: Interactive Dashboard Development

### Objective
To create an interactive dashboard using Power BI to visualize sales data and extract actionable insights.

### Dataset
- large_sales_data.csv
- Columns:
  - Order_ID
  - Category
  - Region
  - Sales
  - Profit

### Tool Used
- Power BI Desktop

### Dashboard Features
- Total Sales by Category (Bar Chart)
- Sales by Region and Category (Stacked Column Chart)
- Sales vs Profit Analysis (Scatter Chart)
- KPI Cards for Total Sales and Total Profit
- Interactive Slicers (List type) for Region and Category

### Insights
- Certain categories generate higher sales
- Some regions contribute more to overall profit
- Sales and profit show a positive trend relationship


## Task 4: Sentiment Analysis using NLP

### Objective
To perform sentiment analysis on textual data and classify reviews as Positive or Negative using Natural Language Processing techniques.

---

### Dataset
- Sample product reviews dataset
- Columns:
  - Review: Text data
  - Sentiment: Positive / Negative

---

### Tools & Technologies
- Python
- Google Colab
- Pandas
- NLTK
- Scikit-learn

---

### Workflow
1. Dataset creation and loading
2. Text preprocessing
   - Lowercasing
   - Removing punctuation
   - Stopword removal
3. Feature extraction using CountVectorizer
4. Model training using Naive Bayes classifier
5. Model evaluation using:
   - Classification Report
   - Confusion Matrix

---

### Results & Insights
- The model successfully classifies reviews into Positive and Negative sentiments
- Text preprocessing improves prediction performance
- The approach can be scaled to larger datasets such as tweets or product reviews

---


Thank you for the opportunity. I have successfully completed all the internship tasks and submitted them within the deadline.
