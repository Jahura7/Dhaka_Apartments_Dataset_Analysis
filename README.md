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
<img width="1441" height="541" alt="image" src="https://github.com/user-attachments/assets/57d422bf-3359-43f8-b632-84c2c45e7559" />
<img width="1914" height="402" alt="image" src="https://github.com/user-attachments/assets/a7c6aaae-7bbf-425f-bed9-f71c4aa86d5a" />
<img width="1920" height="446" alt="image" src="https://github.com/user-attachments/assets/995938ad-df43-46a5-9d28-ef54cc3806a6" />
<img width="1920" height="696" alt="image" src="https://github.com/user-attachments/assets/c287a260-425b-47b0-9ba1-e40832999652" />

### 2. Measures of Central Tendency

- Mean Rent
- Mean Apartment Size
- Median Rent
- Mode of Apartment Location
<img width="1920" height="870" alt="image" src="https://github.com/user-attachments/assets/3f24f9cf-3911-448b-8b72-36f92acefac8" />

### 3. Frequency Analysis

- Number of apartments in each location
- Percentage distribution of locations
<img width="1920" height="770" alt="image" src="https://github.com/user-attachments/assets/22e79290-f334-403e-9b4c-9bdbc9cd149b" />

### 4. Measures of Dispersion

- Range
- Variance
- Standard Deviation
<img width="1920" height="814" alt="image" src="https://github.com/user-attachments/assets/927b0dd7-a8fd-4dc1-a1cd-017f68e3910f" />

### 5. Correlation Analysis

Correlation between:

- Apartment Size vs Rent
- Bedrooms vs Rent
- Apartment Age vs Rent
<img width="1920" height="654" alt="image" src="https://github.com/user-attachments/assets/dd4b6fcf-8bda-477b-a83e-576ace93f31b" />

### 6. Correlation Heatmap

A heatmap is created to visualize relationships between:

- Size (sqft)
- Bedrooms
- Age of Apartment
- Rent
<img width="1920" height="870" alt="image" src="https://github.com/user-attachments/assets/4e1277ca-02df-4413-b0df-46f8e2c6080d" />

---

## 📈 Key Findings
The Correlation heatmap showes that-
- Apartment rent is **right-skewed**, meaning a few high-priced apartments increase the average rent.
- Rent is strongly influenced by apartment size(0.91) and moderately influenced by the number of bedrooms(0.67)
- Apartment age has weak negative correlation with rent(-0.31), indicating that older apartments tend to have slightly lower rents.
Overall, larger apartments with more bedrooms are generally more expensive to rent.

But Correlation is not causation. Bathrooms and rent rise together because bigger flats have both -> size is the real driver, not the bathroom.
 
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
git clone https://github.com/jahura7/Dhaka-Apartments-Analysis.git
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
