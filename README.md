# Rental Property Financial Dashboard

📊 **A Power BI + PostgreSQL dashboard for long-term rental performance analysis**

Walkthru of project: https://youtu.be/Tj4k1GtpL7Y

---

## 🔍 Overview

This interactive dashboard tracks 15+ years of financial data for a single-family rental property, providing high-level KPIs and granular insights for investors, landlords, or analysts.

- Built in **Power BI** and powered by a **PostgreSQL backend**
- Fully mock dataset with real-world lease cycles, payment behavior, and expenses
- Clean dark-themed layout inspired by Spotify and Pixar-style dashboards

---

## 💡 Key Features

- **KPI Cards**  
  ![Total Rental Income](Screenshots/Total%20Rental%20Income.PNG)  
  ![Total Expenses](Screenshots/Total%20Expenses.PNG)  
  ![Net Operating Income](Screenshots/Net%20Operating%20Income.PNG)  
  ![Late Payments](Screenshots/Late%20Payments.PNG)

- **Visuals**
  - 📈 Monthly Income & NOI (Line Chart)  
    ![Monthly NOI](Screenshots/Monthly%20NOI.PNG)  
    ![Monthly Rental Income](Screenshots/Monthly%20Rental%20Income.PNG)
  - 🍩 Rent Collected by Tenant  
    ![Rent Collected by Tenant](Screenshots/Rent%20Collected%20per%20Tenant.PNG)
  - 🧾 Top Expense Categories  
    ![Top 3 Expense Categories](Screenshots/Top%203%20Expense%20Categories.PNG)
  - 📊 Additional Insights  
    ![Average Rent per Tenant](Screenshots/Average%20Rent%20per%20Tenant.PNG)  
    ![Invoices Paid On Time](Screenshots/Invoices%20Paid%20On%20Time.PNG)  
    ![Total Invoices vs Payments](Screenshots/Total%20Invoices%20vs%20Payments.PNG)  
    ![Monthly Expenses](Screenshots/Monthly%20Expenses.PNG)  
    ![Yearly Summary](Screenshots/Yearly%20Summary.PNG)

---

## 🧱 Dataset Schema

| Table | Description |
|-------|-------------|
| `tenants` | Tenant ID, Name, Lease Period, Status |
| `invoices` | Monthly rent invoices issued per tenant |
| `payments` | Payment records tied to invoices |
| `expenses` | Property expenses with category breakdowns |

---

## 🛠 Technologies Used

- **PostgreSQL 17**
- **Power BI Desktop**
- DAX Measures + Calculated Columns
- SQL Table Relationships + Sample Data

---

## 📁 Files Included

- `Dashboard/Rental_Property_Financial_Dashboard.pbix` – Power BI file
- `SQL/rental_financial_analytics_schema.sql` – Create & populate tables
- `README.md` – Project overview and instructions
- `Screenshots/` – Full output preview images

---

## 🧠 Skills Demonstrated

- Financial KPI development
- Relational SQL modeling
- Power BI dashboard design
- DAX performance calculations
- Real estate rental analytics

---

## 📈 Sample Output

![Main Dashboard Preview](Screenshots/Rental_Property_Financial_Dashboard.PNG)

---

## 📎 License

MIT License — feel free to adapt and build for your own portfolio.
