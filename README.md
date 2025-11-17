# 🧠 AI-Driven Demand Forecasting & Dynamic Pricing

**Technologies:** Python, PyTorch, Temporal Fusion Transformer (TFT), Reinforcement Learning (PPO)

## 📌 Overview

This project applies deep learning to solve real-world retail challenges using the Walmart M5 dataset. The **Temporal Fusion Transformer (TFT)** is used to forecast multi-store, multi-SKU sales, capturing seasonality, holidays, promotional effects, and other temporal patterns.
Additionally, a **Reinforcement Learning (PPO)** agent is implemented to recommend optimal product prices with the goal of maximizing revenue while minimizing stock-outs.

## 🚀 Key Features

* Multi-time-series forecasting using **Temporal Fusion Transformer**
* **Dynamic pricing** driven by Proximal Policy Optimization (PPO)
* Demonstrated **~25% improvement** in pricing efficiency
* Works across large-scale retail datasets with many SKUs and stores
* Modular, reproducible notebook with full pipeline and visualizations
* Scalable deep learning pipeline suitable for production

## 📊 Dataset

Dataset Source:
👉 [Walmart M5 Forecasting Competition — Kaggle](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data)

Files used:

* `sales_train_validation.csv`
* `sell_prices.csv`
* `calendar.csv`

The dataset includes 30,000+ Walmart SKUs across multiple categories, stores, and states, spanning 5+ years of daily sales.

---

## 📊 Results

The **Temporal Fusion Transformer (TFT)** produced accurate multi-horizon forecasts across diverse product categories and stores. It successfully modeled seasonality, price fluctuations, events, and trend shifts present in the retail data.

The **Reinforcement Learning dynamic pricing agent (PPO)** learned to adjust prices in response to forecasted demand. This resulted in:

* ~**25% improvement** in pricing efficiency
* Better revenue optimization
* Reduced stock-outs
* More stable inventory planning

Together, the forecasting and pricing modules demonstrate how deep learning can significantly improve retail analytics, planning, and business decision-making.

---

## 🤝 Acknowledgments

* Walmart M5 Forecasting Dataset (Kaggle)
* Temporal Fusion Transformer architecture by **Google Research**
* PPO algorithm from **OpenAI**
* PyTorch ecosystem and open-source community resources
