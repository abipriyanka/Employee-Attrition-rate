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

### 🔸 Overall Attrition Rate
- **23.8%** of employees have left the company.

### 🔸 Top Features Positively Correlated with Attrition
| Feature              | Correlation |
|----------------------|-------------|
| Time spent at company| +0.145      |
| Average monthly hours| +0.071      |
| Number of projects   | +0.024      |

> Employees with **longer tenure and heavier workloads** were more likely to leave.

### 🔸 Top Features Negatively Correlated with Attrition
| Feature              | Correlation |
|----------------------|-------------|
| Satisfaction level   | **-0.39**   |
| Work accident        | -0.15       |
| Promotion in 5 years | -0.06       |

> Lower satisfaction is the **strongest negative signal** — unhappy employees are much more likely to leave.

---

## 🏢 Department-wise Attrition

| Department     | Attrition % |
|----------------|-------------|
| HR             | 29.1%       |
| Accounting     | 26.6%       |
| Technical      | 25.6%       |
| Sales          | 24.5%       |
| Management     | **14.4%**   |

> **HR and Accounting** show the **highest turnover rates**, while **Management** has the lowest.

---

## 💸 Salary-wise Attrition

| Salary Level | Attrition % |
|--------------|-------------|
| High         | **6.6%**    |
| Medium       | 20.4%       |
| Low          | **29.7%**   |

> Employees earning **lower salaries are over 4x more likely** to leave than high earners.

---

## 🧪 Tools Used

- **Python** (Pandas, NumPy)
- **Data Analysis** (EDA, Correlation)
- **Jupyter Notebook**

---

## 📁 Files

- `python codes.ipynb` – Main notebook with all analysis steps
- `People Charm case.csv` – Clean HR dataset with employee-level data

---

## 📌 Future Work

- Add machine learning models to predict attrition
- Explore time-series trends in employee departures
- Deploy a dashboard (e.g., Power BI or Streamlit)

---

## 🤝 Contributions

Open to ideas, improvements, or visualizations! Feel free to fork, star ⭐, or create a pull request.

---

## 📜 License

This project is licensed under the MIT License.
