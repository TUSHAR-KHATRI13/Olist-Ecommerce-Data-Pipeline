# Olist eCommerce Data Pipeline  

A **real-time ETL pipeline** for processing Olist eCommerce data, built using the **Medallion architecture** to ensure structured data ingestion, transformation, and efficient querying.  1

![image](https://github.com/user-attachments/assets/ddf699e3-d41f-4dc8-bac6-b3687eba9645)


## 🚀 Features  
- **Real-time ETL processing of eCommerce data**  
- **Medallion Architecture (Bronze → Silver → Gold) for data refinement**  
- **SQL-based ingestion for structured data processing**  
- **HTTPS-secured API interactions**  
- **Optimized query layer for analytics**  

## 🏗 Architecture Overview  
This pipeline follows the **Medallion architecture** to manage raw, cleaned, and enriched data:  
- **Bronze Layer**: Raw eCommerce transaction data ingestion.  
- **Silver Layer**: Data cleaning, deduplication, and enrichment.  
- **Gold Layer**: Aggregated data for business intelligence and reporting.  

## 🛠️ Tech Stack  
- **Data Processing**: Python, Pandas  
- **Database**: MySQL  
- **ETL Framework**: Apache Airflow  
- **Cloud Storage**: Microsoft Azure  
- **API Security**: HTTPS  

## 📂 Data Flow  
1. **Ingestion**: Raw Olist transaction data is ingested from source APIs.  
2. **Processing**: ETL jobs clean and transform data into structured SQL tables.  
3. **Storage**: Data is stored in PostgreSQL following the Medallion architecture.  
4. **Query Optimization**: Gold-layer tables provide efficient data retrieval for analytics.  

This pipeline enables seamless **real-time data ingestion, transformation, and storage**, supporting **scalable and secure data processing** for eCommerce analytics.  
