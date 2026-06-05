# 🌍 Global Life Expectancy Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Tools-Jupyter-orange.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-green.svg)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-lightgrey.svg)

## 📌 Project Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) investigating global life expectancy. Using Python and data visualization libraries, the project examines the complex relationships between life expectancy and various economic, social, and health factors across Developed and Developing nations.

---

## 📑 Table of Contents
- [Dataset](#-dataset)
- [Technologies Used](#%EF%B8%8F-technologies-used)
- [Data Cleaning & Preprocessing](#-data-cleaning--preprocessing)
- [Key Visualizations](#-key-visualizations)
- [Getting Started](#-getting-started)
- [Usage](#-usage)

---

## 📊 Dataset
The analysis is based on the `Life Expectancy Data.csv` dataset, which includes health and economic metrics for various countries.

* **Total Records:** 2,938
* **Features (Columns):** 22 (16 float, 4 int, 2 object)
* **Categories:** Countries are divided into **Developing** (2,426 records) and **Developed** (512 records).

---

## 🛠️ Technologies Used
The notebook `elv-task5.ipynb` leverages the following Python data science stack:
* **[Pandas](https://pandas.pydata.org/):** Data ingestion, cleaning, and manipulation.
* **[NumPy](https://numpy.org/):** Numerical operations and array handling.
* **[Matplotlib](https://matplotlib.org/):** Foundational plotting.
* **[Seaborn](https://seaborn.pydata.org/):** Advanced statistical data visualization and aesthetic styling (`whitegrid`).

---

## 🧹 Data Cleaning & Preprocessing
To ensure accurate analysis, the data underwent the following preprocessing steps:
1. **Column Formatting:** Stripped extra whitespace from column names to prevent indexing and querying errors.
2. **Handling Missing Values:** Null values were detected in multiple features (e.g., Alcohol, Hepatitis B, GDP, Population). To preserve data integrity without skewing the distribution, all missing numerical values were imputed using the **median** of their respective columns.

---

## 📈 Key Visualizations
The analysis includes a variety of statistical plots to uncover trends:
1. **Life Expectancy Distribution:** A histogram showing the overall global frequency of life expectancy ages.
2. **GDP Spread:** Boxplots identifying the central tendency and outliers in Gross Domestic Product.
3. **Developed vs. Developing Nations:** A comparative boxplot highlighting the stark contrast in median life expectancy based on country status.
4. **Economic Impact (GDP vs. Life Expectancy):** Scatterplots mapping how national wealth correlates with longer lifespans.
5. **Educational Impact:** Visualizations examining the positive relationship between years of schooling and life expectancy.

---

## 🚀 Getting Started

### Prerequisites
To run this notebook locally, you will need Python installed along with Jupyter Notebook or JupyterLab.

### Installation
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/life-expectancy-eda.git](https://github.com/yourusername/life-expectancy-eda.git)
   cd life-expectancy-eda
