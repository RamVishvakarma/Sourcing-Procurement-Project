# Sourcing & Procurement Cycle – Excel Project

An end-to-end beginner Excel project demonstrating the **sourcing and procurement cycle** from supplier evaluation to purchase order delivery and performance reporting.

> **Note:** All suppliers, items, prices, and dates are synthetic and created for learning purposes.

## Project Objective

Build an Excel-based procurement model to:

- Evaluate and rate suppliers
- Review Purchase Requisitions (PRs)
- Compare supplier quotes and select the best-value supplier
- Track Purchase Orders (POs) against delivery dates
- Analyse spend, savings, and supplier performance

## Procurement Cycle

**Supplier Evaluation → PR Review → Quote Comparison → Purchase Order → Delivery & Reporting**

## Workbook Sheets

| Sheet | Purpose |
|---|---|
| Suppliers | Supplier evaluation using quality, delivery, and price |
| Requisitions | PR validation and next-action decisions |
| Quote_Comparison | RFQ quote evaluation and supplier ranking |
| Purchase_Orders | PO delivery and status tracking |
| Summary | Spend, savings, delivery performance, and dashboard |

### Supplier Scoring

Supplier performance is evaluated using **Quality (40%), Delivery (30%), and Price (30%)** to generate a weighted score and supplier rating.

![Supplier Scoring](images/score.png)

### Purchase Order Tracking

POs are tracked against promised and actual delivery dates to identify **On-Time, Late, Overdue, and Open** orders.

![Purchase Order Tracking](images/po.png)

## Key Results

- **15** suppliers evaluated; **3** preferred
- **15** PRs reviewed; **2** returned for missing specifications
- **6** PRs required an RFQ
- **12** POs raised worth **₹10,66,100**
- **70%** on-time delivery
- **1** overdue PO
- RFQ winner: **Sitwell Seating – ₹8,800/chair**
- **₹20,000 (2.2%)** saving against ₹9,00,000 budget

## Key Learning

The project demonstrates that supplier selection should consider **price, delivery, supplier quality, and specification compliance**, rather than choosing the cheapest quote alone.
