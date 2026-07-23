# 📊 Alfido Tech Sales Performance Analysis

A comprehensive sales data analysis project built using **Python**, **Pandas**, **Matplotlib**, and **Seaborn** to analyze sales performance across regions, product categories, and time. This project includes data cleaning, KPI calculation, visualizations, and business recommendations.

---

## 📌 Project Objective

The primary objective of this project is to:

- Clean and prepare sales and order data
- Analyze sales performance across regions, categories, and time
- Identify best- and worst-performing products
- Discover seasonal sales trends
- Generate business insights
- Recommend tactical improvements for Alfido Tech

---

## 📂 Dataset

The dataset contains sales transaction details, including:

- Order ID
- Order Date
- Ship Date
- Customer Details
- Product Category
- Sub-Category
- Product Name
- Region
- State
- City
- Sales

> **Note:** The dataset does not include **Profit**, **Quantity**, or **Conversion** information. Therefore, Profit Margin and Conversion Metrics could not be calculated.

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📈 Project Workflow

### 1. Data Cleaning

- Removed duplicate records
- Handled missing values
- Converted date columns
- Created Year, Month, Quarter, and Weekday features
- Calculated Shipping Days
- Validated Sales data

---

### 2. Key Performance Indicators (KPIs)

The following KPIs were calculated:

- Total Revenue
- Total Orders
- Average Order Value
- Unique Customers
- Revenue by Category
- Revenue by Region
- Revenue by State
- Revenue by Segment

---

### 3. Exploratory Data Analysis

The project includes visualizations for:

- Monthly Sales Trend
- Sales by Category
- Sales by Region
- Sales by Segment
- Top 10 Products
- Bottom 10 Products
- Top States by Sales
- Top Cities by Sales
- Sales by Sub-Category
- Shipping Days Distribution
- Correlation Heatmap

---

## 📊 Sample Visualizations

- 📈 Monthly Sales Trend
- 📊 Category-wise Sales
- 🌍 Regional Sales
- 🏆 Top Selling Products
- 📉 Bottom Selling Products
- 🏙 State-wise Sales
- 📦 Shipping Time Distribution

---

## 💡 Business Insights

- Technology products contribute significantly to revenue.
- Consumer segment accounts for a large share of sales.
- Sales vary considerably across different regions.
- Certain products consistently outperform others.
- Shipping time analysis highlights opportunities for operational improvements.

---

## 🚀 Recommendations

1. Increase marketing investment for high-performing products.
2. Bundle slow-selling products with best-selling products.
3. Expand marketing campaigns in high-performing regions.
4. Launch seasonal promotions during peak sales periods.
5. Improve logistics to reduce shipping time and enhance customer satisfaction.

---

## 📁 Project Structure

```
Alfido-Tech-Sales-Analysis/
│
├── Sales_Analysis.ipynb
├── cleaned_superstore_sales.csv
├── README.md
├── dashboard/
│   ├── PowerBI.pbix
│   └── Tableau.twbx
├── images/
│   ├── monthly_sales.png
│   ├── category_sales.png
│   ├── region_sales.png
│   ├── top_products.png
│   └── shipping_distribution.png
└── Report.pdf
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/Alfido-Tech-Sales-Analysis.git
```

2. Open the notebook in **Google Colab** or **Jupyter Notebook**.

3. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

4. Upload the dataset.

5. Run all notebook cells sequentially.

---

## 📌 Results

- Cleaned and prepared sales dataset
- Generated KPIs
- Created insightful visualizations
- Identified top and bottom-performing products
- Analyzed regional and category-wise sales
- Provided actionable business recommendations

---

## 📚 Future Improvements

- Add Profit and Discount analysis
- Build an interactive Power BI/Tableau dashboard
- Forecast future sales using Machine Learning
- Customer segmentation analysis
- Sales prediction using time-series models

---

## 👨‍💻 Author

**Akash Yenni**

- B.Tech CSE (Data Science)
- Python | Data Analysis | Machine Learning | SQL | AWS

---

## ⭐ If you found this project useful, consider giving it a star!
