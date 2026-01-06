# Ecommerce Sales EDA

Exploratory Data Analysis (EDA) on an e-commerce sales dataset using Python, pandas, and matplotlib.  
This project includes data cleaning, feature engineering, and visualizations for insights on product sales, daily trends, and city-wise performance.

---

## Dataset

- **File:** `Updated_sales.csv`
- **Columns:**
  - `Order ID`
  - `Product`
  - `Quantity Ordered`
  - `Price Each`
  - `Order Date`
  - `Purchase Address`

- **Description:** This dataset contains e-commerce transactions including order details, product information, and purchase location.

---

## Files in this Repository

| File | Description |
|------|-------------|
| `eda_sales_data.py` | Python script performing EDA on the sales dataset |
| `eda_sales_data.ipynb` | Jupyter notebook with step-by-step EDA, visualizations, and insights |
| `Updated_sales.csv` | Raw dataset used for analysis |
| `README.md` | Project description and instructions |

---

## Features & Analysis

- Data cleaning and handling missing values
- Numeric conversion of `Quantity Ordered` and `Price Each`
- `Sales` column creation: `Sales = Quantity Ordered * Price Each`
- Date and time-based feature extraction: Year, Month, Day, Hour
- City and State extraction from `Purchase Address`
- Product-wise, city-wise, and daily sales analysis
- Visualization using Matplotlib:
  - Histograms for quantity and price distribution
  - Bar charts for top products and city sales
  - Pie chart for most sold products
  - Line charts for daily and monthly sales trends

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/<username>/Ecommerce-Sales-EDA.git
cd Ecommerce-Sales-EDA
