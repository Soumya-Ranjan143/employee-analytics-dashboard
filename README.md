# 🏢 Employee Analytics Dashboard (Python + SQL)

An end-to-end data analytics and relational pipeline built to model, query, and extract actionable workforce insights from organizational data. This project integrates SQLite relational database design with Python data processing tools (`Pandas`, `NumPy`) to simulate real-world enterprise reporting workflows.

---

## 🎯 Executive Summary & Key Insights

* **Payroll Allocation**: Engineering and Data Science represent over **65% of overall corporate compensation**, driven by market demand in high-growth tech domains.
* **Geographic Distribution**: Key technology hubs (**Bangalore and Mumbai**) host the highest density of top-earning engineering talent.
* **Project Throughput**: Operational tracking indicates **80% of active projects** are currently on schedule or completed.
* **Compensation Gap**: Identifies a **₹97,000 baseline variance** between entry-level operations and senior engineering roles.

---

## 🛠️ Tech Stack & Architecture

* **Database Core**: SQLite3 (Schema Design, Foreign Key Constraints, Primary Keys)
* **Data Engineering & Querying**: Raw SQL (`JOINs`, `GROUP BY`, `HAVING`, `Subqueries`, Window Aggregations)
* **Data Processing & Analytics**: Python 3.x, Pandas, NumPy
* **Environment**: JupyterLab / Google Colab

---

## 📐 Relational Database Schema

The system uses 3 normalized relational tables:

1. **`departments`**: Contains organizational structure and annual department budgets.
2. **`employees`**: Stores demographic info, compensation, city locations, and join dates.
3. **`projects`**: Tracks individual project allocations and operational statuses.

---

## 📊 Analytical Scope (SQL Queries & Python Pipelines)

### SQL Capabilities Demonstrated:
* **Complex Multi-Table Joins**: Correlating employee metrics across departments and project deliverables.
* **Conditional Aggregations**: Grouping payroll metrics filtered via `HAVING` clauses.
* **Subqueries & Window Operations**: Identifying top-earning percentiles and salary rankings.
* **Outer Joins**: Spotting unallocated department budgets and unassigned staff.

### Python Data Pipeline Capabilities:
* **NumPy Vectorization**: Rapid statistical analysis (mean, median, standard deviation) and annual compensation projections.
* **Pandas Merges**: Cross-verifying relational database queries directly against Pandas DataFrame operations.
* **Custom Functions & Conditionals**: Vectorized salary grading (`Grade A/B/C`) and dynamic city-level filtering utilities.

---

## 🚀 How to Run Locally

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/Soumya-Ranjan143/employee-analytics-dashboard.git](https://github.com/Soumya-Ranjan143/employee-analytics-dashboard.git)
   cd employee-analytics-dashboard
