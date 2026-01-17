# High-Throughput E-Commerce Streaming Analytics & Security Detection System

## 📌 Overview

This project is a scalable, cloud-native **eCommerce analytics and security detection system** built on **AWS**. It processes **67M+ events** using batch and real-time pipelines to deliver business insights while detecting anomalous traffic, bots, and potential DDoS attacks in near real time.

The system is designed for **high throughput, low latency, fault tolerance, and cost-efficient storage**, making it suitable for large-scale data-driven platforms.


<img width="1536" height="1024" alt="project-diagram" src="https://github.com/user-attachments/assets/6222f171-1cb2-4013-ab52-aac1874d92d7" />

---

## 🏗️ System Architecture

**Data Sources**

* User clickstream events
* Product views, cart actions, and purchases
* Web traffic logs

**Analytics Layer**

* Batch processing for historical analysis
* Real-time streaming for live insights

**Security Layer**

* Stateful stream processing for behavior tracking
* Automated detection of bots and DDoS patterns

---

## 🚀 Key Features

* Processed **67M+ eCommerce events** at scale
* Batch and real-time analytics pipelines on AWS
* Traffic, cart abandonment, category, and brand insights
* **Apache Hudi** for low-latency analytics and storage optimization
* Real-time **bot and DDoS detection** using streaming analytics
* Automated alerting for suspicious activity

---

## 🛠️ Tech Stack

**Cloud & Storage**

* AWS S3
* DynamoDB

**Streaming & Processing**

* Amazon Kinesis
* Apache Flink

**Data Lake & Analytics**

* Apache Hudi
* AWS Glue / Athena (optional for querying)

**Monitoring & Alerts**

* CloudWatch
* Custom alerting logic

---

## ⚙️ Data Pipeline Flow

1. Events are ingested via **Amazon Kinesis**
2. **Apache Flink** performs real-time transformations and stateful processing
3. Security rules detect abnormal behavior (bots, spikes, DDoS patterns)
4. Alerts are triggered and state is stored in **DynamoDB**
5. Events are written to **Apache Hudi tables on S3**
6. Batch analytics queries provide business insights

---

## 📊 Performance Optimizations

* **~50% faster query performance** using Apache Hudi
* **~40% storage reduction** through optimized file layouts
* Low-latency streaming analytics with stateful processing

---

## 🔐 Security Detection Logic

* Rate-based anomaly detection
* Behavioral pattern analysis
* Stateful IP/session tracking
* Automated alerts for suspicious traffic

---
## proofs
<img width="1505" height="255" alt="Screenshot 2025-12-12 182959" src="https://github.com/user-attachments/assets/a9b29baa-c078-49aa-81a8-8a42e6d403db" />
<img width="558" height="474" alt="Screenshot 2025-12-13 001548" src="https://github.com/user-attachments/assets/18d013c4-dd5f-4fc0-94c5-6fe3cecba141" />
<img width="1861" height="667" alt="Screenshot 2025-12-12 211919" src="https://github.com/user-attachments/assets/861a72b7-2f11-442e-bc1a-d1e557a71613" />
<img width="475" height="503" alt="Screenshot 2025-12-12 212051" src="https://github.com/user-attachments/assets/112d6e33-69a0-4580-9a5a-eccf281cfa54" />
<img width="991" height="585" alt="Screenshot 2025-12-10 022353" src="https://github.com/user-attachments/assets/af2e7c66-708f-4f4b-90fe-5f4ef1169f57" />
<img width="1084" height="419" alt="Screenshot 2025-12-10 022659" src="https://github.com/user-attachments/assets/a98c9e27-7cfa-4681-be3e-0cc857ad1b53" />


--- 

## 📈 Use Cases

* Real-time traffic monitoring
* Cart abandonment analysis
* Category and brand performance tracking
* Bot and DDoS attack detection
* Operational monitoring for eCommerce platforms

---

⭐ If you find this project useful, feel free to star the repository!
