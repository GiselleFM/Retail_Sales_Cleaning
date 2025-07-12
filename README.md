
# 🧼 Retail Sales Cleaning and Preparation

This project focuses on cleaning and transforming raw retail store sales data to prepare it for analysis and visualization. The notebook demonstrates practical data wrangling techniques using **Pandas** and **NumPy**.

---

## 📁 Dataset

The dataset includes retail transaction records with the following columns:
- `Transaction Date`
- `Category`
- `Item`
- `Quantity`
- `Price Per Unit`
- `Total Spent`
- `Discount Applied`

---

## 🎯 Objectives

- Identify and handle missing values
- Use logic-based rules and group statistics to impute data
- Convert columns to appropriate data types
- Generate clean, consistent, and analysis-ready data

---

## 🔧 Techniques Used

- Filled missing `Price Per Unit` values by mapping from `Item`
- Imputed `Quantity` using the average quantity per price point
- Recalculated `Total Spent` where sufficient data was available
- Inferred `Discount Applied` by comparing calculated and reported totals
- Reconstructed missing `Item` names using combinations of `Category` and `Price Per Unit`
- Converted date strings to datetime format and ensured numeric consistency

---

## 🧪 Technologies

- Python 3
- Pandas
- NumPy
- Jupyter Notebook

---

## 📊 Potential Next Steps

- Add EDA (Exploratory Data Analysis) with visualizations
- Build time series plots (orders per month, top categories)
- Create a Power BI dashboard for business insights

---

## 📁 File Structure

```
Sales_Cleaning.ipynb    # Main Jupyter notebook
retail_store_sales.csv  # Input dataset (not included)
```

---

## 🚀 How to Run

1. Clone this repository
2. Ensure the dataset file is in the working directory
3. Run the notebook in Jupyter or VSCode

```bash
pip install pandas numpy
jupyter notebook
```

---

## 👩‍💼 Author

**Giselle Freitas Moura**  
📫 [gisellinhapb@gmail.com](mailto:gisellinhapb@gmail.com)  
🌎 [LinkedIn](https://www.linkedin.com/in/seu-perfil) *(update with your real link)*
