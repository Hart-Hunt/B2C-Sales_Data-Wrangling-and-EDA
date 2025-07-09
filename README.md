# B2C Retail Sales (Argentina) – Data Wrangling and Exploratory Data Analysis

## 📌 Objective

This project showcases the first step in working with a real-world sales dataset from the B2C retail channel in Argentina.  
The objective is to clean, transform, and explore sales data using Python, with the goal of building a solid analytical base for further modeling.

---

## 🗂️ Dataset Overview

The dataset is based on weekly point-of-sale (POS) sales records from a panel of Argentine self-service stores, spanning March to June 2024.  
It includes information on stores, products, and transactional sales.

- `AR_PDV.csv`: Metadata of points of sale (e.g., store type, region, chain)
- `AR_PRD.csv`: Metadata of products (e.g., category, brand, presentation)
- `AR_VTA.csv`: Weekly sales records with volume and revenue metrics, linked by store and product

---

## 🔧 Key Steps

- Reading and combining multiple CSV files from ZIP archives
- Data type validation and formatting (dates, floats, categoricals)
- Handling of missing values and outliers
- Enrichment of sales data with product and POS metadata
- Exploratory visualizations to detect patterns and anomalies

---

## 📊 Exploratory Data Analysis

The EDA focuses on:

- Weekly evolution of sales volume and revenue
- Product category performance
- POS-level contribution to total sales
- Detection of promotional spikes or outliers
- Distribution of product sales across store types and regions

All charts and insights are generated using Python (Pandas, Matplotlib, Seaborn) and are documented with business context and interpretations.

---

## 📁 Output

The project produces:
- Cleaned and merged datasets ready for modeling
- EDA visualizations and descriptive statistics
- Scripts for reproducible preparation workflows

These outputs serve as the foundation for the following projects in the portfolio:
- Forecasting demand using time series models
- Price elasticity modeling
- Predictive modeling using machine learning

---

## 🧭 Next Steps

Explore the companion repositories:
- `Forecasting_B2C_Sales`
- `Price_Elasticity_Modeling`
- `ML_Classification_Retail`

All projects reuse this cleaned dataset to focus on a specific analytics objective.

---

## 💡 Technologies Used

- Python (Pandas, Numpy, Matplotlib, Seaborn, Zipfile)
- Jupyter Notebooks
- Structured project workflow and documentation

---

## 🔐 Disclaimer

This project is based on **real-world data** that has been **fully anonymized** for ethical and legal compliance.  
Identifiers such as store codes, product IDs, and names have been replaced with random codes.  
No sensitive or proprietary information is disclosed.

---

## 📬 Contact

If you'd like to discuss this project, collaborate, or explore tailored data solutions:

🔗 [Ezequiel Sueldo on LinkedIn](https://www.linkedin.com/in/ezequielalbertosueldo/)
<!-- 🌐 [ESU Analytics Website](https://esuanalytics.com)  -->
