# 📊 Real-Time Stock Data Streaming with Kafka & AWS

This is a self-study project that simulates a real-time stock market data pipeline using open-source tools and AWS cloud services. The goal is to understand and apply real-time data engineering concepts as part of my journey to learn **Data Science**.

---

## 🧠 Project Overview

- Simulate real-time stock data using a CSV file.
- Stream data to **Kafka** (running on **AWS EC2**) via a Python **producer**.
- Receive and process data using a Python **consumer**, then store it in **Amazon S3**.
- Use **AWS Glue Crawler** to catalog the data stored in S3.
- Query the data using **Amazon Athena** with standard SQL.

---

## 🧱 Architecture

The architecture includes:

- Kafka + ZooKeeper on AWS EC2 for real-time messaging
- Python (Producer & Consumer)
- Amazon S3 for data lake storage
- AWS Glue for schema discovery
- Amazon Athena for serverless querying

📷 *Refer to the architecture diagram in the repo for a full visual overview.*

---

## 🛠️ Tech Stack

- Python  
- Apache Kafka  
- ZooKeeper  
- AWS EC2  
- Amazon S3  
- AWS Glue  
- Amazon Athena  
- Boto3 SDK  

---

## 🎓 Learning Resource

This project was inspired and guided by the following YouTube tutorial series:  
👉 [Watch on YouTube](https://www.youtube.com/watch?v=KerNf0NANMo&list=PLBJe2dFI4sgvQTNNkI3ETYJgNPR4CBpFd&index=5)

---

## 📂 Folder Structure

