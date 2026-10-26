# Exploratory Data Analysis on Amazon-Style Sales Data

> **Data note:** This project uses a synthetic Amazon-style dataset created for learning and portfolio practice. It is not actual Amazon company data.

## Objective
Practice a complete EDA workflow on sales records: inspect and clean data, analyze sales and profit by category, region, month, product, and discount, and translate findings into business recommendations.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## Project structure
```text
amazon-sales-eda-project/
├── data/
│   └── amazon_sales_raw.csv
├── notebooks/
│   └── amazon_sales_eda.ipynb
├── README.md
└── requirements.txt
```

## Dataset
The raw CSV contains 10,000 rows and 12 columns, including 300 intentionally duplicated rows and some missing values so the cleaning workflow can be demonstrated. The data is synthetic.

Columns: `order_id`, `order_date`, `product`, `category`, `region`, `quantity`, `price`, `discount`, `sales`, `cost`, `profit`, `payment_method`.

## Analysis plan
- Data inspection and quality checks
- Duplicate removal and missing-value handling
- Date/time feature engineering
- Sales and profit KPIs
- Grouped analysis by category, region, month, and product
- Discount band analysis
- Histograms, line charts, bar charts, scatter plot, and correlation heatmap
- Pivot table and business recommendations

## How to run
1. Download or clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open `notebooks/amazon_sales_eda.ipynb` and run cells from top to bottom.

## Results
After running the notebook, replace this section with your actual findings. Do not copy assumptions from a template—use the numbers and charts produced by your analysis.

## Limitations
Because the dataset is synthetic, findings demonstrate analytical workflow only and should not be presented as factual conclusions about Amazon's real sales.
