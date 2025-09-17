# MarketMind: E-commerce Behavioral Analytics & Recommendation Engine


## Project Overview
An end-to-end data analytics project simulating a real-world pipeline. The goal is to derive business intelligence from e-commerce transaction data and build a simple product recommendation model.

**Key Features:**
- **Data Engineering:** Utilizes a cloud data lake (GCS) with Apache Iceberg for managing raw data.
- **Data Warehousing:** Processes and models data in Google BigQuery for analysis.
- **Business Intelligence:** A Power BI dashboard for visualizing sales trends and customer segments (RFM Analysis).
- **Machine Learning:** An association rule learning model to recommend "frequently bought together" products.
- **Deployment:** An interactive Streamlit app serving both the dashboard and the recommendation tool.

## Architecture
1.  **Data Layer:** Raw data is stored in cloud storage (GCS) and managed with Apache Iceberg.
2.  **Processing Layer:** Data is cleaned and transformed using PySpark/SQL before being loaded into BigQuery.
3.  **Analytics Layer:** Power BI connects to BigQuery for dashboards. A ML model is trained using Python.
4.  **Application Layer:** A Streamlit app integrates everything for end-user consumption.

## Technology Stack
- **Cloud & Storage:** Amazon Web Services (AWS)
- **Data Lake:** Amazon S3, Apache Iceberg Table Format
- **Data Catalog & Metastore:** AWS Glue Data Catalog
- **Query Engine:** Amazon Athena
- **BI Visualization:** Microsoft Power BI
- **Machine Learning:** Python (Pandas, Scikit-learn, MLxtend)
- **Deployment & App:** Streamlit

## Getting Started
Instructions for setting up the environment and running the code will be added here upon project completion.

Get the full silver_sales.csv on this drive: https://drive.google.com/drive/folders/1FDSk9avnmW0A3X9-zH-wMKqUr9xwsXQL?usp=sharing

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
