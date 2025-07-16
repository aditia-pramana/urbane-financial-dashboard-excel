
# PT Urbane Stitch Indonesia  Accounting Dashboard (2025–2026)

This Excelbased interactive dashboard was developed for PT Urbane Stitch Indonesia, a modern garment manufacturing company, to support its endtoend accounting workflow from transaction entry to financial reporting for the fiscal years 2025 and 2026.



## 📌 Project Objectives

The primary goal of this project is to design an automated and userfriendly accounting system in Excel, enabling accurate data recording, realtime calculations, and dynamic financial insights, without the need for external accounting software.



## 🧾 Key Features

### 📘 Accounting Process
 Chart of Accounts (COA)  
 General Journal with autopopulating fields
 General Ledger by account
 Trial Balance linked dynamically to ledger
 Financial Statements for two years:
   Income Statement
   Statement of Changes in Equity
   Balance Sheet
   Cash Flow Statement

### 📊 Additional Reports & Schedules
 Aging Schedule (Receivables & Payables)
 Labor Cost Calculation
 Bond Valuation
 Raw Material Inventory Table
 Interactive transaction links to supporting documents or specific sheets/pages



## 🧠 Excel Functions & Formulas Used

This project leverages advanced Excel features including:

```excel
=SUMIF()          ' For aggregation by criteria (e.g., aging schedule)
=SUBTOTAL()       ' For dynamic filtering and summarizing
=PV()             ' Present value of bonds
=PMT()            ' Monthly payment calculation
=GROUPBY() + HSTACK() + CHOOSECOLS()  ' For advanced data transformation
=XLOOKUP()        ' Dynamic account lookup from COA
=IFS() + LEFT()   ' For automatic debit/credit balances in trial balance
=IFERROR()        ' Error handling for lookups and formulas
````

Hyperlinks are embedded to allow:

 Navigation between sheets (internal linking)
 Access to online resources (external linking)
 Reference to transaction evidence (document linking)



## 📂 File Structure

 `AccountingDashboard_UrbaneStitch.xlsx`: The main Excel file
 Linked tabs for:

   Input (Transactions, COA)
   Processing (Journal, Ledger, Trial Balance)
   Output (Reports, Schedules)



## 🧵 About the Company

PT Urbane Stitch Indonesia is a fashionforward garment manufacturing company specializing in elegant and modern apparel using materials like cotton, linen, rayon, silk, and denim. This dashboard was tailored to support the company’s financial documentation and analysis needs as it grows.



## 🙌 Notes

This project was created manually using only native Excel features, formulas, and dynamic named ranges. It is designed for small to mediumsized enterprises seeking a scalable, transparent, and auditable financial system.



## 🔗 Credits

This dashboard and its structure were designed and developed by \[Aditia Pramana] as part of a financial systems improvement initiative.

For inquiries or collaboration, feel free to reach out.



