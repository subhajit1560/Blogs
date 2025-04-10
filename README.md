# 🔥🐼 FireDucks vs. Pandas: Streamlining Large-Scale Data Processing for AI Workflows

This repository accompanies my blog **“FireDucks vs. Pandas: When to Choose Each for AI & Data Science Challenges”** — a practical exploration of when and why to use **FireDucks** over **Pandas** for large-scale data science and AI tasks.

---

## 📄 Blog

📝 Read the full blog here:  
[**FireDucks vs. Pandas (Google Docs)**](https://docs.google.com/document/d/1zRjNhUajMDc-D_gcPX2bxTDNa9zXvIXuZkWGwUQtzPw/edit?usp=sharing)

---

## 🧪 Colab Notebook

🚀 Run all code and benchmarks directly in Google Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10uFR_I6bPA_kIY3EYcQpq0B3GLGr4vck?usp=sharing)

This Colab notebook includes:

- 📥 Reading & processing large CSV files  
- 📊 GroupBy & aggregation comparisons  
- 🔍 Filtering, sorting, and EDA on big data  
- 📈 Performance benchmark plot with `matplotlib`

---

## 🔧 Technologies Used

- [FireDucks](https://pypi.org/project/fireducks/) – High-performance data processing
- [Pandas](https://pandas.pydata.org/) – Baseline for data manipulation
- [Matplotlib](https://matplotlib.org/) – For benchmark visualizations
- Google Colab – To run all code in the cloud

---

## ⚡ Benchmarks at a Glance

| Operation         | Pandas Time | FireDucks Time | Speedup |
|------------------|-------------|----------------|---------|
| Read CSV         | 3.45s       | 1.12s          | ~3x     |
| GroupBy Mean     | 8.76s       | 2.34s          | ~4x     |
| Filter + Sort    | 5.67s       | 1.89s          | ~3x     |


---

## 📦 Try It Yourself

Install FireDucks using pip:

```bash
pip install fireducks
