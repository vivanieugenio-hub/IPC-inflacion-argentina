# 📈 Argentine Inflation Analysis — CPI INDEC (2016 · 2023 · 2025)

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Data Source](https://img.shields.io/badge/Source-INDEC%20IPC-lightgrey)

Comparative analysis of Argentina's **Consumer Price Index (CPI / IPC)** evolution across three distinct economic and political periods, using official INDEC data. The project maps how inflation behaved under three different administrations, identifying which spending categories drove price increases in each context.

---

## 🎯 Objective

Provide a data-driven, politically contextualized reading of Argentine inflation — translating official CPI statistics into clear trends and cross-period comparisons accessible to both technical and non-technical audiences.

---

## 🔍 Analyses Performed

1. **2016 General CPI evolution** — first year of INDEC's modern CPI methodology
2. **Accumulated variation by category (2016)** — which spending segments rose most
3. **Top 3 categories by inflation (2016)** — trajectory comparison
4. **Annual accumulated inflation by division** — 2023 vs. 2025 comparison
5. **Cross-category comparison chart** — 2023 basket vs. 2025 basket
6. **Monthly General CPI evolution** — month-by-month trajectory per period

---

## 📊 Key Findings by Period

| Indicator | 2016 (Apr–Nov) | 2023 (Full year) | 2025 (Jan–Oct) |
|-----------|---------------|-----------------|----------------|
| Accumulated CPI (General) | **15.5%** | **211.2%** | **24.8%** |
| Monthly average | ~2.2% | ~10.0% | ~2.2% |
| Highest category | Other goods & services (+27%) | Food & Beverages (+251.2%) | Housing & utilities (+32.3%) |

---

## 💡 Political-Economic Reading

- **2016** marked the launch of INDEC's modern CPI under the Macri administration, with moderate but sustained inflation following currency devaluation and utility tariff adjustments. *Other goods & services* led the increase (+27%), followed by *Healthcare* (+21%).

- **2023** represented the highest inflationary peak since the 1989–1990 hyperinflation. *Food & Beverages* surpassed 251% annual accumulation under the Massa economy ministry, hitting lower-income households hardest.

- **2025** shows a sustained deceleration since May, with the General CPI stabilizing around 2% monthly under the Milei administration. *Housing* leads (+32.3%), reflecting utility tariff normalization after years of subsidized rates.

- **Read alongside the EPH labor market analysis**: the 2025 disinflation trend coexists with persistently high informality (~40%) and structural youth unemployment (20.3%) — suggesting that price stabilization has not yet translated into broad improvements in real income or formal employment.

---

## 🛠️ Tools & Stack

- **Python** — Pandas, Matplotlib
- **Google Colab** — interactive notebook environment
- **Data source:** [IPC — INDEC](https://www.indec.gob.ar)

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/vivanieugenio-hub/IPC-inflacion-argentina.git

# Open the notebook in Google Colab or Jupyter
# No local installation required — all dependencies run in Colab
```

1. Open `IPC_inflacion_argentina.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Download the relevant IPC datasets from [INDEC](https://www.indec.gob.ar)
3. Upload the data files and run all cells

---

## 📁 Project Structure

```
IPC-inflacion-argentina/
│
├── IPC_inflacion_argentina.ipynb    # Main analysis notebook
└── README.md
```

---

## 🔗 Related Projects

- [Argentine Labor Market Analysis — EPH](https://github.com/vivanieugenio-hub/EPH-mercado-laboral-argentina) — complements this inflation analysis with employment, informality, and wage gap data.
- [LATAM Tech Labor Market Analysis](https://github.com/vivanieugenio-hub/latam-tech-labor-market-analysis) — regional tech sector salary and remote work trends.

---

## 👤 Author

**Eugenio Vivani** — Political Science & International Relations | Junior Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-eugenio--vivani-blue?logo=linkedin)](https://www.linkedin.com/in/eugenio-vivani)
[![GitHub](https://img.shields.io/badge/GitHub-vivanieugenio--hub-black?logo=github)](https://github.com/vivanieugenio-hub)
