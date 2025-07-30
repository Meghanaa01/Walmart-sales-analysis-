
# Walmart Sales Analysis Project

*End-to-End SQL + Python Project*

---

## Project Overview

This project delivers a comprehensive data analysis solution designed to extract critical business insights from Walmart sales data. Leveraging **Python** for data processing, **SQL** for advanced querying, and structured problem-solving methods, this project is ideal for aspiring data analysts aiming to strengthen skills in data manipulation, complex SQL querying, and end-to-end data pipeline development.

---

## Project Workflow

### Environment Setup

* **Tools:** Visual Studio Code (VS Code), Python, SQL (MySQL & PostgreSQL)
* **Objective:** Organize a clean and efficient workspace and project folder structure to facilitate smooth development and data management.

### Kaggle API Configuration

* **Process:**

  * Download Kaggle API token (`kaggle.json`) from your Kaggle profile settings.
  * Place it in the `.kaggle` folder on your local machine.
  * Use the Kaggle API to download datasets directly into your project environment.

### Dataset Acquisition

* **Source:** Walmart Sales Dataset on Kaggle
* **Dataset Link:** [Walmart Sales Dataset](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)
* **Storage:** Store datasets within the `data/` directory for easy access.

### Installation & Data Loading

* **Required Libraries:**

  ```bash
  pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
  ```
* **Data Loading:** Load datasets into Pandas DataFrames for initial exploration and cleaning.

### Data Exploration

* Conduct preliminary analysis to understand data distribution, inspect column names, data types, and identify anomalies using `.info()`, `.describe()`, `.head()`.

### Data Cleaning

* Remove duplicates and handle missing data appropriately.
* Convert data types where necessary (e.g., dates to datetime objects, prices to floats).
* Standardize currency formats and validate data consistency.

### Feature Engineering

* Create new calculated columns such as **Total Amount** by multiplying `unit_price` and `quantity` to support revenue and sales analysis.

### Database Integration

* Establish connections with MySQL and PostgreSQL databases using SQLAlchemy.
* Automate table creation and load cleaned data into both databases.
* Verify data accuracy through sample queries.

### SQL Analysis & Business Insights

* Execute complex SQL queries to answer critical business questions including:

  * Revenue trends by branch and category
  * Best-selling product categories
  * Sales performance by time, city, and payment method
  * Peak sales periods and customer purchase behavior
  * Profit margin analysis by branch and category

### Documentation & Project Publishing

* Maintain comprehensive documentation of processes and insights.
* Publish the project to GitHub with organized folder structure, including SQL scripts, notebooks, and README.

---

## Project Requirements

* Python 3.8 or higher
* SQL databases: MySQL and/or PostgreSQL
* Python libraries: `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`, `psycopg2`
* Kaggle API key for dataset download

---

## Getting Started

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Set up Kaggle API, download data, and follow project steps for loading and analysis.

---

## Project Structure

```plaintext
|-- data/                     # Raw and processed datasets
|-- sql_queries/              # SQL query scripts for analysis
|-- notebooks/                # Jupyter notebooks for Python analysis
|-- README.md                 # Project documentation
|-- requirements.txt          # Python package dependencies
|-- main.py                   # Main script for data loading, cleaning, and processing
```

---

## Key Results & Insights

* Identified top-performing sales branches and categories.
* Analyzed profitability across locations and product segments.
* Uncovered customer purchase trends related to payment methods and shopping times.

---

## Future Work

* Integration with visualization tools such as Power BI or Tableau for interactive dashboards.
* Incorporate additional data sources to deepen analysis.
* Automate the data pipeline for continuous ingestion and real-time analytics.

---

## License

This project is licensed under the **MIT License**.

---

## Acknowledgments

* Dataset courtesy of [Kaggle’s Walmart Sales Dataset](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)
* Inspired by Walmart’s retail analytics and supply chain case studies.

---

