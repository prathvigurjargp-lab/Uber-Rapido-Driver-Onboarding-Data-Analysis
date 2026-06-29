# 🚖 Uber & Rapido Driver Onboarding Data Analysis

An end-to-end **Data Analytics** project focused on cleaning and analyzing a real-world inspired ride-sharing driver onboarding dataset. This project demonstrates industry-standard data cleaning techniques using Python and Pandas before performing exploratory data analysis and visualization.

---

## 📌 Project Overview

Ride-sharing companies such as **Uber**, **Ola**, and **Rapido** collect thousands of driver applications every month. However, raw datasets often contain:

- Missing values
- Duplicate records
- Inconsistent text values
- Invalid numeric values
- Incorrect date formats
- Data quality issues

The goal of this project is to clean the dataset and prepare it for meaningful business analysis.

---

## 🎯 Business Problem

The company wants to understand:

- Which cities have the highest number of driver applications?
- How many duplicate or invalid applications exist?
- How can poor data quality impact business decisions?
- How can a clean dataset improve future analytics?

Before answering these questions, the dataset must be cleaned and standardized.

---

# 📊 Dataset Information

| Feature | Details |
|---------|---------|
| Dataset Type | Driver Onboarding Dataset |
| Industry | Ride Sharing |
| Inspired By | Uber, Ola, Rapido |
| Total Records | 50,000 |
| Total Columns | 33 |

---

# 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Git
- GitHub

---

# 🧹 Data Cleaning Process

The following data cleaning steps were performed.

## ✅ Step 1
Imported required Python libraries.

- Pandas
- NumPy

---

## ✅ Step 2
Loaded the dataset into a Pandas DataFrame.

---

## ✅ Step 3
Performed initial data exploration.

- Shape
- Info
- Data Types
- Missing Values
- Unique Values

---

## ✅ Step 4
Replaced fake missing values such as:

- NA
- N/A
- NULL
- NONE
- -
- Blank Spaces

with proper `NaN` values.

---

## ✅ Step 5
Removed records with missing Driver IDs.

Approximately **995 records** removed.

---

## ✅ Step 6
Standardized Platform Names.

Example:

```
uber
UBER
Uber
Uber Technologies
```

↓

```
Uber
```

Reduced **19 inconsistent values** into **4 standardized values**.

---

## ✅ Step 7
Corrected City Name Typos.

Example:

```
Ahmedbad
Ahemdabad
Ahmedabad
```

↓

```
Ahmedabad
```

Reduced **40 unique city values** into **10 standardized cities**.

---

## ✅ Step 8
Cleaned Age Column.

Handled:

- Negative ages
- Unrealistic ages
- Missing values
- Outliers

Approximately **3,894 invalid values** converted into missing values for further processing.

---

## ✅ Step 9
Standardized Boolean Columns.

Converted different representations into consistent values.

Example:

```
TRUE
True
YES
Yes
1
```

↓

```
1
```

and

```
FALSE
False
NO
0
```

↓

```
0
```

---

## ✅ Step 10
Standardized Categorical Columns.

Cleaned:

- Vehicle Type
- Vehicle Condition
- Experience Level
- Preferred Shift
- Interview Result
- Background Check Status
- Document Verification

---

## ✅ Step 11
Removed Impossible Numeric Values.

Validated business rules for columns such as:

- Ratings
- Experience
- Earnings
- Trips
- Scores

Invalid values were converted into missing values.

---

## ✅ Step 12
Converted Date Columns.

Converted:

- Interview Date
- Onboarding Date

into proper datetime format.

---

## ✅ Step 13
Removed Duplicate Driver IDs.

Approximately **2,752 duplicate records** removed.

---

## ✅ Step 14
Saved the cleaned dataset.

Output:

```
uber_rapido_driver_CLEAN.csv
```

---

# 📈 Project Summary

| Task | Result |
|------|--------|
| Original Records | 50,000 |
| Missing Driver IDs Removed | 995 |
| Duplicate Driver IDs Removed | 2,752 |
| Platform Values Standardized | 19 → 4 |
| City Values Standardized | 40 → 10 |
| Invalid Age Values Fixed | 3,894 |
| Boolean Columns Standardized | 2 |
| Categorical Columns Cleaned | 7 |
| Date Columns Converted | 2 |
| Final Dataset | Clean & Analysis Ready |

---

# 📂 Repository Structure

```
Uber-Rapido-Driver-Onboarding-Data-Analysis/

│
├── Dataset/
│   ├── uber_rapido_driver_dirty.csv
│   └── uber_rapido_driver_CLEAN.csv
│
├── notebooks/
│   └── Data_Cleaning.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

# 🚀 Next Phases

The upcoming stages of this project include:

- Exploratory Data Analysis (EDA)
- Business Insights
- SQL Analysis
- Power BI Dashboard
- KPI Reporting
- Business Recommendations

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Missing Value Handling
- Duplicate Detection
- Data Standardization
- Feature Validation
- Data Quality Assessment
- Python Programming
- Pandas
- NumPy
- Git & GitHub

---

# 📬 Connect With Me

**Prathvi Gurjar**

Aspiring Data Analyst | Python | SQL | Power BI | Data Analytics

- GitHub: https://github.com/prathvigurjargp-lab
- LinkedIn: https://www.linkedin.com/in/prathvi-gurjar/

---

## ⭐ If you found this project helpful, consider giving it a star!
