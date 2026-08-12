# 🚢 Titanic Survival Insights Dashboard

An interactive Power BI dashboard designed to analyze passenger demographics, ticket economics, and survival factors from the classic Titanic dataset. 

![Titanic Survival Insights Dashboard](<img width="1840" height="1050" alt="Screenshot 2026-06-30 105927" src="https://github.com/user-attachments/assets/dc4762bb-3f23-4954-a37e-766c380a4fde" />)

---

## 📌 Project Overview

This dashboard visualizes key demographics and factors influencing passenger survival rates aboard the Titanic. By leveraging visual analytics, it reveals clear patterns between socioeconomic status (fare/class), family dynamics, boarding locations, and survival outcomes.

---

## 📊 Key Insights & Metrics

### High-Level KPI Summary
* **Total Passengers:** 1,309
* **Average Fare:** $33.30
* **Total Survivors:** 501

### Main Findings
1. **Gender Impact:** Females had a significantly higher survival rate compared to males, aligned with the "women and children first" protocol.
2. **Fare & Class Correlation:** Passengers who paid higher fares (High Fare Category) experienced a noticeably higher rate of survival than those in Low or Medium categories.
3. **Family Dynamics:** 
   * **60.35%** ($790$) of passengers traveled with family.
   * **39.65%** ($519$) of passengers traveled alone.
4. **Port Dynamics:** The majority of passengers boarded from **Port S (Southampton)**, which also accounted for the highest proportion of 3rd class passengers.

---

## 📈 Visualizations Included

* **Key Indicators:** Dynamic Cards showing Total Passengers, Average Fare, and Total Survived.
* **Survival Status by Fare Category:** Clustered column chart detailing outcomes across Low, Medium, and High fare brackets.
* **Survival Status by Gender:** Horizontal stacked bar chart displaying survival distributions between male and female passengers.
* **Survival by Family Status:** Pie chart breaking down passenger proportions based on traveling alone vs. with family.
* **Distribution by Boarding Port:** Clustered column chart showing passenger class distribution (`pclass` 1, 2, 3) across embarking ports (**S**outhampton, **C**herbourg, **Q**ueenstown).

---

## 🛠️ Tools & Technologies

* **Business Intelligence:** Power BI Desktop
* **Data Modeling:** DAX (Data Analysis Expressions) & TMDL
* **Data Source:** Titanic Passenger List (Full Dataset of 1,309 records)

---

## 🚀 How to View & Use

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/titanic-survival-dashboard.git](https://github.com/your-username/titanic-survival-dashboard.git)
