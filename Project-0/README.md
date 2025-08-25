# Project-0: Data Cleaning, Exploratory Data Analysis (EDA) & Financial Dashboard

This project represents the **foundational step** of my data science journey. Before diving into advanced machine learning or predictive modeling, the most crucial stage is always **data preparation and exploration**.

With **Project-0**, I focused on three interconnected phases:

* 🧹 **Data Cleaning & Preparation**
* 🔎 **Exploratory Data Analysis (EDA)**
* 📊 **Financial Dashboard Creation**

The goal is to take raw, imperfect data and transform it into structured, meaningful insights — first through Python-based EDA, and then by designing an **interactive Power BI dashboard** that communicates findings in a clear and compelling way.

---

## 📑 Table of Contents

1. [Overview](#overview)
2. [Why This Project?](#why-this-project)
3. [Features](#features)
4. [Dataset](#dataset)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Project Structure](#project-structure)
8. [EDA Summary](#eda-summary)
9. [Dashboard Insights](#dashboard-insights)
10. [Learning Outcomes](#learning-outcomes)
11. [License](#license)

---

## 🔎 Overview

The lifecycle of this project can be broken down into three main stages:

1. **Data Cleaning & Preparation** – Identifying missing values, handling duplicates, resolving inconsistencies, and ensuring the dataset is analysis-ready.
2. **Exploratory Data Analysis (EDA)** – Using statistical summaries and visualizations to uncover trends, correlations, and anomalies within the data.
3. **Dashboard Creation** – Designing an interactive Power BI dashboard that brings the data story to life for decision-makers.

The entire workflow is reproducible, portable, and built with **good practices for reusability** — thanks to Jupyter Notebooks for Python workflows and DevContainer setup for environment consistency.

---

## ❓ Why This Project?

In the real world, **80% of a data scientist’s time** is often spent cleaning and preparing data. Raw datasets are rarely perfect. They are often:

* ❌ Incomplete (missing rows/columns)
* ❌ Inconsistent (mixed formats, irregular entries)
* ❌ Redundant (duplicate records)
* ❌ Noisy (errors, typos, or irrelevant data)

This project was designed to highlight:

* ✅ **Data preparation skills** – turning “messy” datasets into a usable foundation.
* ✅ **Analytical thinking** – asking the right questions and exploring the data meaningfully.
* ✅ **Visualization storytelling** – translating findings into insights with Python plots and interactive Power BI reports.

By working through this project, I built a **strong foundation in data exploration**, which will support more advanced projects in predictive analytics and machine learning.

---

## ✨ Features

* 🧹 Automated **data-cleaning pipeline** to handle missing values, duplicates, and inconsistencies.
* 📈 Comprehensive **EDA** using **Matplotlib, Seaborn, and Plotly**.
* 🌍 **Interactive Power BI Dashboard** with dynamic filters, drill-downs, and geographical insights.
* 🔄 Fully **reproducible workflow** using DevContainers for consistent setup.
* 🎓 Portfolio-ready project that demonstrates the **end-to-end data analysis process**.

---

## 📂 Dataset

**File:** `Financial Sample.xlsx`

This dataset contains simulated financial transactions across multiple segments, products, and geographies.

**Key Fields Explored:**

* `Segment` – Type of customer (Government, Midmarket, Enterprise, etc.)
* `Country` – Country of transaction
* `Product` – Product sold
* `Sales` – Net sales after discount
* `Gross Sales` – Total sales before discount
* `Profit` – Net profit earned
* `Discount Band` – Level of discount applied
* `Date/Year` – Transaction period

This dataset serves as an excellent foundation for **business-oriented data cleaning, visualization, and dashboarding practice**.

---

## ⚙️ Installation

### Option 1: DevContainer (recommended)

1. Clone repository:

   ```bash
   git clone https://github.com/ParasMittu/Data-Exploration-Portfolio.git
   cd Data-Exploration-Portfolio
   ```
2. Open in **VS Code** → Reopen in Container.
3. Dependencies install automatically.

### Option 2: Local Setup

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## ▶️ Usage

* Open **`Data Cleaning And Visualizing.ipynb`** → Walk through step-by-step data cleaning and visualization.
* Open **`EDA.ipynb`** → Perform deeper exploratory analysis with correlations and distributions.
* Open **`Financial Analysis.pbix`** → Interact with the financial dashboard in Power BI.

---

## 📁 Project Structure

```
Project-0/
│── Data Cleaning And Visualizing.ipynb   # Data cleaning & visualization workflow
│── EDA.ipynb                             # Detailed exploratory data analysis
│── Financial Analysis.pbix               # Interactive Power BI dashboard
│── Financial Sample.xlsx                 # Dataset
│── README.md                             # Documentation
│── LICENSE                               # MIT License
```

---

## 📊 EDA Summary

Some key insights from the exploratory analysis:

* ✅ Missing values were handled, and categorical formats were standardized.
* ✅ Duplicate records were removed to ensure data integrity.
* ✅ Distribution analysis revealed skewed sales data across different segments.
* ✅ Correlation analysis showed strong links between **Gross Sales, Discounts, and Profit**.
* ✅ Outliers were identified, especially in **high-discount and low-profit transactions**.

The EDA provided **valuable business insights** while also preparing the dataset for advanced modeling in future projects.

---

## 📈 Dashboard Insights (Power BI)

The **Financial Analysis Dashboard** provides stakeholders with a comprehensive yet interactive view of the dataset:

* 📌 At-a-glance **KPIs**: Profit, Sales, Units Sold, Discounts
* 📌 **Profitability by Country & Segment**
* 📌 **Sales trends over time**, segmented by product and customer group
* 📌 **Geographical breakdown** with map visuals for easy comparison
* 📌 Fully interactive filtering by **Year, Segment, and Product**

This dashboard transforms static analysis into a **decision-making tool** for managers and executives.

---

## 🎯 Learning Outcomes

By completing this project, I strengthened my skills in:

* 🧹 **Data Cleaning** – handling missing, duplicate, and inconsistent data.
* 📈 **EDA Techniques** – applying univariate, bivariate, and multivariate analysis.
* 📊 **Visualization** – creating impactful plots and dashboards.
* 💻 **Tool Mastery** – working with Jupyter, Python libraries, DevContainers, and Power BI.
* 🎨 **Storytelling with Data** – presenting findings in a way that is both analytical and business-friendly.

This project represents a **strong first step** in building my data portfolio, showing not only technical execution but also the ability to present insights professionally.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file.

---
