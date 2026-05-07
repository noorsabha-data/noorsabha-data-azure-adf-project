# 🚀 Azure Data Factory End-to-End Data Engineering Project

## 📌 Project Overview
This project demonstrates an end-to-end **data engineering pipeline using Azure Data Factory (ADF)**. It includes data ingestion, transformation, and loading into Azure services such as SQL Database and Data Lake Storage.

The goal of this project is to showcase real-world ETL workflows, orchestration, and cloud data engineering skills.

---

## 🏗️ Architecture

- Architecture Diagram

---

## 🔧 Tech Stack
- Azure Data Factory (ADF)
- Azure SQL Database
- Azure Data Lake Storage Gen2
- Linked Services
- Dataset (Blob + SQL)
- Data Flows
- GitHub Integration

---

## ⚙️ Project Components

### 1. Linked Services
- Azure SQL Database connection
- Azure Data Lake Storage connection

### 2. Datasets
- Source datasets from SQL / On-prem / Blob storage
- Sink datasets into Data Lake / SQL

### 3. Pipelines
- End-to-end ETL pipelines
- Copy activity (Source → Destination)
- Data flow transformations

### 4. Data Flows
- Data cleaning and transformation logic
- Filtering, joins, and aggregations

---

## 🔄 Workflow
1. Extract data from SQL / source system  
2. Transform data using Mapping Data Flows  
3. Load data into Azure Data Lake / SQL Database  
4. Orchestrate using ADF Pipelines  

---

## 📊 Features
- Scalable cloud-based ETL pipeline
- Modular pipeline design
- GitHub version control integration
- Reusable linked services and datasets

---

## 🚀 How to Run
1. Clone the repository
2. Open Azure Data Factory Studio
3. Import linked services, datasets, pipelines
4. Trigger pipeline manually or via schedule

---

## 📌 Future Improvements
- Add Azure DevOps CI/CD pipeline
- Add real-time streaming using Event Hub
- Implement incremental data loading (CDC)

---

## 👨‍💻 Author
**Noorsabha Qureshi**