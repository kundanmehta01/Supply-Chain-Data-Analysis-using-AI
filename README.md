# 🚛 Supply Chain Analytics Project using AI (n8n + Supabase + Quadratic)

This project explores key performance metrics of a supply chain using AI tools and automation platforms. The goal is to analyze delivery issues, revenue loss, and supply chain bottlenecks — while using **low-code tools** to automate and streamline the analysis.

---

## 📌 Business Questions Addressed

- 📉 What is the **revenue loss** due to undelivered orders?
- 🧍 Which **customers have the highest OTIF (On-Time, In-Full) issues**?
- 📦 Which **product categories exhibit low 'In Full' delivery rates**?
- ⏱️ What is the **average delay** in late deliveries?
- 🚧 What do consistent delivery failures indicate about **supply chain bottlenecks**?

---

## ⚙️ Tools & Technologies Used

| Tool        | Purpose                                                                 |
|-------------|-------------------------------------------------------------------------|
| **n8n**     | Automated ETL workflows (extract-transform-load from files to database) |
| **Supabase**| Cloud-hosted backend and database (PostgreSQL)                          |
| **PostgreSQL** | SQL-based analytics and metric calculations                           |
| **Quadratic**| AI-powered spreadsheet interface for analysis and visualization         |

---

## 📂 File Included

- `supply_chain_analysis.grid`: Quadratic project file containing the analysis, KPIs, visualizations, and SQL queries.

---

## 🧠 How to Open `.grid` File

1. Go to [https://quadratic.to](https://quadratic.to)
2. Sign in or create a free account
3. Upload the `.grid` file using the **Upload** button
4. Explore the analysis with full interactivity — modify SQL, use AI to ask questions, or create new visuals

---

## ✅ Steps Followed in This Project

1. **Data Collection & Automation**
   - Used **n8n** to automate loading of order, product, and customer data from local/online sources
   - Cleaned and transformed the data before inserting into the backend

2. **Database Setup with Supabase**
   - Structured datasets into relational tables: `fact_order_line`, `dim_products`, `dim_customers`
   - Managed storage and access through Supabase’s built-in PostgreSQL

3. **SQL-Based Analysis**
   - Wrote SQL queries to compute:
     - Total order lines
     - On-Time/In-Full (OTIF) metrics
     - Average delay time
     - Revenue loss from undelivered orders
     - Performance by product category and customer

4. **Visualization & Insights with Quadratic**
   - Uploaded data into Quadratic
   - Used AI to help generate visualizations and answer business questions interactively

---

## 🙏 Acknowledgements

Special thanks to:

- **Dhaval Patel** and **Hemanand** — for their valuable domain knowledge and mentorship  
- **Codebasics** — for the exceptional learning platform and real-world project inspiration  
- The Quadratic and n8n communities for enabling accessible AI-driven analytics

---

## 🔗 Connect With Me

If you found this useful or are working on similar projects, feel free to connect with me on LinkedIn ([https://linkedin.com/](https://www.linkedin.com/in/kundan-k-670b7b203/)) or fork this repo and contribute.

---

## 📎 License
This project is for learning and demonstration purposes only.

