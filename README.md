# 📊 Trader Behavior vs Market Sentiment (Fear & Greed)

> Hiring Assignment — Junior Data Scientist (Web3 Trading)

**Candidate:** Ahmed Mushaf

---

## 🚀 What This Project Shows

This project analyzes **how trader behavior changes under different market sentiment regimes** (Fear, Greed, etc.) using real Hyperliquid trading data + the Fear & Greed Index.

It answers:

- Do traders take **more risk** during Fear or Greed?
- When do **big losses** happen?
- When is **overtrading** most common?
- Which sentiment regime is **most dangerous**?

---

## 🧠 Key Findings (TL;DR)

- 🔥 **Fear = highest risk + highest trading activity**
- 💥 **Greed = biggest blow-up losses**
- 🧘 **Neutral = most stable regime**
- ⚠️ **Fear is more dangerous systemically than Greed**

(Details in `ds_report.pdf`)

---

## 📂 Repo Structure

```
ds_ahmed_mushaf/
├── notebook_1.ipynb
├── ds_report.pdf
├── README.md
├── csv_files/
│   └── sentiment_summary.csv
└── outputs/
    ├── trades_count.png
    ├── pnl_distribution.png
    └── risk_comparison.png
```

---

## 📊 What’s Inside

- ✅ Real-world messy data cleaning (DD-MM-YYYY timestamps)
- ✅ Feature engineering (risk, PnL, behavior flags)
- ✅ Sentiment-based behavioral analysis
- ✅ Clear visualizations
- ✅ Business-grade conclusions & recommendations

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib
- Google Colab

---

## ▶️ How To Run

1. Open `notebook_1.ipynb` in Google Colab  
2. Upload CSVs into `csv_files/`  
3. Run all cells top-to-bottom  

Outputs auto-save to `outputs/`.

---

## 📄 Report

👉 **Read the final insights here:** `ds_report.pdf`

---

## 🎯 Why This Matters

This project shows how **sentiment can be used as a first-class risk signal** for:

- Position sizing limits  
- Trade frequency throttling  
- Platform-level risk controls  

---

## 📬 Candidate

**Ahmed Mushaf**  
(Details shared in application)
