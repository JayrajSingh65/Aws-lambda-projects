### Real-World AWS Lambda Projects | Production-Grade | Event-Driven Architecture

> **Mastering Lambda** is a hands-on repository focused on building **real-world, production-ready AWS Lambda projects**.
>
> Every project here solves a **real cloud problem** using **event-driven serverless design**

---

## 📌 What This Repository Is About

This repository contains **6 end-to-end AWS Lambda projects**  that cover:

* Security automation
* Disaster recovery & failover
* Log processing & data masking
* Event-driven workflows
* AI-powered media pipelines
* Streaming & real-time processing

Each project is:

* ✅ Built step-by-step
* ✅ Event-driven (SNS, EventBridge, S3, CloudWatch, Kinesis, Step Functions)
* ✅ Focused on **real production use-cases**
* ✅ Designed with **least-privilege IAM** and best practices


## 🧠 Projects Included

### 🔐 1. IAM Access Key Auto-Rotation & Deletion

Automates detection and cleanup of exposed IAM access keys using SNS, EventBridge, and Lambda.

**Highlights**

* Detect leaked access keys
* Notify via email
* Automatically delete keys more than 90days

---

### 🛡️ 2. GuardDuty Automated Quarantine

Automatically isolates compromised EC2 instances when GuardDuty raises a finding.

**Highlights**

* GuardDuty → EventBridge → Lambda
* Applies quarantine security group
* Zero manual intervention

---

### 🌍 3. Multi-Region Disaster Recovery with Route53

Implements **automatic DNS failover** using Route53 health checks and Lambda.

**Highlights**

* Primary & DR regions
* Health-based failover
* SNS-driven Lambda execution

---

### 🧹 4. API Log Scrubber (PII Masking)

Cleans sensitive data from application logs before storing them securely in S3.

**Highlights**

* Masks emails, phone numbers, credit cards
* CloudWatch Logs → Lambda → S3
* Compliance-friendly logging

---

### ⚡ 5. Real-Time Fraud Detection with Kinesis

Processes streaming transactions in real time and stores suspicious activity in DynamoDB.

**Highlights**

* Kinesis stream trigger
* DynamoDB persistence
* Near real-time processing

---

### 🎬 6. AI-Powered Media Processing Pipeline

A complete **serverless media factory** using multiple AWS AI services.

**Highlights**

* S3 → Step Functions → Lambda
* Video analysis, transcription, metadata storage
* SNS notifications on completion


---

## 🛠️ Tech Stack Used

* AWS Lambda
* Amazon EventBridge
* Amazon SNS
* Amazon S3
* Amazon DynamoDB
* Amazon Kinesis
* AWS Step Functions
* Amazon GuardDuty
* Amazon Route53
* AWS AI Services (Rekognition, Transcribe, Bedrock)

---

## 🧩 Design Principles Followed

* Least-Privilege IAM
* Event-Driven Architecture
* Fault Tolerance
* Multi-Region Awareness
* Clean Separation of Responsibilities
* Production-ready structure

---
