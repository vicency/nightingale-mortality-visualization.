#  Florence Nightingale Coxcomb Chart Recreation

![Nightingale Coxcomb](images/coxcomb_comparison.png)

**Recreating Florence Nightingale’s iconic 1858 data visualization using Python** — in celebration of Girl Child Month with She Code Africa.

## 📌 Project Overview

This project recreates **Florence Nightingale’s famous Coxcomb (Polar Area) Chart**, one of the earliest and most influential data visualizations in history.

During the Crimean War (1854–1856), Nightingale collected data on soldier mortality and used her coxcomb diagrams to demonstrate that **far more soldiers died from preventable diseases than from battle wounds**. Her compelling visualization led to major sanitary reforms in military hospitals and saved thousands of lives.

In this project, I analyzed two years of historical data (1854–1855 and 1855–1856) and recreated the charts using modern Python tools.

## ✨ What I Built

- Cleaned and transformed two messy historical Excel datasets
- Reshaped data from wide to long format for visualization
- Recreated the **polar area (coxcomb) charts** for both periods
- Combined both visualizations for easy comparison
- Highlighted the dramatic reduction in disease deaths after sanitary improvements

## 🛠️ Tech Stack

- **Python**
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Mathematical operations (square root transformation)
- **Janitor** – Simplified data cleaning
- **Lets-Plot** – Beautiful statistical visualizations

## 📂 Project Structure

```
nightingale-coxcomb-recreation/
├── data/
│   └── raw/
│       ├── raw_night_1854_1855.xlsx
│       └── raw_night_1855_1856.xlsx
├── notebooks/
│   └── night.ipynb          ← Main analysis notebook
├── src/
│   └── visualization.py     ← (Optional) reusable functions
├── images/
│   ├── coxcomb_1854_1855.png
│   ├── coxcomb_1855_1856.png
│   └── comparison.png
├── requirements.txt
└── README.md
```

# 🔍 Key Insights

- In 1854–1855, preventable **disease deaths** (blue) dominated, especially during the harsh winter months.
- After implementing sanitation reforms, disease mortality dropped dramatically in 1855–1856.
- The coxcomb chart effectively shows **proportional impact** using area rather than height — a brilliant design choice by Nightingale.

This project demonstrates how **data visualization can drive real-world change** — a lesson still relevant 150+ years later.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/vicency/florence-nightingale-coxcomb.git
   cd florence-nightingale-coxcomb
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/night.ipynb
   ```

## 📊 Visualizations

- **1854–1855 Coxcomb Chart**: Shows high disease mortality
- **1855–1856 Coxcomb Chart**: Shows significant improvement after reforms
- Side-by-side comparison (recommended to add to repo)

## 🎯 Learning Outcomes

- Handling messy historical datasets
- Data reshaping with `pivot_longer()`
- Understanding polar coordinates and area-based visualizations
- Recreating historical charts with modern libraries
- The power of persistence in data projects

## 🙏 Acknowledgments

Special thanks to **She Code Africa** for the learning opportunity and support during Girl Child Month. 💙

This was my first major data visualization project — and a powerful reminder that **data has the power to inform, persuade, and transform**.

---

**Made with ❤️ for #GirlChildMonth**

#SheCodeAfrica #WomenInTech #DataVisualization #Python #DataAnalytics #LearningInPublic
```
  
