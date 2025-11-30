# aws-space-weather-dashboard
Cloud-native space weather monitoring system using AWS serverless architecture (WIP).
# 🌌 AWS Space Weather Monitoring Dashboard (WIP)

This project matches the Space Weather Dashboard described in my resume.

## 🚀 Overview
A cloud-native dashboard that collects and processes real-time space weather data (solar wind, geomagnetic storms, KP-index) from NASA & NOAA APIs using AWS serverless components.

## 🧩 Architecture (Planned)
- API Gateway
- AWS Lambda (scheduled ingestion)
- DynamoDB (storage with TTL)
- SNS alerts for anomalies
- CloudWatch dashboards & logs
- IAM least-privilege roles
- S3 storage (coming soon)
- Terraform IaC (coming soon)

## 📡 Data Flow
1. Lambda fetches space weather data  
2. Cleans & validates JSON fields  
3. Stores items in DynamoDB  
4. CloudWatch visualizes metrics  
5. SNS alerts on thresholds  

## 🧠 Skills Demonstrated
- Python (APIs, JSON)
- Serverless architecture
- DynamoDB modeling
- Event-driven design
- Monitoring & alerting
- IAM security

## 📅 Status
🟡 Work in progress (updated weekly)
