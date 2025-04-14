# 🕵️‍♀️ Data Detectives: Automated Data-Driven Reporting Using Generative AI (SecureGPT)

## 🔍 Overview
This project, completed as part of the **DAEN 690** Capstone at George Mason University, presents a secure, scalable solution for **automated insight generation and reporting** using generative AI. We developed an end-to-end pipeline that utilizes **SecureGPT**, an enterprise-ready large language model, to automate the creation of customizable, industry-agnostic reports enriched with textual insights and visualizations.

The core goal is to democratize data analysis by providing **non-technical users** across industries like **healthcare, finance, retail, and pharmaceuticals** with fast, secure, and easy access to actionable insights — without compromising on data privacy or accuracy.

---

## 🧠 Problem Statement
Organizations struggle with:
- Manual, error-prone analysis pipelines
- Non-scalable analytics for large datasets
- Barriers for non-technical users to extract value from complex data

We aim to solve these issues with **SecureGPT-powered automation** that converts structured/unstructured data into clear summaries, visualizations, and recommendations — while preserving privacy and security.

---

## ⚙️ Tech Stack & Tools
- **Python** – Data processing, API integration, automation
- **SecureGPT API** – Generative AI for textual insights
- **Postman** – API testing and validation
- **Command Line Interface** – Execution & integration
- **Pandas, Matplotlib, Seaborn** – EDA and charting
- **GitHub** – Version control and collaboration

---

## 🧬 Datasets Used
| Domain        | Dataset                                                                                     | Source |
|---------------|----------------------------------------------------------------------------------------------|--------|
| Healthcare    | [Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)           | Kaggle |
| Pharmaceutical | [Consolidated Pharmaceutical List](https://opendata.nhsbsa.net/dataset/consolidated-pharmaceutical-list) | NHSBSA |
| Finance       | [Digital Wallet Transactions](https://www.kaggle.com/datasets/harunrai/digital-wallet-transactions) | Kaggle |
| Retail        | [Quarterly Retail Sales Tax Data](https://catalog.data.gov/dataset/quarterly-retail-sales-tax-data-by-county-and-city) | Data.gov |

---

## 🧪 Core Functionality
### 1. 🔄 Data Ingestion & Preprocessing
- Cleans, transforms, and conditions datasets from diverse domains.
- Handles missing values, formats fields, and removes duplicates.

### 2. 🤖 Generative Report Automation
- Transforms raw data into natural-language prompts.
- Uses **SecureGPT** to generate descriptive summaries and data insights.
- Stores and organizes responses for display and further use.

### 3. 📊 Visualization Layer
- Converts AI-generated insights into interactive visualizations.
- Supports bar charts, time-series plots, pie charts, and dashboards.

## 🧩 Architecture Diagram
Data Input (CSV/Database) → Data Conditioning → Prompt Generation ↓ ↓ SecureGPT API ← Query Engine ← Python Automation Scripts ↓ Output Storage → Textual Insights + Charts → Dashboard / UI Layer


---

## 🚀 Key Outcomes
- **Generated over 50+ automated summaries** across 4 domains.
- Reduced manual reporting time by **>60%**.
- Enabled non-technical users to extract insights with **zero code**.
- Ensured **data privacy and auditability** through SecureGPT features.

---

## 🎯 Future Enhancements
- Integration with real-time streaming data (Kafka, AWS Kinesis)
- Enhanced UI for drag-and-drop report generation
- Cross-language support for multilingual datasets
- Predictive modeling integration (forecasting trends)

---

## 👩‍💻 Team Members
- **Dhavani Avu**
- Neha Reddy Yenugu
- Hemanth Alam
- Shanmukh Rao

---

## 🤝 Partner
**Prof. Sam Ansari, CEO, Accure Inc.**  
Accure specializes in AI/ML platforms for secure, scalable enterprise intelligence.

## 📢 License
This project is for academic and non-commercial research purposes only. © 2024 George Mason University, DAEN Program.



