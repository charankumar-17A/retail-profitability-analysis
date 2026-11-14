# 🛒 Retail Profitability Analysis

> Analyzed **9,994 retail line-item records** → identified **1,871 loss-making records (18.7%)** and traced the margin erosion to deep discounting, ending in an actionable discount-control recommendation.

**Stack:** Python · Pandas · Matplotlib
**Dataset:** [Sample Superstore](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) — 9,994 order-line records (included in `data/`)

---

## 🎯 Business Problem

Retail management suspected some product lines were actively destroying profit. The questions this analysis answers:

1. How much of the catalog is actually **losing money** — and where?
2. What is **driving** those losses?
3. What control can be applied **immediately** to protect margins?

## 🛠 Approach

1. **Data cleaning & validation** — types, dates, category labels, duplicates
2. **Profitability segmentation** — profit distribution by line item, category, sub-category, region
3. **Root-cause analysis** — isolating the relationship between discount depth and loss-making records
4. **Visualization** — Matplotlib charts of margin erosion and loss concentration
5. **Recommendation** — a concrete, immediately actionable margin-control measure

## 📊 Key Findings

| Finding | Number |
|---|---|
| Line items analyzed | **9,994** |
| Loss-making records | **1,871 (18.7%)** |
| Loss records carrying discounts ≥ 20% | **50.5%** |
| Top loss-driving categories | **Binders, Tables, Machines** |

**Recommendation:** cap discount depth in the loss-driving categories — an immediately actionable control that protects margins without broad price changes.

## 📂 Repository Contents

| File | Description |
|---|---|
| `retail_profitability_analysis.ipynb` | Full analysis notebook — cleaning, EDA, root-cause, charts |
| `retail_profitability_analysis.html` | Rendered notebook with outputs (view without running anything) |
| `data/Sample_Superstore.csv` | Source dataset (9,994 records) |

## ▶️ How to Run

```bash
pip install pandas matplotlib jupyter
jupyter notebook retail_profitability_analysis.ipynb
```

---

*Part of my data analytics portfolio — see [github.com/charankumar-17A](https://github.com/charankumar-17A) for more.*
