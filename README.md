# E-commerce-data-processing
A polished Pandas-based e-commerce data processing project that combines Orders, Customers, and Products using merge() and concat(), applies data transformations with apply(), performs DateTime analysis, and exports a clean 120-record, 23-column dataset ready for further analysis.

# 🛒 E-commerce Data Processing with Pandas

A practical **Python & Pandas project** that combines Orders, Customers, and Products datasets into a clean, structured, and analysis-ready dataset.

## 📌 Overview

This project demonstrates essential Pandas data-processing techniques:

* Load CSV datasets with `read_csv()`
* Combine DataFrames using `concat()`
* Join related datasets using `merge()`
* Create calculated columns with `apply()`
* Process dates using Pandas DateTime
* Perform basic data-quality checks
* Export the final dataset as CSV

## 📂 Datasets

| File            | Description                |
| --------------- | -------------------------- |
| `Orders.csv`    | Order and transaction data |
| `Customers.csv` | Customer information       |
| `Products.csv`  | Product information        |

The datasets are connected using `Customer_ID` and `Product_ID`.

## ⚙️ Processing

The project:

1. Loads the three CSV files.
2. Inspects their structure.
3. Demonstrates `concat()`.
4. Merges Orders with Customers and Products.
5. Converts `Order_Date` to DateTime.
6. Extracts year, month, day, weekday, and week.
7. Calculates `Total_Amount = Quantity × Unit_Price`.
8. Creates `Order_Value_Band` for transaction categorization.
9. Checks data quality.
10. Exports the processed dataset.

## 📊 Output

**120 records × 23 columns**

The final dataset contains integrated order, customer, and product information along with calculated and DateTime-based features.

### Key Added Features

* `Total_Amount`
* `Order_Year`
* `Order_Month`
* `Order_Month_Name`
* `Order_Day`
* `Order_Day_Name`
* `Order_Week`
* `Order_Value_Band`

## 🔎 Observations

* The three datasets were successfully integrated into one DataFrame.
* Customer and product details are available at the order level.
* DateTime features make the dataset suitable for time-based analysis.
* `Total_Amount` provides a transaction-level sales metric.
* `Order_Value_Band` provides simple transaction segmentation.

## ✅ Conclusion

The project successfully converts multiple raw e-commerce datasets into a **clean, structured, and analysis-ready dataset** using Pandas.

The resulting CSV can be used for further **sales analysis, customer segmentation, product analysis, visualization, and dashboard development**.

## 📁 Repository Structure

```text
E-commerce-Data-Processing/
│
├── Ecommerce_Data_Processing.ipynb
├── Orders.csv
├── Customers.csv
├── Products.csv
├── Processed_Ecommerce_Dataset_GitHub.csv
└── README.md
```

## ▶️ Run the Project

### Google Colab

Upload the notebook and three CSV files to Colab, then run the cells sequentially.

### Jupyter Notebook

```bash
pip install pandas
jupyter notebook
```

Keep the notebook and CSV files in the same directory.

## 🛠️ Tools

**Python • Pandas • Jupyter Notebook • Google Colab • GitHub**

## 🚀 Future Scope

* Sales and revenue analysis
* Product and category performance
* Customer segmentation
* Regional analysis
* Time-based sales trends
* Data visualization
* Power BI / Tableau dashboard

## 👨‍💻 Author

**NAVNEET KAUR**

Python & Data Analysis Project

⭐ **If you find this project useful, consider starring the repository.**
