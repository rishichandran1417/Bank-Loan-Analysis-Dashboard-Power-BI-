# 🏦 Bank Loan Analysis Dashboard (Power BI)

An interactive Power BI dashboard providing a complete view of a **$435.8M loan portfolio**, including performance metrics, trends, and detailed loan-level insights.

---

## 📊 Dashboard Overview

### **1. Summary Page**
Gives a snapshot of the loan portfolio health and key performance indicators (KPIs):

- **Total Loan Applications:** 38.6K  
- **Total Funded Amount:** $435.8M  
- **Total Amount Received:** $473.1M  
- **Average Interest Rate:** 12.05%  

#### **Loan Quality**
- **Good Loans:** 86.2% (33.2K applications, $370.2M funded)  
- **Bad Loans:** 13.8% (5.3K applications, $65.5M funded)  
- **Definitions:**  
  - *Good Loans* = “Fully Paid” + “Current”  
  - *Bad Loans* = “Charged Off”

---

### **2. Overview Page**
Analyzes the total funded amount across multiple dimensions:

- **By Month:** Steady growth from $25M (Jan) to $54M (Dec)  
- **By State:** Highest in CA, TX, FL, NY  
- **By Term:**  
  - 36-month → $273.04M (62.66%)  
  - 60-month → $162.72M (37.34%)  
- **By Employment Length:** Dominated by “10+ years” ($116M)  
- **By Purpose:**  
  - *Debt Consolidation* → $232.46M  
  - *Credit Card* → $58.89M  
- **By Home Ownership:**  
  - *Mortgage* → $219.33M  
  - *Rent* → $185.77M  

---

### **3. Details Page**
Allows deep drill-down into individual loans.

- Fields include:  
  `id`, `purpose`, `home_ownership`, `grade`, `sub_grade`, `issue_date`, `funded_amount`, `interest_rate`, `installment`
- Filters for quick exploration by **State**, **Purpose**, or **Status**.

---

## 🧠 Key Insights
- 86.2% of loans are performing (“Good Loans”).  
- Debt consolidation is the dominant borrowing reason.  
- Most borrowers have 10+ years of employment.  
- 36-month loans form the majority of disbursements.  

---

## 🛠️ Tech Stack
- **Tool:** Power BI  
- **Data Source:** CSV dataset (loan portfolio data)  
- **Visuals Used:** Cards, Tables, Maps, Bar Charts, Pie Charts, Line Charts, Slicers  

---

## 📂 How to Use
1. Download the `.pbix` file.  
2. Open it in **Power BI Desktop**.  
3. Explore the interactive pages and filters.  

---

## 👤 Author
**Rishi Chandran**  
📍 Kerala, India  
📧 [rishichandran17@gmail.com](mailto:rishichandran17@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/rishi-chandran-525970262/)  
💻 [GitHub](https://github.com/rishichandran1417)

---

⭐ *If you find this dashboard useful, consider starring the repository!*
