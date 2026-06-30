# 🦠 COVID-19 Data Analysis with Python

A data analysis project that explores the global COVID-19 dataset using **Python, Pandas, NumPy, and Matplotlib**. The project performs data cleaning, feature engineering, statistical analysis, and visualization to identify trends in COVID-19 cases and deaths across countries.

---

## 📌 Project Overview

This project analyzes the **Our World in Data (OWID) COVID-19 dataset** to answer questions such as:

- Which countries have the highest number of COVID-19 cases?
- Which countries reported the highest number of deaths?
- What is the death rate by country?
- How did daily cases change over time?
- How are COVID-19 cases distributed across months?

---

## 📂 Project Structure

```
COVID-19-Data-Analysis/
│
├── Covid.ipynb              # Jupyter Notebook
├── data/
│   └── owid-covid-data.csv  # Dataset
├── images/                  # Graph screenshots (optional)
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

**Source:**

Our World in Data (OWID)

https://ourworldindata.org/coronavirus

CSV File:

```
owid-covid-data.csv
```

---

## 🛠 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📋 Project Workflow

### 1. Data Loading

- Load COVID-19 dataset
- Explore rows and columns
- Understand dataset structure

---

### 2. Data Cleaning

Performed:

- Missing value handling
- Duplicate removal
- Datetime conversion
- Removed aggregated "World" records
- Created new feature:
  - `death_rate = total_deaths / total_cases`

---

### 3. Exploratory Data Analysis

The notebook includes:

### ✔ Dataset Overview

- Number of countries
- Dataset duration
- Missing values
- Numerical columns

---

### ✔ Top 10 Countries by Cases

Bar chart showing countries with highest total COVID-19 cases.

---

### ✔ Top 10 Countries by Deaths

Visualization of countries with highest recorded deaths.

---

### ✔ Top Death Rate Countries

Calculated using

```
death_rate = total_deaths / total_cases
```

Displayed as a horizontal bar chart.

---

### ✔ Daily Cases Trend

Line plot showing changes in daily COVID-19 cases over time.

---

### ✔ Monthly Cases

Monthly aggregation of new COVID-19 cases.

---

## 📈 Visualizations

The project generates:

- 📊 Top 10 Countries by Cases
- 📊 Top 10 Countries by Deaths
- 📉 Daily Cases Trend
- 📈 Monthly Cases
- 📊 Top Death Rate Countries

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/<your-username>/COVID-19-Data-Analysis.git
```

### Move into Project

```bash
cd COVID-19-Data-Analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Covid.ipynb
```

and run all cells.

---

## 📦 Requirements

```
numpy
pandas
matplotlib
jupyter
```

Or install manually:

```bash
pip install numpy pandas matplotlib notebook
```

---

## 📚 Python Concepts Used

- Data Cleaning
- DataFrame Operations
- GroupBy
- Aggregation
- Sorting
- Feature Engineering
- Datetime Handling
- Missing Value Handling
- Data Visualization

---

## 📸 Sample Output

The notebook generates graphs such as:

- Top 10 Countries by Cases
- Top 10 Countries by Deaths
- Death Rate Comparison
- Daily COVID Trend
- Monthly Cases Trend

---

## 🚀 Future Improvements

- Interactive dashboard using Plotly
- Streamlit web application
- Country-wise comparison tool
- Vaccination trend analysis
- Predictive modeling using Machine Learning
- Time series forecasting

---

## 👨‍💻 Author

**Aditya Yadav**
