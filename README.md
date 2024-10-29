# Walmart Retail Data Pipeline
<div align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)

![Screenshot from 2024-10-29 11-19-30](https://github.com/user-attachments/assets/bbb3536b-11c5-43a5-8e2d-681a765cc06d)


</div>

### Data Pipeline Overview

**Project Goal:** Build a data pipeline for e-commerce data, focusing on grocery sales.

#### Technologies Used:
- **Jupyter Notebook:** For interactive data analysis and visualization.
- **SQL & PostgreSQL:** To query and manage the e-commerce data.
- **PyCharm Pro:** For Python development and executing the data pipeline.

#### Pipeline Steps:
1. **Extract:** Use SQL to fetch grocery sales data into a DataFrame (`grocery_sales`).
2. **Transform:** 
   - Fill missing numerical values.
   - Add a "Month" column.
   - Filter rows with weekly sales over $10,000.
   - Drop unnecessary columns.
3. **Aggregate:**
   - Calculate average monthly sales using the cleaned DataFrame.
4. **Load:** Save the cleaned and aggregated DataFrames to CSV files (`clean_data.csv` and `agg_data.csv`).
5. **Validation:** Check the existence of the saved CSV files in the current directory.

---
