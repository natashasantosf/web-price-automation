# 🛒 Web Price Automation

This project automates the process of comparing product prices across multiple websites using **Python and Selenium**.

It simulates a real-world scenario from a purchasing department:  
checking suppliers’ websites to find the best prices and automatically sending an email report when items are below a defined target price.

---

## 🎯 Objective
To automate price collection from different sources (Google Shopping, Buscapé) and generate a report with the most affordable options within a price range.

---

## ⚙️ How It Works
1. Reads a spreadsheet (`produtos.xlsx`) containing:
   - Product name
   - Maximum price
   - Minimum price
   - Terms to exclude from search

2. For each product:
   - Searches on **Google Shopping** and **Buscapé**
   - Collects price, product name, and purchase link
   - Filters valid results (within price range)

3. Generates a report and sends an **email notification** with the results.

---

## 🧠 Technologies Used
- **Python**
- **Selenium** – Web automation
- **Pandas** – Data handling and Excel processing
- **smtplib** / **email** – Sending reports via email
- **OpenPyXL** – Spreadsheet manipulation

---

## 📂 Project Structure
web-price-automation/
│
├── main.py # Main automation script
├── produtos.xlsx # Example input file
├── requirements.txt # Project dependencies
└── README.md # Documentation

---

## 🧩 Example Workflow
1. Define your max/min prices in the spreadsheet.
2. Run the script:
   ```bash
   code.ipynb
3. Receive an email with a list of all products under your target price.

---

## 🚀 Results
This project demonstrates:
- Web scraping and automation with Selenium
- Data validation and processing with Pandas
- Sending email reports automatically
- Real-world automation use case for businesses

---

## 📬 Contact

📧 natasha.s.felipel@gmail.com

🌐 UpWork Profile: https://www.upwork.com/freelancers/~013c7057dae33df28b?mp_source=share

