# 💳 SpendDNA – Your Wallet's Year-End Story

> **"Spotify Wrapped for your money."**
> A Python-based fintech analytics project that analyzes transaction data to uncover spending patterns, financial behaviors, anomalies, and spending personality archetypes.

---

## 📌 Project Overview

SpendDNA is a financial transaction analytics system developed using Python, Pandas, and NumPy. The project analyzes six months of UPI and bank transaction data to generate meaningful insights into spending habits, vendor preferences, monthly trends, anomalies, and financial personality traits.

This project simulates real-world transaction analytics workflows commonly used in fintech companies for merchant normalization, spending categorization, behavioral analytics, and anomaly detection.

---

## 🎯 Objectives

* Parse and clean real-world style financial transaction data
* Normalize merchant/vendor names from messy transaction descriptions
* Categorize transactions into meaningful spending categories
* Analyze spending behavior and monthly trends
* Detect anomalous transactions using statistical methods
* Identify spending personality archetypes
* Generate a comprehensive financial analytics report

---

## 📊 Dataset Information

| Attribute                   | Details                  |
| --------------------------- | ------------------------ |
| Dataset                     | `rahul_transactions.csv` |
| Time Period                 | January 2024 – June 2024 |
| Total Transactions          | 1,328                    |
| Transactions After Cleaning | ~1,310                   |
| Duplicate Rows              | 18                       |
| Transaction Types           | UPI, POS, ATM, Credit    |
| Unique Vendors              | ~35                      |

The dataset contains realistic Indian banking and UPI transaction patterns, including:

* Multiple date formats
* Multiple currency formats
* Merchant aliases
* Personal transfers
* ATM withdrawals
* Duplicate records
* Missing values

---

## 🚀 Features Implemented

### ✅ Feature 1 – Transaction Parser

* Parsed four different date formats
* Processed multiple amount formats
* Standardized transaction types
* Removed duplicate records

### ✅ Feature 2 – Vendor Extraction

* Built a merchant normalization engine
* Mapped multiple vendor aliases to canonical vendors
* Identified P2P transfers and ATM withdrawals

### ✅ Feature 3 – Category Tagging

Transactions categorized into:

* Food Delivery
* Quick Commerce
* E-commerce
* Investments
* Transport
* Cafe
* Entertainment
* Fuel
* Groceries
* Subscriptions
* Personal Transfer
* Cash Withdrawal

### ✅ Feature 4 – Spending Overview

* Total credits and debits
* Savings rate analysis
* Top spending categories
* Top spending vendors

### ✅ Feature 5 – Monthly Trend Analysis

* Month-wise spending trends
* Spending growth and decline analysis

### ✅ Feature 6 – Time-of-Day Analysis

* Hourly spending patterns
* Late-night spending behavior detection

### ✅ Feature 7 – Anomaly Detection

* Statistical anomaly detection using Z-score
* Identification of unusually large transactions

### ✅ Feature 8 – Spending Archetype Detection

Detected financial personality archetypes such as:

* THE FOODIE
* THE QUICK COMMERCE JUNKIE
* THE SHOPAHOLIC
* THE INVESTOR
* THE LATE-NIGHT SNACKER
* THE YOLO SPENDER

---

## 🛠️ Technology Stack

* Python
* Pandas
* NumPy
* Datetime Module
* Exploratory Data Analysis (EDA)

---

## 📂 Project Structure

```text
SpendDNA-Financial-Analytics/
│
├── SpendDNA_Vinisha.ipynb
├── rahul_transactions.csv
├── README.md
└── report_screenshot.png
```

---

## 📈 Sample Output

The final output generates a formatted financial report containing:

* Executive Summary
* Spending Breakdown
* Top Vendors
* Monthly Trends
* Time-of-Day Patterns
* Anomaly Detection
* Spending Archetypes
* Financial Insights

> Add your final report screenshot below:

![SpendDNA Report](report_screenshot.png)

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/SpendDNA-Financial-Analytics.git
```

2. Navigate to the project folder:

```bash
cd SpendDNA-Financial-Analytics
```

3. Ensure the following files are present:

* `SpendDNA_Vinisha.ipynb`
* `rahul_transactions.csv`

4. Open the notebook using Jupyter Notebook or Google Colab.

5. Run all cells sequentially.

---

## 💡 Key Learnings

This project provided practical experience in:

* Financial data cleaning
* Merchant normalization
* Transaction analytics
* Behavioral analysis
* Statistical anomaly detection
* Fintech data processing workflows
* Exploratory Data Analysis

---

## 🔍 Industry Relevance

This project mirrors transaction analytics workflows commonly used in fintech companies such as:

* Cred
* Jupiter
* Fi Money
* Slice
* PhonePe
* OneCard

Key industry concepts implemented include:

* Merchant normalization
* Spending categorization
* Behavioral profiling
* Anomaly detection
* Financial trend analysis

---

## 🔗 Project Links

**GitHub Repository:** Add your GitHub repository link here

**Google Colab Notebook:** Add your Google Colab link here

---

## 👩‍💻 Author

**Vinisha**

Aspiring Data Analyst | Python Developer | Data Science Enthusiast

---

### ⭐ If you found this project interesting, please consider giving it a star.
