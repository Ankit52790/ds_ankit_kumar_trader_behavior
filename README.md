## 📓 Colab Notebook
[Open in Google Colab](https://colab.research.google.com/drive/YOUR_NOTEBOOK_ID)

---

## ⚙️ How to Run the Notebook
1. Open `notebook_1.ipynb` in **Google Colab**.
2. Upload the raw datasets:
   - `historical_data.csv`
   - `fear_greed_index.csv`
3. Run all cells from top to bottom.
4. All processed CSVs will be saved to `/csv_files/`.
5. All charts will be saved to `/outputs/`.

---

## 📊 Features Created
- **profit**: Same as Closed PnL.
- **is_win**: 1 if profit > 0, else 0.
- **abs_leverage** & **leverage_bin**: Placeholder (not available in this dataset).
- **trade_value_usd**: USD value of the trade.
- **trade_hour** & **day_of_week**: Time-related features for trading patterns.

---

## 📈 Insights Summary
- **Higher win rate** observed during *Greed* periods.
- **Profitability trends** suggest sentiment influences trader success.
- **Trade activity** is more intense during Greed periods.

Full details are available in `ds_report.pdf`.

---

## 🛠 Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn

---

## 📧 Contact
Prepared by **Ankit Kumar** for the Junior Data Scientist – Trader Behavior Insights assignment.

