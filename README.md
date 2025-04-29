# 💰 Personal Finance Manager

**Live Demo:** [https://personal-finance-manager-szymleg.streamlit.app/](https://personal-finance-manager-szymleg.streamlit.app/)

A simple web application built with **Python**, **Streamlit**, and **Plotly** for managing personal finances. The app allows you to upload CSV files containing your transaction history, categorize your expenses, and visualize your financial data.

## 🚀 Features

- 📁 Upload CSV files with transaction details.
- 🏷️ Automatically categorize expenses based on keywords.
- ✏️ Edit and add new categories.
- 📊 Visualize spending with pie charts.
- 💾 Categories are saved in `categories.json` for persistence.

## 📝 CSV File Format

Ensure your CSV file contains the following columns:
- `Date` (e.g., `01 Jan 2024`)
- `Details` (description of the transaction)
- `Amount` (e.g., `123.45`)
- `Debit/Credit` (either `Debit` or `Credit`)

## 📦 Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/SzymLeg/personal-finance-manager.git](https://github.com/SzymLeg/personal-finance-manager.git)
    cd personal-finance-manager
    ```
2.  **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the app:**
    ```bash
    streamlit run main.py
    ```

## 📂 Project Structure

```bash
personal-finance-manager/
├── main.py           # Main Streamlit application
├── categories.json   # Stores the categories for transactions
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```

## ℹ️ About Me

Hi there! I'm **Szymon Legierski**, also known as **SzymLeg**. I'm an IT student and passionate about Data Engineering!
