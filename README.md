# Nonprofit Finance Management Software

This project is a simple accounting software built in *Python* to help *nonprofit organizations* manage their finances.  
It follows the voucher → book → report → ledger → balance sheet structure.

## 📌 Features
- Manage 5 types of vouchers:
  - Cash Payment Voucher
  - Cash Receipt Voucher
  - Bank Payment Voucher
  - Bank Receipt Voucher
  - Journal Voucher
- Maintain *Cash Book* and *Bank Book*
- Generate:
  - Total Expense Summary
  - Office Operational Expenses
  - Monthly Activity Reports (by activity code & name)
  - Ledger Accounts (per activity)
  - Final Balance Sheet

## 🛠️ Requirements
- Python 3.8+
- SQLite3 (built-in with Python)
- Recommended editor:
  - [VS Code](https://code.visualstudio.com/) (best for running locally)
  - or [Google Colab](https://colab.research.google.com/) (online testing)

## 📦 Installation
1. Clone or download this repository.
2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows: venv\Scripts\activate
