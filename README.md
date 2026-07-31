# Dhaka_Apartments_Dataset_Analysis
# 🏠 Dhaka Apartments Dataset Analysis

A beginner-friendly data analysis project that explores apartment rental data in Dhaka using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. This project demonstrates basic descriptive statistics and correlation analysis commonly used in Exploratory Data Analysis (EDA).

---

## 📌 Project Overview

The notebook analyzes a dataset of apartments in Dhaka to answer statistical questions such as:

- What is the average apartment rent?
- What is the average apartment size?
- What is the median rent?
- Is the rent distribution skewed?
- Which location has the most apartments?
- What percentage of apartments are in each location?
- What is the range, variance, and standard deviation of rent?
- How strongly are apartment size and rent related?
- Which variables have the strongest correlation?

---

## 📂 Dataset

The notebook uses the following dataset:

- **File:** `dhaka_apartments.xlsx`

Example columns include:

- `rent`
- `size_sqft`
- `bedrooms`
- `age_years`
- `location`
<img width="764" height="477" alt="image" src="https://github.com/user-attachments/assets/27fd9238-0d39-4286-820c-1a8eeffc2783" />

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Analysis Performed

### 1. Data Inspection

- View first few records
- Dataset shape
- Data types
- Summary statistics
- Missing value check
- Duplicate value check

### 2. Measures of Central Tendency

- Mean Rent
- Mean Apartment Size
- Median Rent
- Mode of Apartment Location

### 3. Frequency Analysis

- Number of apartments in each location
- Percentage distribution of locations

### 4. Measures of Dispersion

- Range
- Variance
- Standard Deviation

### 5. Correlation Analysis

Correlation between:

- Apartment Size vs Rent
- Bedrooms vs Rent
- Apartment Age vs Rent

### 6. Correlation Heatmap

A heatmap is created to visualize relationships between:

- Size (sqft)
- Bedrooms
- Age of Apartment
- Rent

---

## 📈 Key Findings

- Apartment rent is **right-skewed**, meaning a few high-priced apartments increase the average rent.
- Apartment **size has a strong positive correlation with rent**.
- Larger apartments generally have higher rental prices.
- Correlation analysis helps identify which apartment features most influence rent.

---

## 📷 Visualization

The project includes:

- Correlation Heatmap

Example:

- Heatmap of numerical variables using Seaborn

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/Dhaka-Apartments-Analysis.git
```

2. Navigate to the project folder

```bash
cd Dhaka-Apartments-Analysis
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

4. Place the dataset (`dhaka_apartments.xlsx`) in the project directory.

5. Open the notebook

```bash
jupyter notebook Dhaka_Apartments_Dataset_Analysis.ipynb
```

---

## 📁 Project Structure

```
Dhaka-Apartments-Analysis/
│
├── Dhaka_Apartments_Dataset_Analysis.ipynb
├── dhaka_apartments.xlsx
├── README.md
└── images/
    └── heatmap.png (optional)
```

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Load Excel datasets using Pandas
- Explore datasets
- Calculate descriptive statistics
- Analyze data distribution
- Measure data variability
- Compute correlation coefficients
- Create informative visualizations using Seaborn

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Correlation Analysis
- Data Visualization
- Python Programming
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 👩‍💻 Author

**Jahura Begum**

- Aspiring Data Analyst
- Learning Python, SQL, Power BI, and Data Analytics
- Building projects to strengthen practical data analysis skills

---

## ⭐ If you found this project useful, consider giving it a star!
