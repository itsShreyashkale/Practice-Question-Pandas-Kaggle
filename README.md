# 🐦 Pandas DataFrame Practice – Birds Dataset

This project contains a series of basic to intermediate **Pandas operations** performed on a sample dataset of birds. It is useful for **beginners**, **students preparing for exams**, and anyone looking to strengthen their data manipulation skills in Python.

---

## 📂 Dataset Description

The dataset is created using a Python dictionary and includes the following columns:

- **birds** → Type of bird (Cranes, plovers, spoonbills)
- **age** → Age of the bird (with some missing values)
- **visits** → Number of visits recorded
- **priority** → Priority status (yes/no)

Custom index labels are used: `a` to `j`.

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas 📊
- NumPy 🔢

---

## 📌 Operations Performed

The following operations are implemented step-by-step:

1. Create a DataFrame with custom index labels  
2. Display basic information (`info()`, `describe()`)  
3. View first 2 rows  
4. Select specific columns  
5. Select specific rows and columns  
6. Filter rows based on conditions  
7. Handle missing values (`NaN`)  
8. Apply multiple conditions (AND filtering)  
9. Filter values within a range  
10. Aggregate data (sum of visits)  
11. Group data and calculate mean  
12. Add and remove rows  
13. Count occurrences of each category  
14. Sort values by multiple columns  
15. Replace categorical values with numeric values  
16. Update specific entries in a column  

---

## 🧠 Key Concepts Covered

- DataFrame creation  
- Indexing (`loc`, `iloc`)  
- Filtering & boolean masking  
- Handling missing data  
- Aggregation & grouping (`groupby`)  
- Sorting  
- Data cleaning & transformation  

---

## 🚀 How to Run

1. Install required libraries:

```bash
pip install pandas numpy

2.Run Python Script or Jupyter Notebook
python filename.py
