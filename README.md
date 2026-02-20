☕ Coffee Sales Analysis (Python Data Analysis Project)

This project analyzes real coffee shop transaction data collected from two different time-period datasets and transforms raw sales records into meaningful business insights using Python.

The workflow includes data validation, cleaning, transformation, analysis, OOP module creation, and automated reporting.

📂 Dataset Information

Source: Two CSV transaction files (index_001.csv and index_002.csv)

Total records after merging: 3,898 transactions

Features available:

Date & DateTime

Payment Type (Cash / Card)

Card ID

Transaction Amount

Coffee Product Name

The datasets initially had inconsistent schemas (missing card column in one file), which were aligned before merging. 

Coffee Sales Analysis

🔧 Data Cleaning & Preparation

Steps performed:

Validated both datasets structure before merging

Added missing column (card) to second dataset

Combined datasets into single dataframe

Converted date & datetime columns to proper datetime format

Handled missing values:

Filled missing datetime using date

Replaced missing card values with "No Card"

Created new feature → payment_category (Cash vs Digital)

After cleaning → 0 missing values remained 

Coffee Sales Analysis

📊 Exploratory Data Analysis (EDA)
💰 Revenue Insights

Total Revenue: 122,321.58

Average Transaction Value: 31.38 

Coffee Sales Analysis

☕ Top Selling Coffee Products

Americano with Milk — 824 orders

Latte — 806 orders

Americano — 593 orders

Cappuccino — 517 orders

Cortado — 292 orders 

Coffee Sales Analysis

💳 Payment Behavior

Cash Sales: 5,207

Digital/Card Sales: 117,114.58

➡️ Majority customers prefer digital payments 

Coffee Sales Analysis

🧠 Object-Oriented Analysis Module

A reusable Python class was built to perform automated analysis:

SalesAnalysis class functions

total_revenue()

average_transaction_value()

product_popularity()

payment_trends()

This allows running analytics on any new dataset without rewriting code. 

Coffee Sales Analysis

📈 Automated Reporting & Visualization

The project automatically generates charts and saves them into a reports folder:

Top selling products (Bar chart)

Daily revenue trend (Line chart)

Payment mode distribution (Bar chart)

It also includes error handling:

Missing file detection

Empty dataset validation

Safe report generation 

Coffee Sales Analysis

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

OOP (Reusable Analytics Module)

🎯 Project Outcome

The project converts raw coffee shop transaction logs into a decision-making dashboard by:

Identifying best-selling items

Understanding customer payment behavior

Tracking revenue performance

Automating business reports
