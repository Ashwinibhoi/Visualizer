# Data Analysis & Visualization Program

## 📌 Project Overview

This project is a **Data Analysis & Visualization Program** developed using Python and Pandas.

The program provides a menu-driven interface to load a CSV dataset, explore data, perform DataFrame operations, handle missing values, generate descriptive statistics, create visualizations, and save visualizations.

---

## 🚀 Features

The program provides the following options:

1. **Load Dataset**
2. **Explore Data**
3. **Perform DataFrame Operations**
4. **Handle Missing Data**
5. **Generate Descriptive Statistics**
6. **Data Visualization**
7. **Save Visualization**
8. **Exit**

---

## 📂 Dataset Information

The program uses a CSV file containing sales-related information.

### Dataset Columns

| Column        | Description                    |
| ------------- | ------------------------------ |
| `Date`        | Date of the sale               |
| `Product`     | Product sold                   |
| `Region`      | Region where the sale occurred |
| `Quantity`    | Quantity of products sold      |
| `Unit_Price`  | Price of one unit              |
| `Sales`       | Total sales amount             |
| `Profit`      | Profit generated               |
| `Salesperson` | Name of the salesperson        |

The dataset contains **250 records**.

---

## 🔍 1. Load Dataset

The program allows the user to enter the path of a CSV file.

Example:

```text
Enter the path of the dataset (CSV file):
C:\Users\RW\Downloads\sales_data (1).csv
```

After successfully loading the dataset, the program displays a preview of the data.

### Sample Preview

```text
         Date     Product Region  Quantity  Unit_Price      Sales    Profit  Salesperson
0  2025-08-03  Headphones   East         8     3569.06   28552.49   5173.82  Rahul
1  2025-11-05    Keyboard  South         4     1671.43    6685.73   1873.19  Neha
2  2025-06-10     Monitor   West         6    10801.87   64811.21  22582.97  Priya
3  2025-06-19     Monitor   West         9    11498.95  103490.55  28187.78  Neha
4  2025-05-11  Headphones  North         3     3417.72   10253.17   3554.22  Rahul
```

---

## 🔎 2. Explore Data

The Explore Data section provides different ways to inspect the dataset.

### Available Operations

```text
1. Display the first 5 rows
2. Display the last 5 rows
3. Display column names
4. Display data types
5. Display basic info
6. Back to Main Menu
```

For example, selecting option `1` displays the first five rows of the dataset.

---

## 🧹 3. Handle Missing Data

The program can identify and manage missing values in the dataset.

### Available Operations

```text
1. Display rows with missing values
2. Fill missing values with mean
3. Drop rows with missing values
4. Replace missing values with a specific value
5. Back to Main Menu
```

### Missing Values Found

Some rows contain missing values in the `Profit` and `Region` columns.

Example:

```text
Rows with missing values:

10   2025-02-22   Laptop      West    8   69478.94   555831.52    NaN
25   2025-07-06   Tablet      NaN     1   20451.58    20451.58   7148.81
55   2025-05-09   Keyboard    South   5    1649.11      8245.57    NaN
100  2025-12-13   Monitor     NaN     2   12215.80     24431.60   5581.37
120  2025-08-08   Headphones  East    8    3228.43     25827.42    NaN
```

---

## 📊 4. Descriptive Statistics

The program provides statistical calculations for numerical columns.

### Available Operations

```text
1. Count
2. Mean
3. Median
4. Minimum
5. Maximum
6. Standard Deviation
7. Complete Statistics
8. Back to Main Menu
```

### Count Output

```text
Count:

Quantity      250
Unit_Price    250
Sales         250
Profit        247
dtype: int64
```

This shows that the dataset contains **250 values** for Quantity, Unit Price, and Sales, while Profit contains **247 non-missing values**.

---

## 📈 5. Data Visualization

The program provides an option to generate visualizations from the loaded dataset.

```text
6. Data Visualization
```

Visualizations can be used to understand sales, profit, quantity, products, regions, and other patterns in the dataset.

---

## 💾 6. Save Visualization

The program also provides an option to save the generated visualization.

```text
7. Save Visualization
```

If no visualization has been generated, the program displays:

```text
No visualization available to save!
Please generate a visualization first using option 6.
```

This ensures that the program only attempts to save a visualization after one has been created.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

---

## 📋 Main Menu

The complete main menu of the program is:

```text
========== Data Analysis & Visualization Program ==========
Please select an option:
1. Load Dataset
2. Explore Data
3. Perform DataFrame Operations
4. Handle Missing Data
5. Generate Descriptive Statistics
6. Data Visualization
7. Save Visualization
8. Exit
==========================================================
```

---

## ▶️ How to Run

### Step 1: Install Required Libraries

Open Command Prompt or Terminal and run:

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 2: Run the Python Program

```bash
python data_analysis.py
```

### Step 3: Load the CSV Dataset

Select option:

```text
1. Load Dataset
```

Then enter the path of your CSV file.

### Step 4: Analyze the Dataset

Use the available menu options to:

* Explore data
* Perform DataFrame operations
* Handle missing values
* Generate statistics
* Create visualizations
* Save visualizations

---

## 📁 Project Structure

```text
Data-Analysis-Visualization/
│
├── data_analysis.py
├── sales_data.csv
├── README.md
└── visualizations/
```

---

## 🎯 Project Objective

The main objective of this project is to demonstrate how Python data analysis libraries can be used to:

* Load and analyze CSV datasets
* Explore structured data
* Handle missing values
* Perform statistical analysis
* Create meaningful visualizations
* Save generated charts

---

## 👨‍💻 Conclusion

This project provides a simple and interactive way to perform **data analysis and visualization on sales data**. It demonstrates important concepts of Pandas, NumPy, Matplotlib, and Seaborn through a menu-driven Python application.

```text
Exiting the program. Goodbye!
```
