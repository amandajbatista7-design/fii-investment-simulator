# 📘 FII Portfolio & Scenario Analysis Dashboard

A dynamic Excel-based investment simulator designed to help users analyze long‑term returns when investing in Brazilian Real Estate Investment Funds (FIIs).  
This project combines financial modeling, scenario analysis, and interactive dashboards to support better investment decision‑making.

---

## 📌 Overview

This tool allows users to simulate monthly investments in FIIs, visualize long‑term portfolio growth, and compare outcomes under different market scenarios.  
It includes:

- Interactive user inputs  
- Automatic portfolio allocation based on risk profile  
- Scenario modeling (Best, Base, Worst case)  
- 60‑month projection chart  
- Dividend estimation  
- Clean, dashboard‑style layout  

This project was developed as part of an Excel laboratory challenge focused on applying financial concepts to real‑world investment simulations.

---

## 🏢 What Are FIIs?

**FIIs (Fundos de Investimento Imobiliário)** are Brazilian Real Estate Investment Funds.  
They pool investor capital to acquire:

- Commercial properties  
- Logistics warehouses  
- Shopping centers  
- Real‑estate‑backed securities  
- Development projects  

Investors receive **monthly dividends** and benefit from **long‑term appreciation** of the underlying assets.  
FIIs are popular in Brazil due to their accessibility, liquidity, and income‑generating nature.

This simulator models how an investor’s wealth and dividends evolve over time when investing consistently in FIIs.

---

# 🧩 How the Workbook Works

The workbook is structured into **three interactive sheets**, each with a specific purpose.

---

## 1. 🖥 Main Dashboard (User Interaction Area)

This is the central interface where the user inputs data and views results.

### 🔧 Settings
The user can input:
- **Salary**
- **Portfolio yield**

The workbook automatically calculates a **suggested investment amount**, equal to **30% of the salary**.

---

### 💰 Monthly Investment
The user inputs:
- **How much they want to invest monthly**
- **For how many years**
- **Expected monthly return rate**

The dashboard then calculates:
- **Accumulated equity**
- **Monthly dividends**
- **Long‑term projections** (2, 5, 10, 20, 30 years)

---

### 📊 Portfolio Allocation (Based on Profile Selection)

The user selects a **risk profile** from a dropdown:
- Conservative  
- Moderate  
- Assertive (Aggressive)

Based on the selected profile:
- The table updates the **suggested percentage allocation** for each FII type  
- The workbook calculates **how much of the monthly investment** goes to each category:
  - Paper  
  - Brick  
  - Hybrid  
  - Funds of Funds  
  - Development  
  - Hospitality  

The **pie chart updates automatically** to reflect the new allocation.

---

### 📈 Scenario Analysis (Integrated Into Dashboard)

The user selects a scenario:
- **Best Case**
- **Base Case**
- **Worst Case**

The dashboard then displays:
- Monthly return rate for the scenario  
- Accumulated value after 5 years  
- Monthly dividend  
- A dynamic **60‑month growth chart** that updates automatically  

---

## 2. 📄 Profile Sheet

This sheet contains the allocation rules for each risk profile.

Each row defines:
- A **profile** (Conservative, Moderate, Assertive)
- A **FII type** (Paper, Brick, Hybrid, FOFs, Development, Hospitality)
- The **percentage allocation**

Example:

| Profile | FII Type | % Allocation |
|--------|----------|--------------|
| Conservative | Paper | 30% |
| Moderate | Brick | 35% |
| Assertive | Development | 20% |

The main dashboard uses this table to calculate how the user’s monthly investment is distributed.

---

## 3. 📊 Scenario Analysis Sheet

This sheet contains:
- **Best, Base, and Worst case scenarios**
- Monthly return rates for each scenario
- Accumulated value after 5 years
- Monthly dividends
- A **60‑month projection table** used to build the dynamic chart

The main dashboard pulls these values based on the user’s scenario selection.

---

# 🚀 Features

- ✔ Interactive user inputs  
- ✔ Automatic investment suggestion (30% of salary)  
- ✔ Portfolio allocation based on risk profile  
- ✔ Scenario modeling (Best, Base, Worst)  
- ✔ Dynamic 60‑month projection chart  
- ✔ Dividend estimation  
- ✔ Clean dashboard layout  
- ✔ Lookup‑driven automation (XLOOKUP, data validation)  

---

# 📂 Repository Structure

/fii-investment-simulator
│
├── README.md
├── Investment_ScenarioAnalysis.xlsx
│
└── /images
      ├── main_dashboard.png
      ├── scenario_analysis.png
      ├── profile_table.png


---

# 🧭 How to Use

1. Open the Excel file.  
2. Enter your salary and portfolio yield.  
3. Review the suggested investment amount (30% of salary).  
4. Enter your monthly investment, time horizon, and expected return rate.  
5. Choose a **risk profile** to update portfolio allocation.  
6. Choose a **scenario** to update return rate, accumulated value, and the projection chart.  
7. Explore how different assumptions impact long‑term returns.

---

# 🛠 Excel Concepts Used

- Data validation (dropdowns)  
- Lookup functions (XLOOKUP)  
- Financial functions (FV)  
- Conditional formatting  
- Dynamic charts  
- Scenario modeling  
- Dashboard design principles  

---

# 👩‍💻 Author

**Amanda Batista**

Junior Data Analyst focused on Python, SQL, Excel, and Power BI.

LinkedIn: https://www.linkedin.com/in/amandabat

GitHub: https://github.com/amandajbatista7-design
