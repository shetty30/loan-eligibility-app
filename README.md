# 🏦 Loan Eligibility Checker

**Loan Eligibility Checker** is a Python-based web app built with **Streamlit** that helps users determine whether they’re eligible for a loan based on financial inputs like income, age, and existing EMIs.

This tool simplifies the eligibility process and gives quick results — great for both personal use and learning financial logic implementation with Python.

---

## 🌟 Features

- 🔍 Takes user input for age, income, loan amount, loan term, and EMI
- 📊 Calculates basic loan eligibility instantly
- 🚫 Displays eligibility status with easy-to-understand logic
- 👩‍💻 User-friendly and interactive interface (Streamlit)

---

## ⚙️ Tech Stack

| Tech       | Used For                        |
|------------|----------------------------------|
| Python     | Core logic and backend          |
| Streamlit  | Web app frontend                |
| GitHub     | Version control                 |

---

## 🧠 How It Works

1. User enters:
   - Age
   - Monthly income
   - Existing EMI obligations
   - Desired loan amount
   - Loan tenure

2. App checks:
   - If age is within acceptable range
   - If the user's EMI-to-Income ratio is acceptable (e.g. < 40%)

3. Based on these, the app returns:
   - ✅ Eligible
   - ❌ Not Eligible (with reason)

---

## 📦 Installation (For Local Use)

```bash
git clone https://github.com/shetty30/loan-eligibility-checker.git
cd loan-eligibility-checker
pip install -r requirements.txt
streamlit run app.py