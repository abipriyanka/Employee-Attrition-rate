
# 🧑‍💼 Employee Attrition Rate Analysis

This project analyzes employee attrition patterns based on HR data from "People Charm", aiming to uncover the key factors behind voluntary resignations and provide actionable insights for HR decision-makers.

---

## 📊 Dataset Overview

- **Total records**: 14,999 employees
- **Columns**: Satisfaction level, last evaluation, number of projects, average monthly hours, time at company, department, salary level, etc.
- **Target Variable**: `left` — where `1` means the employee left the company, and `0` means they stayed.

---

## 🎯 Key Objectives

- Identify patterns and drivers of employee attrition
- Quantify the impact of features like salary, workload, and evaluation scores
- Provide insights to improve retention and employee satisfaction

---

## 🔍 Key Findings

### 🥧 Attrition Distribution
![Attrition Distribution](images/attrition_pie_chart.png)

- **23.8%** of employees have left the company.

### 🏢 Attrition by Department
![Attrition by Department](images/attrition_by_dept.png)

- HR and Accounting departments experience the **highest attrition**.
- Management retains most of its employees (only 14.4% left).

### 💸 Attrition by Salary Level
![Attrition by Salary](images/attrition_by_salary.png)

- Employees with **low salaries** are **4x more likely** to leave compared to high earners.

### 🧠 Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

- Strongest negative correlation: **satisfaction level (-0.39)** — key driver of attrition.
- Positive correlation with time spent at company and average monthly hours.

---

## 🧪 Tools Used

- **Python** (Pandas, NumPy, Seaborn, Matplotlib)
- **Jupyter Notebook**
- **Visualization & Correlation Analysis**

---

## 📁 Files

- `python codes.ipynb` – Main notebook with all analysis steps
- `People Charm case.csv` – HR dataset with employee-level data
- `/images` – Folder containing all generated charts

---

## 📌 Future Work

- Train machine learning models to predict employee attrition
- Deploy a dashboard using Streamlit or Power BI
- Explore temporal trends in attrition rates

---

## 🤝 Contributions

Open to ideas, improvements, or visualizations! Feel free to fork, star ⭐, or create a pull request.

---

## 📜 License

This project is licensed under the MIT License.
