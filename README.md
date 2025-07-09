# 🅿️ Dynamic Pricing for Urban Parking Lots

## 🚀 Overview

This project aims to optimize the pricing of urban parking spaces dynamically based on real-time demand and other influencing factors. It helps maximize revenue while ensuring fair pricing and optimal space utilization.

This was developed as part of the **Summer Analytics 2025 Capstone Project**.

---

## 🧰 Tech Stack Used

- **Python 3.10+**
- **Pandas** – data preprocessing and feature engineering
- **NumPy** – numerical calculations
- **Pathway** – real-time data pipeline and dynamic pricing model implementation

---

## 🧱 Architecture Diagram

```mermaid
graph TD
    A[CSV Input / Sensor Data] --> B[Preprocessing with Pandas & NumPy]
    B --> C[Feature Engineering]
    C --> D[Dynamic Pricing Model using Pathway]
    D --> E[Output to Real-Time Dashboard or Log]
