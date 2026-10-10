# 🐼 Python Pandas Group Practice

A hands-on Python project focused on practicing **Pandas GroupBy operations** using a student dataset. This repository helps beginners understand how to group, summarize, and analyze data with Python.

## 📌 About the Project

This repository contains practical exercises using Pandas and a student dataset. It is designed to strengthen data analysis skills through coding practice and hands-on learning.

## 🎯 Objectives

- Understand the Pandas `groupby()` function.
- Group data based on specific columns.
- Perform calculations on grouped data.
- Analyze student marks, attendance, and other attributes.
- Practice data manipulation and analytical thinking.
- Build a strong foundation for Data Analysis and Data Science.

## 🛠️ Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **Jupyter Notebook** — Interactive coding and practice
- **CSV** — Dataset storage format

## 📂 Files Included

| File | Description |
|---|---|
| `group.ipynb` | Jupyter Notebook containing Pandas GroupBy practice |
| `students.csv` | Dataset used for student data analysis |

## 📚 Topics Covered

- Loading CSV datasets using `pd.read_csv()`
- Exploring DataFrames
- Grouping data using `groupby()`
- Selecting columns from grouped data
- Calculating aggregate statistics
- Finding minimum, maximum, mean, and other summary values
- Analyzing student performance by category

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/PrathmeshSurwase6250/Python_Pandas_Group_Practice.git
```

### 2. Navigate to the project directory

```bash
cd Python_Pandas_Group_Practice
```

### 3. Create a virtual environment (recommended)

```bash
python3 -m venv .venv
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

### 4. Install the required libraries

```bash
python3 -m pip install pandas jupyter
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `group.ipynb` and run the cells to practice the examples.

## 💻 Example: Pandas GroupBy

```python
import pandas as pd

students = pd.read_csv("students.csv")

# Group students by course
groups = students.groupby("course")

# Calculate average marks for each course
average_marks = groups["marks"].mean()

print(average_marks)
```

*Note: This example assumes the dataset contains `course` and `marks` columns.*

## 🚀 Learning Outcomes

After completing this practice project, you will be able to:

- Understand how grouping works in Pandas.
- Summarize data using aggregation functions.
- Extract useful insights from datasets.
- Write cleaner and more efficient data analysis code.
- Prepare for more advanced Pandas exercises.

## 👨‍💻 Author

**Prathmesh Surwase**

- GitHub: [PrathmeshSurwase6250](https://github.com/PrathmeshSurwase6250)
- LinkedIn: [Connect on LinkedIn](https://www.linkedin.com/in/prathmesh-surwase-858a672b9)

## ⭐ Support

If you find this repository useful for learning Pandas, consider giving it a star on GitHub.

---

*Learning Python, practicing Pandas, and improving data analysis skills one exercise at a time.*
