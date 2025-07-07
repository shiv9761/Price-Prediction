# Price-Prediction
# 🚗 Dynamic Pricing for Urban Parking Lots  
**Summer Analytics 2025 – Capstone Project**  
Hosted by Consulting & Analytics Club × Pathway

---

## 📌 Overview

This project simulates dynamic pricing for 14 urban parking lots using real-time data features like occupancy, traffic, and competition.  

It includes 3 models:  
- **Model 1:** Linear Pricing  
- **Model 2:** Demand-Based Pricing  
- **Model 3:** Competitive & Location-Aware Pricing

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Bokeh (for real-time plots)  
- Google Colab  
- Pathway (for real-time simulation)

---

## 📐 Architecture Diagram

```mermaid
graph TD
    A[Dataset.csv] --> B[Preprocessing]
    B --> C1[Model 1: Linear Pricing]
    B --> C2[Model 2: Demand Pricing]
    B --> C3[Model 3: Competitive Pricing]
    C1 --> D[Real-Time Loop]
    C2 --> D
    C3 --> D
    D --> E[Bokeh Visualization]
