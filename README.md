# Indian-world-economic-sectors-project
Python-based EDA of India &amp; World Economic Sectors data using Pandas, NumPy, Seaborn, and Matplotlib.
# 📊 Exploratory Data Analysis on India & World Economic Sectors

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on an India & World Economic Sectors dataset using Python.

The analysis focuses on understanding **GDP, employment, and economic growth** across different countries, economic sectors, and years. The project includes data loading, cleaning, statistical analysis, grouping, pivot-table analysis, and data visualization.

## 🎯 Objectives

* Understand the structure and characteristics of the dataset.
* Clean and prepare the data for analysis.
* Identify and handle missing values.
* Perform statistical analysis on economic indicators.
* Analyze GDP by country and economic sector.
* Analyze employment percentage across countries and sectors.
* Analyze growth rates across countries and sectors.
* Explore GDP trends across different years.
* Create visualizations to communicate insights.

## 📂 Dataset

The dataset contains **15,000 records and 6 columns**.

### Columns

| Column             | Description                        |
| ------------------ | ---------------------------------- |
| `Country`          | Country represented in the dataset |
| `Year`             | Year of the economic record        |
| `Sector`           | Economic sector                    |
| `GDP_Value_USD_Bn` | GDP value in USD billions          |
| `Employment_%`     | Employment percentage              |
| `Growth_Rate_%`    | Economic growth rate percentage    |

The dataset contains **8 countries** and **3 economic sectors**: Agriculture, Manufacturing, and Services.

## 🛠️ Technologies & Libraries

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 📈 Seaborn
* Jupyter Notebook

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

* Checked the first and last records.
* Checked dataset shape and column names.
* Removed extra spaces from column names.
* Checked data types.
* Identified missing values.
* Checked duplicate records.
* Checked unique values.
* Removed `%` symbols from the `Employment_%` column.
* Converted `Employment_%` and `Growth_Rate_%` into numeric data types.
* Filled missing values in `Employment_%` and `Growth_Rate_%` using their respective column means.

The original dataset contained **1,920 missing Employment values** and **2,164 missing Growth Rate values**; after handling them, no missing values remained.

## 📊 Statistical Analysis

Statistical analysis was performed using Pandas, including:

* Mean
* Median
* Minimum
* Maximum
* Standard deviation
* Descriptive statistics

The average GDP value in the dataset is approximately **2,529.34 USD billion**, while the median GDP value is **2,527 USD billion**.

## 🔎 Exploratory Data Analysis

### 🌍 Country-wise Analysis

The project analyzes:

* Total GDP by country
* Average GDP by country
* Average employment percentage by country
* Average growth rate by country

### 🏭 Sector-wise Analysis

The analysis compares:

* Total GDP by sector
* Average growth rate by sector
* Average employment percentage by sector

The three sectors analyzed are:

* Agriculture
* Manufacturing
* Services

### 📅 Year-wise Analysis

The project also analyzes total GDP across different years to understand changes over time. The dataset covers the years **2010–2023**.

### 🔄 Country & Sector Analysis

A pivot table was created to compare total GDP across countries and economic sectors.

## 📈 Data Visualization

The project uses **Seaborn and Matplotlib** to visualize the analysis.

Visualizations include:

* 📊 Bar charts
* 🥧 Pie charts
* Country-wise GDP comparisons
* Sector-wise comparisons
* Economic data visualizations

The notebook also uses the `ggplot` plotting style for visualization.

## 📁 Project Structure

```text
India-World-Economic-Sectors-EDA/
│
├── Nittin_rawat_EDA_project.ipynb
├── India_World_Economic_Sectors_Unclean.csv
└── README.md
```

## 💡 Key Skills Demonstrated

This project demonstrates practical knowledge of:

* Data Loading
* Data Cleaning
* Missing Value Handling
* Data Type Conversion
* Duplicate Checking
* Statistical Analysis
* GroupBy Operations
* Pivot Tables
* Data Aggregation
* Exploratory Data Analysis
* Data Visualization
* Python for Data Analytics

## 👨‍💻 Author

**Nitin Rawat**

Aspiring Data Analyst

### 📧 Contact

`nr7060968771@gmail.com`

---

⭐ If you find this project useful, feel free to explore the notebook and provide feedback.
