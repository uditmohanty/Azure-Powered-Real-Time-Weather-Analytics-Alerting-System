
# 🌤️ Azure-Powered Real-Time Weather Analytics & Alerting System for Los Angeles

## 📌 Project Overview
This project implements a **real-time weather monitoring and alerting system** using **Azure cloud services**. It collects live weather data, processes it efficiently, and visualizes insights while also triggering **real-time alerts** for extreme weather conditions.

## 🔧 Tech Stack
- **Cloud & Data Engineering:** Azure Databricks, Azure Functions, Microsoft Fabric, Event Hub
- **Data Storage & Querying:** Kusto DB (Azure Data Explorer)
- **Data Visualization:** Power BI
- **Real-Time Alerts:** Data Activator
- **Programming Languages:** Python, SQL
- **Orchestration & Optimization:** Incremental Data Loading, Real-Time Data Streaming

## 🚀 Key Features
- 🔄 **Real-time weather data ingestion** using **Azure Functions** and **Databricks**
- 📡 **Event-driven data streaming** with **Azure Event Hub**
- 📊 **Interactive Power BI dashboard** for real-time weather trends
- ⚡ **Optimized querying** with **Kusto DB** for high-performance analytics
- 🚨 **Automated real-time alerts** for extreme weather conditions via **Data Activator**

## 📂 Project Structure

weather-streaming-project/
│── src/
│ ├── data_ingestion.py # Fetches weather data from API using Azure Functions
│ ├── event_hub_stream.py # Streams data to Azure Event Hub
│ ├── data_processing.py # Cleans & processes data using Azure Databricks
│ ├── alert_system.py # Triggers real-time alerts using Data Activator
│
├── dashboard/
│ ├── power_bi_dashboard.pbix # Power BI interactive dashboard file
│
├── docs/
│ ├── project_report.pdf # Documentation & reports
│
├── .gitignore # Specifies files to ignore in Git
├── README.md # Project overview & setup instructions
├── requirements.txt # Dependencies & libraries
└── LICENSE # Open-source license information


## ⚡ Setup Instructions

### 1️⃣ Install Dependencies
Ensure **Python 3.11.1+** is installed and run:
```sh
pip install -r requirements.txt

## 2️⃣ Configure Azure Services

Create an Azure Event Hub for real-time streaming /
Deploy Azure Functions to fetch data from a weather API /
Set up a Databricks workspace for data processing /
Use Kusto DB for high-performance data querying /
Connect Power BI to Kusto DB for real-time visualization /
Configure Data Activator to trigger automated alerts /


