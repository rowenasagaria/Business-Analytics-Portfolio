# Retail Sales Dashboard (Google Sheets + Apps Script)

## 📌 Overview

This project was made by using this reference [[Youtube Link](https://www.youtube.com/watch?v=zkGoagGpeuY)]

This **Retail Sales Dashboard** is a web-based application built using Google Sheets, Google Apps Script, HTML/CSS/JS, and powered by Gemini AI prompts. It allows users to dynamically visualize retail sales data using an intuitive UI backed by charts and key metrics derived from a Google Sheet (`DASHBOARD` > `dataset` tab).

This project demonstrates how LLMs like Gemini can be used to rapidly prototype dashboards. In cases where Gemini's output is unreliable or inconsistent, the accompanying `index.html` and `code.gs` files can serve as fallback templates or fine-tuning datasets.

---

## 🚀 How It Works

- **Dataset Location:** Google Sheets spreadsheet named `DASHBOARD`, with a tab named `dataset`.
- **Backend Logic:** Implemented in `code.gs` (Apps Script).
- **Frontend Interface:** Built with `index.html` using ApexCharts and custom CSS.
- **Prompts:** Gemini AI Studio prompts were used to scaffold the dashboard structure and chart layout logic.

---

## 📊 Data Structure

The `dataset` tab must include:

| Column         | Description                  |
|----------------|------------------------------|
| `Date`         | Date of sale (DD-MM-YYYY)    |
| `Entity Name`  | Customer or Buyer            |
| `Product`      | Product sold                 |
| `Category`     | Product category             |
| `Location`     | Sales location               |
| `Sales`        | $ Sale amount                |
| `Cost`         | $ Cost of goods              |
| `Margin`       | $ Margin                     |
| `Expenses`     | $ Expenses incurred          |
| `Profit`       | $ Net profit                 |
| `Margin %`     | Margin % (calculated)        |
| `Profit %`     | Profit % (calculated)        |

---

## 🧠 Key Features

- **6 KPI Cards:**
  - Total Sales
  - Total Cost
  - Average Margin
  - Top Sales Location
  - Top Selling Product
  - Top Customer

- **8 Interactive Charts:**
  1. Sales Trend (spline area)
  2. Sales by Location (bar)
  3. Sales by Category (pie)
  4. Top 10 Customers (horizontal bar)
  5. Sales, Expenses, and Profit (100% stacked bar)
  6. Profit by Category (stacked column)
  7. Profit by Location (semi-donut)
  8. Sales and Profit Trend (stacked area)

---

## 🧩 Files Included

- `index.html` – Full front-end UI with ApexCharts
- `code.gs` – Backend Apps Script for data fetching
- `dataset.csv` – Sample input data
- `README.md` – Project documentation (you are here!)

---

## 🧪 How to Replicate

1. **Gemini Integration:**
   - Paste the provided prompts one by one in [Gemini AI Studio](https://aistudio.google.com/prompts/new_chat)
   - Provide the sample dataset
   - Review or debug the generated logic
   - Use this project’s files as reference or training inputs

2. **Google Sheet Setup:**
   - Create a sheet named `DASHBOARD`
   - Add a tab named `dataset` with the above structure
   - Paste the sample data or use your own

3. **Script Deployment:**
   - Open Apps Script tied to the sheet (Extensions -> Apps Script)
   - Add `code.gs` logic
   - Create a new HTML file and paste `index.html`
   - Deploy as a web app (set access to "Anyone" if you want to add collaborators)



---

## 🧠 Use Case

Ideal for rapid prototyping dashboards for small businesses, analysts, and students who want a lightweight BI dashboard powered by Google Sheets and visualized without any external BI software.

---

## 🙋 Support

If Gemini fails to generate a working version:
- Use `code.gs` and `index.html` from this repo.
- Modify chart logic or layout based on your dataset.
- Reach out to me on LinkedIn: [Rowena Sagaria](https://www.linkedin.com/in/rowenasagaria)

---

## 📌 License

Open-source project. Use freely, attribute where applicable.

---

