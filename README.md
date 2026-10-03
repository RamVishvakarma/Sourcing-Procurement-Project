Sourcing & Procurement Cycle - Beginner Excel Project

A small, end-to-end Excel project that walks through the procurement cycle: find suppliers → check requisitions → compare quotes → raise POs → track delivery → report results.

All suppliers, items, prices and dates are synthetic (made up for learning). No real companies are represented.

File: Beginner_Sourcing_Procurement_Project.xlsx

1. Project Goal

Show a clear understanding of sourcing and procurement by building a working model that:

Evaluates and rates suppliers
Checks purchase requisitions (PRs) and decides the next action
Compares supplier quotes and picks the best-value supplier (not just the cheapest)
Tracks purchase orders (POs) against promised delivery dates
Summarises spend, savings and supplier performance
2. Key Terms
Term	Meaning
Sourcing	Finding, evaluating and selecting suppliers
Procurement	The full buying cycle: need → supplier → quote → PO → delivery → payment
PR (Purchase Requisition)	An internal request to buy something
RFQ (Request for Quotation)	Asking several suppliers to quote for the same requirement
PO (Purchase Order)	The formal order sent to the chosen supplier
Spec	The technical/quality details of what is being bought
3. Workbook Structure
#	Sheet	Purpose
0	Overview	The 5 steps of the cycle and the Excel skill used in each
1	Suppliers	15 suppliers rated 1-10 on quality, delivery and price → weighted score → rating
2	Requisitions	15 PRs checked for spec and value → next action
3	Quote_Comparison	One RFQ (100 ergonomic chairs) with 5 quotes scored and ranked
4	Purchase_Orders	12 POs with promised vs actual delivery and status
5	Summary	Spend, savings, on-time delivery and a chart
4. Business Rules Used

Supplier rating (Suppliers sheet)

Weighted score = (Quality × 40% + Delivery × 30% + Price × 30%) × 10, so the score is out of 100
80 and above = Preferred | 65 to 79 = Approved | below 65 = Not approved

Requisition check (Requisitions sheet)

Spec missing → Send back - spec missing
Value at or above ₹1,00,000 → Needs RFQ (3 quotes)
Value below ₹1,00,000 → Raise PO directly

Quote evaluation (Quote_Comparison sheet)

Suppliers that do not meet the spec are excluded (score = 0)
Price score = lowest compliant price ÷ supplier's price × 100
Delivery score = shortest compliant delivery days ÷ supplier's days × 100
Overall score = Price 50% + Delivery 20% + Supplier score 30%
Rank 1 = recommended supplier

PO status (Purchase_Orders sheet)

On time: delivered on or before the promised date
Late: delivered after the promised date
Overdue: not delivered and the promised date has passed
Open: not delivered yet, but not yet due
5. Results (with the data provided)
Metric	Result
Suppliers evaluated / Preferred	15 / 3
PRs received	15
PRs sent back (spec missing)	2
PRs needing an RFQ	6
POs raised	12
Total PO value	₹10,66,100
On-time delivery	70%
Overdue POs	1
RFQ winner	Sitwell Seating at ₹8,800 per chair
Saving vs ₹9,00,000 budget	₹20,000 (2.2%)

Key takeaway: the cheapest bid (₹7,650) failed the spec and was excluded. The winner was not the lowest compliant price (₹7,900) either. Sitwell Seating won on faster delivery (14 days) and a stronger supplier rating, and still came in under budget.
