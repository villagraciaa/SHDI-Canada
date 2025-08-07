
# Canada SHDI Dashboard (Dash Version)

This project provides an interactive dashboard built with **Dash** to visualize the Subnational Human Development Index (SHDI) for Canada and its provinces/territories from 1990 to 2022.
By Muhammad Ibrahim Shah and Al Rey Villagracia
---

## 📊 Features

- **Interactive SHDI Trends** by selected provinces
- **2022 SHDI Comparison** bar chart
- **Heatmap** of SHDI by region and year
- **LaTeX-rendered documentation tab** explaining SHDI formula and importance

---

## 🧪 How to Run

### Install Requirements
```bash
pip install dash pandas plotly seaborn matplotlib dash-bootstrap-components
```

### Run the App
```bash
python shdi_dash_app.py
```

Visit: [http://127.0.0.1:8050](http://127.0.0.1:8050) in your browser.

---

## 📘 SHDI Formula

\[
\text{SHDI} = \left( I_{\text{education}} \cdot I_{\text{health}} \cdot I_{\text{income}} \right)^{1/3}
\]

---

## 📁 Files

- `shdi_dash_app.py` — Full Dash app script with tabs
- `shdi_dash_dashboard.ipynb` — Jupyter Notebook version of the app
- `GDL-Subnational-HDI-data.csv` — Source dataset from Global Data Lab

---

## 👥 Authors

- Muhammad Ibrahim Shah  
- Al Rey Villagracia
