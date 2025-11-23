**Overview**

This project demonstrates a complete end-to-end data analytics workflow — from loading and exploring raw data in Python to building a fully interactive Power BI dashboard and a final project report.
It highlights practical skills in data cleaning, SQL querying, visualization, and presenting insights in a structured and professional manner.

The goal of this project is to analyze real-world data, uncover meaningful patterns and insights, and present them through a clear, actionable dashboard and report.

**📂 Dataset**

The dataset used in this project contains information on customer data. 

Format: .csv

The dataset was cleaned and transformed before analysis.


**🛠️ Tools & Technologies**

Languages

Python (Pandas, NumPy, Matplotlib/Seaborn)

SQL (PostgreSQL)

Visualization & Reporting

Power BI

AI-based Presentation Tool (for generating final PPT)

Other Tools

Jupyter Notebook / VS Code

pgAdmin / DBeaver for SQL execution

GitHub for version control

📈 Project Steps
1. Data Loading (Python)

Imported dataset using Pandas

Performed initial inspection (head, shape, summary statistics)

Identified missing values, datatypes, and potential data issues

2. Exploratory Data Analysis (EDA)

Univariate, bivariate, and multivariate analysis

Distribution plots, correlations, trend analysis

Identified patterns, outliers, and feature relationships

3. Data Cleaning & Transformation

Handled missing data

Removed duplicates and outliers

Standardized formats (dates, numbers, categories)

Created new derived features where required

4. SQL Analysis (PostgreSQL)

Loaded cleaned dataset into PostgreSQL

Executed queries for:

Aggregations

Filters and joins

Grouped analysis

Business-level metrics

Validated Python insights with SQL results

5. Power BI Dashboard Development

Imported processed dataset

Designed visualizations for key metrics

Created slicers, filters, and dynamic visuals

Built an interactive dashboard for business insights

Followed best practices for layout, color, and clarity

6. Report & Presentation

Summarized findings into an analytical report

Created a professional PPT using an AI tool

Included key charts, insights, and recommendations

📊 Dashboard Overview

The Power BI dashboard includes:

KPI cards

Trend and time-series analysis

Category-wise comparisons

Geographic/segment breakdowns (if applicable)

User-friendly filters for interactive exploration

You can view the dashboard file (.pbix) and screenshots in the /dashboard directory.

📁 Project Structure
├── data/
│   ├── raw_data.csv
│   ├── cleaned_data.csv
│
├── notebooks/
│   ├── eda.ipynb
│   ├── cleaning.ipynb
│
├── sql/
│   ├── analysis_queries.sql
│
├── powerbi/
│   ├── dashboard.pbix
│
├── reports/
│   ├── final_report.pdf
│   ├── presentation.pptx
│
└── README.md

🚀 How to Run the Project
1. Clone the Repository
git clone https://github.com/yourusername/your-repo.git
cd your-repo

2. Install Python Dependencies
pip install -r requirements.txt

3. Run Jupyter Notebook
jupyter notebook


Open eda.ipynb and cleaning.ipynb to explore and clean the data.

4. Execute SQL Queries

Import cleaned_data.csv into your PostgreSQL database

Run queries from analysis_queries.sql using pgAdmin/DBeaver

5. Open Dashboard

Launch Power BI Desktop

Open dashboard.pbix
