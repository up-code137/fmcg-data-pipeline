# 📊 FMCG Data Engineering Pipeline

## 🚀 Overview
This project demonstrates an end-to-end data engineering pipeline built using modern data stack tools. The objective was to consolidate and process data from a parent FMCG company and an acquired subsidiary into a unified data platform for analytics and reporting.

The pipeline is designed using Medallion Architecture and supports scalable data ingestion, transformation, and incremental processing.

---

## 🧩 Problem Statement
A parent company acquired a smaller company with unstructured and scattered data. The challenge was to:
- Integrate data from multiple sources
- Maintain data consistency
- Enable efficient analytics and reporting

---

## 🏗️ Architecture
```
AWS S3 → Databricks → Bronze → Silver → Gold → Dashboard
```

### 🔹 Architecture Explanation
- **AWS S3** → Stores raw data from child company  
- **Bronze Layer** → Raw ingested data with metadata  
- **Silver Layer** → Cleaned and transformed data  
- **Gold Layer** → Business-ready aggregated tables  
- **Dashboard** → Final insights for stakeholders  

---

## 🛠️ Tech Stack
- Databricks  
- PySpark  
- AWS S3  
- Delta Lake  
- SQL  

---

## ⚙️ Key Features

### ✅ Medallion Architecture
Implemented a layered architecture:
- Bronze → Raw ingestion  
- Silver → Data cleaning & merging  
- Gold → Analytical tables  

---

### ✅ Data Consolidation
- Merged parent and child company datasets  
- Integrated dimension and fact tables  

---

### ✅ Incremental Data Processing
- Implemented incremental loading using Delta Lake  
- Processed only new data instead of full reload  

---

### ✅ Pipeline Automation
- Created scheduled workflows using Databricks Jobs  
- Automated daily data ingestion and transformation  

---

### ✅ Metadata Tracking
- Captured file-level metadata (file name, size, timestamp)  
- Enabled better data lineage and debugging  

---

## 🔄 Data Flow

1. Raw data stored in AWS S3  
2. Ingested into Bronze layer using PySpark  
3. Data cleaned and merged in Silver layer  
4. Final business tables created in Gold layer  
5. Data used for dashboarding and analytics  

---

## 📈 Business Use Cases

- **Data Consolidation After Acquisition**  
  Unified reporting across multiple business entities  

- **Sales & Performance Analysis**  
  Enabled insights into product, pricing, and customer behavior  

- **Operational Efficiency**  
  Reduced redundancy and improved data reliability  

---

## 📷 Screenshots

### 🔹 Pipeline Workflow
<img width="1895" height="1021" alt="Pipeline-workflow" src="https://github.com/user-attachments/assets/0ab16cbf-74d6-47a6-aa0a-d952377efc76" />

### 🔹 Data Layers (Bronze / Silver / Gold)
<img width="1827" height="979" alt="Data-layer" src="https://github.com/user-attachments/assets/14565cb4-cc7f-43ea-9ca7-dd1da727e7cc" />

### 🔹 Dashboard
<img width="1505" height="609" alt="Dashboard1" src="https://github.com/user-attachments/assets/f49b5616-515e-4f15-b165-ea95e1248a89" />
<img width="1529" height="674" alt="Screenshot 2026-04-26 203824" src="https://github.com/user-attachments/assets/9943ed16-0d14-4be1-aed4-394cf8f9014c" />

---

## 🧠 Learnings

- Built scalable data pipelines using PySpark  
- Understood Medallion Architecture in real-world scenarios  
- Implemented incremental data loading using Delta Lake  
- Gained hands-on experience with Databricks and AWS S3  
- Learned how to design data models for analytics
- Developed understanding of distributed data processing using Apache Spark

---

## 📌 Conclusion
This project simulates a real-world data engineering use case involving data consolidation and pipeline automation. It demonstrates the ability to design scalable data systems and transform raw data into actionable insights.

---

## 👤 Author
Sameer Sinha
