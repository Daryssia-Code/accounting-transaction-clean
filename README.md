# Transaction Cleaner

A Python script to clean, normalize, and summarize Excel transaction files.

---

## 🛠 Features

- Load raw transaction Excel files.
- Normalize string and date columns.
- Remove unnecessary columns (`Conversion Amount`, `Foreign Currency Amount`).
- Exclude transactions for non-required month/s (please customize).
- Automatically detect and remove reversal transactions (e.g., payment reversals, failed payments).
- Aggregate transactions by `Code` and other relevant fields.
- Label each transaction as **Credit** or **Debit**.
- Export cleaned and summarized data to a new Excel file.

---

## 📦 Requirements

- Python 3.8+
- Libraries:
  - `pandas`
  - `numpy`
  - `openpyxl`  

Install dependencies:

```bash
pip install pandas numpy openpyxl
