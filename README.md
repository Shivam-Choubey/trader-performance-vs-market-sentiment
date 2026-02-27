# Trader Performance vs Market Sentiment Analysis

## 📌 Project Objective

Analyze how Bitcoin market sentiment (Fear vs Greed) affects trader behavior and performance using Hyperliquid trading data.

---

## 📂 Datasets

1. Bitcoin Market Sentiment (Fear / Greed)
2. Historical Trader Data (Hyperliquid)

---

## 🧹 Data Preparation

* Loaded and cleaned both datasets
* Checked missing values and duplicates
* Converted timestamps to datetime
* Aligned data at daily level
* Created metrics like:

  * Daily PnL
  * Win rate
  * Trade count
  * Trade size
  * Leverage usage

---

## 📊 Analysis

* Compared trader performance on Fear vs Greed days
* Studied behavior changes:

  * Trade frequency
  * Leverage usage
  * Long/Short bias
* Segmented traders into groups (e.g. high vs low leverage, frequent vs infrequent traders)

---

## 💡 Key Insights

* Performance differs between Fear and Greed market conditions
* Trader behavior changes based on sentiment
* Certain trader segments perform better under specific conditions

---

## 🚀 Strategy Recommendations

* Adjust leverage based on market sentiment
* Increase trade frequency only for specific trader segments

---

## 🛠️ How to Run

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

2. Open the notebook:

```bash
jupyter notebook
```

3. Run all cells to reproduce results.

---

## 📎 Output

* Charts and tables included in the notebook
* Insights and strategy suggestions summarized inside notebook
