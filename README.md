# 🚀 RealTime-Data-Streaming-End-to-End-Data-Pipeline

## 📌 Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [What You'll Learn](#what-youll-learn)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Video Walkthrough](#video-walkthrough)

---

## 🔍 Introduction

Want to build a **real-world, production-style data pipeline** from scratch?

This project is a complete, hands-on guide to designing and implementing a **modern end-to-end data engineering system** — from data ingestion to real-time processing and scalable storage.

You’ll work with industry-standard tools like **Airflow, Kafka, Spark, and Cassandra**, all seamlessly orchestrated and containerized using **Docker**.

By the end, you won’t just understand the theory — you’ll have a **fully working pipeline** that mirrors real-world data engineering systems.

---

## 🏗️ System Architecture

![System Architecture](https://github.com/airscholar/e2e-data-engineering/blob/main/Data%20engineering%20architecture.png)

This pipeline is designed to simulate a **real-time data ecosystem**, consisting of:

### 🔹 Data Source
- Uses the `randomuser.me` API to generate realistic streaming user data.

### 🔹 Orchestration Layer
- **Apache Airflow** schedules and manages workflows.
- Extracted data is stored in **PostgreSQL**.

### 🔹 Streaming Layer
- **Apache Kafka** enables real-time data streaming.
- **Apache Zookeeper** ensures distributed coordination and reliability.

### 🔹 Monitoring & Schema Management
- **Control Center** for monitoring Kafka streams.
- **Schema Registry** for managing data formats and consistency.

### 🔹 Processing Layer
- **Apache Spark (Master + Workers)** processes data at scale in real time.

### 🔹 Storage Layer
- Processed data is stored in **Cassandra**, optimized for high availability and fast reads/writes.

---

## 🎯 What You'll Learn

By building this project, you’ll gain practical experience in:

- ⚡ Designing scalable **data pipelines**
- 🔄 Real-time streaming using **Apache Kafka**
- 📅 Workflow orchestration with **Apache Airflow**
- ⚙️ Distributed data processing with **Apache Spark**
- 🧠 Understanding **Zookeeper’s role** in distributed systems
- 💾 Working with both **SQL (PostgreSQL)** and **NoSQL (Cassandra)** databases
- 🐳 Containerizing complex systems using **Docker**

---

## 🧰 Tech Stack

- **Apache Airflow** – Workflow orchestration  
- **Python** – Core programming language  
- **Apache Kafka** – Real-time streaming  
- **Apache Zookeeper** – Distributed coordination  
- **Apache Spark** – Data processing engine  
- **Cassandra** – NoSQL database  
- **PostgreSQL** – Relational database  
- **Docker** – Containerization & deployment  

---

