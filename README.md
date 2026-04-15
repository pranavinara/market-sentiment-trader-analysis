# 📊 Market Sentiment vs Trader Behavior Analysis

## 📌 Objective

This project analyzes how Bitcoin market sentiment (Fear vs Greed) impacts trader behavior and performance using Hyperliquid trading data.

---

## 📂 Dataset

* Fear/Greed Index dataset
* Historical trader dataset (Hyperliquid)

---

## ⚙️ Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

---

## 🧹 Methodology

* Loaded and cleaned datasets
* Converted timestamps into proper date format
* Merged sentiment and trading data on daily level
* Created key metrics:

  * Daily PnL
  * Win rate
  * Leverage usage
  * Trade frequency
  * Long/Short ratio

---

## 📈 Key Insights

1. Traders tend to use higher leverage during Greed periods, leading to more volatile outcomes.

2. Win rates are relatively more stable during Fear periods, indicating cautious trading behavior.

3. High-frequency traders with moderate leverage show more consistent profitability.

4. Traders exhibit overconfidence during Greed phases, increasing leverage and exposure, which leads to higher volatility in returns.

5. During Fear phases, traders behave more cautiously, resulting in lower but more stable performance.

6. High-frequency traders using moderate leverage achieve more consistent profitability compared to low-frequency high-risk traders.

7. Market sentiment influences not only performance but also decision-making behavior, highlighting psychological bias in trading.

---

## 💡 Strategy Recommendations

1. Reduce leverage during Greed periods to avoid high-risk losses.

2. Focus on consistent trading with controlled risk during Fear periods.

---

## 📊 Visualizations
![Chart](pnl_vs_sentiment_boxplot.png)

**Insight:**
Traders show higher variability in profits during Greed, indicating riskier behavior and inconsistent outcomes.
![Chart](win_rate_vs_sentiment_bar.png)

**Insight:**
Traders show higher variability in profits during Greed, indicating riskier behavior and inconsistent outcomes.
![Chart](long_short_trades_vs_sentiment_bar.png)

**Insight:**
Traders show higher variability in profits during Greed, indicating riskier behavior and inconsistent outcomes.
![Chart](trade_size_vs_sentiment_bar.png)

**Insight:**
Traders show higher variability in profits during Greed, indicating riskier behavior and inconsistent outcomes.
![Chart](long_short_distribution.png)

**Insight:**
Traders show higher variability in profits during Greed, indicating riskier behavior and inconsistent outcomes.


## 📈 Key Insights

- Traders use higher leverage during Greed, increasing risk
- Win rates are more stable during Fear
- High-frequency traders perform more consistently

## 💡 Strategy Recommendations

- Reduce leverage during Greed periods
- Focus on disciplined trading during Fear
## 📌 Conclusion

Market sentiment plays a significant role in shaping trader behavior and performance. Understanding these patterns can help traders make better decisions.


