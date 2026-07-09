# 📊 ConnectaTel Customer Usage Analysis

## 📌 Project Overview

This project analyzes customer behavior for **ConnectaTel**, a telecommunications company operating in Latin America.

The objective is to understand how customers use mobile services by analyzing calls, messages, demographics, and subscription plans. The analysis identifies usage patterns, detects outliers, segments customers, and provides business recommendations to support decision-making.

---

## 🎯 Business Questions

This analysis answers the following questions:

- Which customer segments have the highest and lowest service usage?
- Are there unusual usage patterns or outliers?
- How does usage vary according to age and subscribed plan?
- What opportunities exist to improve current mobile plans?

---

## 📂 Datasets

The project uses three datasets:

- **plans.csv** — Mobile plan information (price, included minutes, GB, extra charges).
- **users_latam.csv** — Customer demographic information and subscription details.
- **usage.csv** — Historical records of calls and text messages.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Analysis Workflow

The project follows these steps:

1. Data loading and exploration
2. Data quality assessment
3. Data cleaning
4. Descriptive statistics
5. Distribution visualization
6. Outlier detection (IQR method)
7. Customer segmentation
8. Executive business insights

---

## 🔍 Key Findings

- Most customers belong to the **Medium Usage** segment.
- Adults represent the largest customer group.
- High-usage customers were identified but retained because they represent valid business behavior rather than data errors.
- Missing values and sentinel values were cleaned without removing meaningful customer information.

---

## 💡 Business Recommendations

- Create personalized plans for high-usage customers.
- Design promotions to increase engagement among low-usage users.
- Improve data validation processes to prevent invalid ages and future registration dates.
- Continue monitoring high-consumption customers to identify commercial opportunities.

---

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/claudiamena90-rgb/telecom-analysis.git
```

2. Navigate to the project directory:

```bash
cd telecom-analysis
```

3. Ensure the following datasets are available in the `datasets/` folder:

- `plans.csv`
- `users_latam.csv`
- `usage.csv`

4. Open the notebook using **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.

5. Run all notebook cells from top to bottom to reproduce the complete analysis.

---

## 👤 Author

**Claudia Mena**

Data Analytics Student | TripleTen
