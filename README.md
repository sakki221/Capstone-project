# Capstone-project

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
    C --> D[Dynamic Pricing Model (Pathway)]
    D --> E[Output to Real-Time Dashboard / Log]

---

## 🧠 Project Architecture & Workflow

1. **Input Data**
   - Parking logs, timestamps, and availability data are ingested (CSV or real-time sensors).

2. **Preprocessing**
   - Cleaned using `pandas` and `numpy`.
   - Features like `hour_of_day`, `day_of_week`, `slot_occupancy_rate`, and `is_peak_hour` were added.

3. **Feature Engineering**
   - Lag features (previous hour's occupancy).
   - Aggregated demand curves.
   - Flags for event days or weekends.

4. **Dynamic Pricing Model (Pathway)**
   - Real-time logic evaluates demand and adjusts prices.
   - Rules like surge pricing, max/min cap, time-based discounts are applied.

5. **Output**
   - Results can be published to dashboard/API or logged to CSV.
