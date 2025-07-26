

#  MongoDB Daily Payment Report Generator

This Python project automates the generation of a daily PDF report summarizing payment statuses from a MongoDB database. It was developed to streamline client reporting at a FinTech company.

## 📌 Objective

Automatically extract and visualize daily payment data, including:
-  Successful payments
-  Failed payments
-  Payments with errors

The script creates a visually styled PDF report with pie charts and key counts.

## 🛠 Technologies Used

- **Python**
- **pymongo** – MongoDB querying
- **matplotlib** – Pie chart generation
- **fpdf** or **reportlab** – PDF formatting
- **yaml** – For DB config (optional)

## ⚙️ How It Works

1. Connects to MongoDB via URI
2. Queries payment data for a given date
3. Aggregates counts of success, fail, and error
4. Creates pie charts
5. Generates a PDF with embedded visuals


