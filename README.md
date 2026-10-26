# 📊 Retail Sales Analytics

**An end-to-end data analytics project using Python, SQL, and Power BI to analyze retail sales, profitability, customer behavior, and regional performance.**

This project uses the Sample Superstore dataset to demonstrate a complete analytics workflow, from data understanding and cleaning to exploratory analysis, SQL-based business queries, and interactive Power BI dashboards.

## 📌 Project Overview

Retail businesses need to understand sales performance, identify profitable products, evaluate regional trends, and make informed decisions using data.

This project explores retail transaction data to answer business questions and present findings through Python notebooks, SQL scripts, and Power BI visualizations.

### 🎯 Business Objectives

- Analyze sales and profit performance.
- Evaluate product category and sub-category performance.
- Compare regional sales and profitability.
- Explore customer purchasing patterns.
- Investigate the relationship between discounts and profit.
- Develop interactive dashboards for business reporting.

## 🖥️ Dashboard Preview

### 1. Executive Dashboard

![Executive Dashboard](page1_dashboard.png)

### 2. Product and Customer Insights

![Product and Customer Insights](page2_dashboard.png)

### 3. Regional and Geographic Insights

![Regional and Geographic Insights](page3_dashboard.png)

*The screenshots above are stored in this repository. Open the Power BI report for interactive exploration.*

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas and NumPy | Data manipulation and cleaning |
| Matplotlib | Data visualization |
| SQL / MySQL | Business queries and analytical reporting |
| Power BI | Interactive dashboards and KPI reporting |
| Jupyter Notebook | Exploratory data analysis |
| Git and GitHub | Version control and project documentation |

## 📂 Repository Structure

```text
retail-sales-analytics/
│
├── 01_data_understanding.ipynb
├── 02_data_cleaning.ipynb
├── 03_eda.ipynb
│
├── 01_database_setup.sql
├── 02_basic_queries.sql
├── 03_aggregation.sql
├── 04_business_analysis.sql
├── 05_advanced_sql.sql
├── 06_interview_queries.sql
│
├── Retails-sales-analytics.pbix
├── Project_Banner.png
├── Workflow.png
│
├── page1_dashboard.png
├── page2_dashboard.png
├── page3_dashboard.png
│
├── sample_-_superstore.csv
├── sample_-_superstore.xlsx
├── requirements.txt
└── README.md
```

## 🔄 Project Workflow

1. **Data Understanding:** Inspect the dataset, columns, data types, and overall structure.
2. **Data Cleaning:** Examine missing values, duplicate records, inconsistent formats, and data quality.
3. **Exploratory Data Analysis:** Investigate sales, profit, product categories, customers, and regional patterns.
4. **SQL Analysis:** Write queries for filtering, aggregation, KPI analysis, and business questions.
5. **Dashboard Development:** Present important metrics and analytical views in Power BI.
6. **Business Interpretation:** Use verified analytical results to support business recommendations.

## 🐍 Python Analysis

The Python notebooks are organized into three stages:

- `01_data_understanding.ipynb` — Dataset inspection and initial understanding.
- `02_data_cleaning.ipynb` — Data quality checks and preprocessing.
- `03_eda.ipynb` — Exploratory data analysis and visualizations.

## 🗄️ SQL Analysis

The repository includes six SQL scripts:

- `01_database_setup.sql` — Database setup.
- `02_basic_queries.sql` — Basic queries and filtering.
- `03_aggregation.sql` — Aggregations and summary metrics.
- `04_business_analysis.sql` — Business-oriented analytical queries.
- `05_advanced_sql.sql` — Advanced SQL analysis.
- `06_interview_queries.sql` — Additional SQL practice and analytical questions.

The scripts can be reviewed and executed in the appropriate order after configuring the database and table structure.

## 📈 Power BI Dashboard

The Power BI report provides visual summaries of retail performance and supports further exploration of the dataset.

**Report file:** `Retails-sales-analytics.pbix`

To explore the report:

1. Install Power BI Desktop.
2. Download or clone this repository.
3. Open the `.pbix` file.
4. Configure the data source if prompted.
5. Refresh the data if required.

## ⚙️ Getting Started

### Prerequisites

- Python 3
- Git
- Jupyter Notebook
- MySQL, if running the SQL scripts
- Power BI Desktop, for the dashboard

### 1. Clone the repository

```bash
git clone https://github.com/VibhorJain1108/retail-sales-analytics.git
cd retail-sales-analytics
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

### 3. Install Python dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks in numerical order.

### 5. Run the SQL scripts

Configure your MySQL database and import the dataset according to the database setup script. Review each SQL file before executing it, and run the scripts in the appropriate order.

### 6. Explore the Power BI report

Open `Retails-sales-analytics.pbix` in Power BI Desktop. If the report requests a data source, update its path to match your local dataset.

## 🚀 Future Improvements

- Add verified business insights and quantified findings.
- Develop sales forecasting models.
- Perform customer segmentation and RFM analysis.
- Add automated data quality checks.
- Improve dashboard interactivity and KPI reporting.
- Document reproducible database and dashboard setup steps.

## 👨‍💻 Author

**Vibhor Jain**

Electronics & Communication Engineering  
Birla Institute of Technology, Mesra

- GitHub: [VibhorJain1108](https://github.com/VibhorJain1108)
- LinkedIn: [Vibhor Jain](https://www.linkedin.com/)

---

*Explore the notebooks, SQL scripts, and Power BI dashboards to learn more about the project.*
