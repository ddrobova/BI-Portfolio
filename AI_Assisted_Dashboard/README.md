# 🚗 Car Sales Analytics Dashboard

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![AI](https://img.shields.io/badge/AI-MiniMax-blueviolet?style=flat-square)
![Kaggle](https://img.shields.io/badge/Data-Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)

Interactive dashboard for used car market analysis, built as an experiment in AI-assisted data visualization.

🔗 **[Live Demo](https://car-analytics-2026.surge.sh/)**

<img width="1927" height="1057" alt="image" src="https://github.com/user-attachments/assets/7d25eff4-3b70-44c6-baed-02036c6ca558" />
<img width="1925" height="1055" alt="image" src="https://github.com/user-attachments/assets/be41aaba-e0db-4eb1-a7c0-9e7a74f188ca" />


---

## 📊 About

**Goal:** Test how well LLM agents (MiniMax-M3) can generate a full interactive front-end from text prompts — without manual coding.

**Data:** [Car Sales dataset](https://www.kaggle.com/) from Kaggle (~16,000 records).
**Key metrics:** Avg price ($12.81K), Avg mileage (72,620 mi), Median year (2015), Top brands, Country & body type distribution.

---

## 🛠️ How It Was Built

1. Selected open Kaggle dataset (make, model, mileage, condition, selling price, MMR).
2. Configured and iteratively prompted **MiniMax-M3**.
3. The AI generated full HTML, CSS, and JS for interactive filters and visualizations.
4. Added dynamic charts and car images.

> **Key insight:** No deep HTML/JS knowledge was required. Just clear business logic and design guidance. The AI handled all the coding.

---

## ✨ Features

- Interactive filters (Year, Body Type, Brand, Country, Transmission, Condition)
- Dynamic KPI cards (avg price, mileage, revenue, etc.)
- Responsive design
- Fully static HTML build (easy to host on any CDN)

