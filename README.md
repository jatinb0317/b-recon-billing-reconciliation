# B-Recon — Billing & Payment Reconciliation

A lightweight web-based billing and payment reconciliation system designed to simplify invoice tracking, payment allocation, outstanding management, and financial reconciliation.

## 🚀 Live Demo

**[Open B-Recon Live Demo](https://jatinb0317.github.io/b-recon-billing-reconciliation/)**

> This is a demonstration/prototype version built for showcasing the product concept and workflow.

---

## 📌 Problem

Managing invoice payments manually can become difficult when payments need to be reconciled across multiple invoices and different payment adjustments such as TDS, GST holds, credit notes, penalties, and short payments.

B-Recon was designed to provide a centralized workflow for tracking invoices, recording payments, allocating received amounts, and understanding outstanding balances.

---

## ✨ Key Features

- 📊 Dashboard for reconciliation overview
- 🧾 Invoice management
- 💰 Payment tracking
- 🔗 Payment-to-invoice allocation
- 📥 Excel / CSV invoice import
- 📥 Excel / CSV payment import
- 🔄 Existing invoice updates without creating unnecessary duplicates
- 🔍 Payment reference based reconciliation
- 🧮 TDS tracking
- 🏦 GST Hold & GST Release tracking
- 📝 Credit Note tracking
- ⚠️ Penalty and Short Payment classification
- 📅 Invoice and payment history
- 📈 Outstanding and reconciliation reporting
- 💾 Automatic local data saving
- 🔐 Local recovery / backup support

---

## 🔄 Reconciliation Workflow

The basic workflow is:

```text
Invoice Data
     ↓
Payment Data
     ↓
Payment Reference Matching
     ↓
Invoice Allocation
     ↓
TDS / GST Hold / Other Adjustments
     ↓
Outstanding Calculation
     ↓
Reconciliation & Reporting
```

## 📥 Excel Import

B-Recon supports importing invoice and payment information from Excel/CSV files.

### Invoice Import

Invoice data can include:

- Invoice Number
- Client
- State
- Invoice Date
- Billing Month
- Basic Value
- GST
- Total
- Credit Note Amount
- Notes

Existing invoice numbers can be updated instead of creating unnecessary duplicate invoice records.

### Payment Import

Payment data can include:

- Payment Reference
- Payment Date
- Payment Amount
- Invoice Number
- TDS
- GST Hold
- GST Release
- Penalty
- Short Payment

---
  
## 📸 Screenshots

### Dashboard — Overview
![Dashboard Overview](screenshots/Dashboard_1.png)

### Dashboard — Detailed View
![Dashboard Detailed View](screenshots/Dashboard_2.png)

### Invoice Management
![Invoice Management](screenshots/Invoice_1.png)

### Invoice Details
![Invoice Details](screenshots/Invoice_2.png)

### Payment Management
![Payment Management](screenshots/Payment_1.png)

### Payment Allocation
![Payment Allocation](screenshots/Allocate_1.png)

### Allocation Details
![Allocation Details](screenshots/Allocate_2.png)

### Reports
![Reports](screenshots/Report_1.png)

### Detailed Report
![Detailed Report](screenshots/Report_2.png)

### Excel Import
![Excel Import](screenshots/Excel_Import.png)
