# 📈 Analyzing Bitcoin Historical Trends Using IBM Granite AI

## 🧠 Project Overview

This project explores the **historical price movements of Bitcoin** using data from Kaggle and advanced analysis powered by **IBM Granite (via Replicate API)**. The project aims not only to extract insights from the data but also to **train and sharpen data analytics skills** using real-world financial data.

---

## 🎯 Project Goals

- 🔍 Strengthen understanding of data analytics workflow: data cleaning, visualization, and insight generation.
- 📊 Generate **real, actionable insights** from Bitcoin price movements.
- 🧠 Practice integrating **Generative AI (IBM Granite)** for automated insight generation and summarization.

---

## ❓ Key Research Questions

1. **What are the long-term trends in Bitcoin's historical prices and trading volumes?**
2. **How does volume correlate with price movement over time?**
3. **Are there recurring patterns or cycles that can help inform investment timing?**
4. **What insights can AI generate from the pattern of Bitcoin’s movement historically?**

---

## 🧰 Dataset & Tools

- 📁 Dataset: [`Bitcoin Historical Price`](https://www.kaggle.com/datasets/adilshamim8/bitcoin-historical-data) from Kaggle  
- 🔧 Tools:
  - Google Colab (Python-based notebook)
  - Pandas, Matplotlib, Seaborn
  - Replicate API (IBM Granite 3.3 - 8B Instruct)
  - Langchain for LLM integration

---

## 📈 Analytical Result

- The dataset covers **Bitcoin’s price, open, high, low, and volume** from 2013 to early 2025.
- **Highest trading volumes and price spikes** are concentrated around:
  - **Late 2017**, **Early 2021**, and an uptick around **2024–2025**.
- **Correlation between Volume and Closing Price:** `~0.67` → indicating moderately strong relationship.
- Cyclical patterns with **sharp bull runs followed by corrections** are evident.

---

## 💡 Insights & Findings (from IBM Granite)

> **“Harga Bitcoin memiliki pola siklus yang terlihat selama 2014 hingga 2025. Ada kenaikan signifikan di tahun 2017 dan 2021, diikuti koreksi harga tajam. Volume perdagangan tinggi cenderung menandai pasar yang volatile. Pola ini cenderung berulang, tapi tetap harus disikapi dengan kehati-hatian karena faktor eksternal bisa memengaruhi pasar.”**

---

## 🎯 Recommendations

- Investor perlu mengenali **pola siklus**: euforia → koreksi → stabil → euforia lagi.
- **Hindari keputusan impulsif** saat harga naik tajam (FOMO).
- Gunakan volume sebagai indikator pendukung saat mengambil keputusan beli/jual.
- Meskipun pola bisa dikenali, **jangan abaikan risiko dan faktor eksternal** (regulasi, sentimen global, dll).

---

## 🚀 How to Run This Project

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/bitcoin-analysis.git
   cd bitcoin-analysis
2. Buka di Google Colab
3. Tambahkan token Replicate anda di:
   from google.colab import userdata
   api_token = userdata.get('api_token')
4. Jalankan seluruh cell dari atas ke bawah.

🙋 About the Author
This project was developed as part of a capstone learning initiative to strengthen real-world data analytics and AI integration skills.
Created by: Muhammad Arifbillah Kamil – Aspiring Data Analyst and AI Explorer.

🏷️ Tags
#Bitcoin #DataAnalytics #Capstone #IBMGranite #TimeSeries #GenerativeAI
