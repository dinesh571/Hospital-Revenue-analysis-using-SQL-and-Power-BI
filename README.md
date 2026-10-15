# Hospital Patient Data Analysis using SQL and Power BI

This project analyzes hospital operations and patient-care trends using SQL for data preparation and analysis and Power BI for interactive reporting. The supplied project materials also include a cleaned CSV dataset, SQL queries, a Python exploratory-analysis notebook, and a written report.

## Analysis areas

- Patient demographics and geographic distribution
- Medical-condition and admission trends
- Admission type, length of stay, and discharge outcomes
- Billing amounts and insurance-provider comparisons
- Hospital performance indicators and summary metrics

## Tools

- MySQL for SQL-based staging, transformation, and analysis
- Power BI for dashboards and visualizations
- Python, Pandas, and Jupyter Notebook for exploratory data analysis

## Project materials

The project archive supplied for this analysis contains:

- `hospital_project_queries.sql` — staging, table creation, and analysis queries
- `healthcare_dataset_cleaned_file.csv` — cleaned analysis dataset
- `hospital_patients_Analytics.ipynb` — exploratory-analysis notebook
- A Word report describing the analysis

This GitHub repository already has its own project files and archive; the newly supplied archive has not been added here.

## Getting started

1. Review the report and dataset fields before running the SQL or notebook.
2. Create the database expected by the SQL script in a local MySQL instance, then run the queries in order.
3. Open the notebook in Jupyter and install Pandas and the notebook's other required packages.
4. Open the available Power BI file in Power BI Desktop to explore the dashboard. Configure its data source to your local, approved dataset.

## Privacy and responsible use

The supplied CSV schema includes names, blood groups, medical conditions, admission and discharge dates, providers, and billing information. Do not publish real patient or protected health information. Use synthetic or properly de-identified data and confirm that you have permission to share all datasets and report materials before making them public. The analysis is for educational and operational exploration and is not medical advice.