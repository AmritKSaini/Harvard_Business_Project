#  Merrimack Tractors & Mowers — LIFO vs FIFO Case Study

> **Course:** Cost Management and Accounting | BBA (Hons), Semester 4  
> **Institution:** Netaji Subhas University of Technology (NSUT)  
> **Submission Date:** April 16, 2025

---

##  Objective

To analyze the suitability of **LIFO (Last-In, First-Out)** or **FIFO (First-In, First-Out)** as an inventory accounting method in view of the present economic health of **Merrimack Tractors and Mowers Inc.**

---

##  About the Case

**Merrimack Tractors and Mowers Inc.** is a regional manufacturer and seller of large commercial grass mowers, founded after World War II in Nashua, New Hampshire. Incorporated in 1980, the company trades on NASDAQ with ~4,000 shareholders, with 25% equity retained by the founding Martino family.

In **2008**, rising manufacturing costs outpaced competitors', threatening earnings growth. President **Ricardo "Rick" Martino** and controller **James Colburn** explored whether switching from LIFO to FIFO could help maintain reported earnings.

> **Original Case:** *Merrimack Tractors and Mowers: LIFO or FIFO? (Brief Case)*  
> By: William J. Bruns Jr., Sharon Bruns & Susan S. Harmeling — Harvard Business School

---

##  Repository Structure
```
merrimack-lifo-fifo-case/
│
├── README.md                              # Project overview (this file)
├── presentation/
│   └── Case_20250516_230350_0000.pdf      # Full case study presentation
├── analysis/
│   ├── Q1_LIFO_ProForma_2008.md
│   ├── Q2_LIFO_Variable_Sales.md
│   ├── Q3_FIFO_Adoption_Impact.md
│   ├── Q4_Stable_Falling_Costs.md
│   ├── Q5_Financial_Reporting.md
│   ├── Q6_Ethics_EarningsManagement.md
│   └── Q7_Draft_Note_FIFO_Switch.md
└── data/
    └── inventory_tables.md
```

---

##  Questions & Analysis

### Q1 — Pro-Forma Income Statement (LIFO, Uniform Sales)

10,000 units/quarter × $2,000/unit. COGS under LIFO uses the most recently purchased (most expensive) inventory first.

**COGS:** `(10K×$1,400) + (10K×$1,500) + (10K×$1,600) + (10K×$1,700) = $62,000,000`

| Metric | 2007 ($'000) | 2008 ($'000) |
|--------|:-----------:|:-----------:|
| Sales | 67,000 | 80,000 |
| COGS | 46,000 | 62,000 |
| Gross Margin | 21,000 | 18,000 |
| Selling & Admin | 10,000 | 10,000 |
| Income before Taxes | 11,000 | 8,000 |
| Income Taxes (35%) | 3,850 | 2,800 |
| **Net Income** | **7,150** | **5,200** |

---

### Q2 — Variable Sales Pattern (10K, 5K, 20K, 5K units)

Uneven quarterly sales under LIFO cause high-volume quarters to dip into older, cheaper inventory layers.

**COGS:** `(10K×$1,400) + (5K×$1,500) + {(10K×$1,600)+(5K×$1,500)+(5K×$900)} + (5K×$1,700) = $58,000,000`

| Metric | Uniform Sales ($'000) | Variable Sales ($'000) |
|--------|:--------------------:|:---------------------:|
| COGS | 62,000 | 58,000 |
| **Net Income** | 5,200 | **7,800** |

> **Key Insight:** Sales timing affects COGS under LIFO even when total annual units sold are identical.

---

### Q3 — FIFO Adoption Impact (Jan 1, 2008)

**LIFO vs FIFO Income Statement Comparison:**

| Metric | LIFO ($'000) | FIFO ($'000) |
|--------|:-----------:|:-----------:|
| Sales | 80,000 | 67,000 |
| COGS | 62,000 | 56,000 |
| Gross Profit | 18,000 | 11,000 |
| Income before Taxes | 8,000 | 1,000 |
| Income Taxes (35%) | 2,800 | 350 |
| **Net Income** | **5,200** | **650** |

**Balance Sheet (FIFO transition):**
- Inventory increases to **$25,000,000** (FIFO ending value)
- LIFO Reserve of **$5,500,000** reclassified to retained earnings
- Net Income added to equity: **$650,000**

> FIFO shows lower COGS, but the LIFO reserve adjustment significantly reduces net income in the transition year.

---

### Q4 — Stable or Falling Costs Scenario

| Cost Environment | LIFO | FIFO |
|-----------------|------|------|
| **Rising** (Merrimack 2008) | High COGS, Low Tax | Low COGS, High Tax |
| **Stable** | ≈ No difference | ≈ No difference |
| **Falling** (e.g., electronics) | Low COGS, High Income | High COGS, Low Income |

> In deflationary industries, FIFO becomes the *costlier* method — reversing the usual strategic preference.

---

### Q5 — Purposes of Financial Reporting

1. **Transparency & Accuracy** — reflects true financial position
2. **Investor Decision-Making** — supports risk and return assessment
3. **Regulatory Compliance** — adherence to GAAP/IFRS
4. **Management Decision-Making** — budgeting, strategy, operations
5. **Credibility & Trust** — for shareholders, lenders, and regulators

---

### Q6 — Ethical Analysis of Earnings Management

> Is James Colburn suggesting earnings management over sound business management?

| Concern | Implication |
|---------|------------|
| Trust & Transparency | Misleads investors relying on reported earnings |
| Short-term vs Long-term | One-time accounting boost is unsustainable |
| Regulatory Risk | Could attract SEC scrutiny if intent to mislead is proven |

**Conclusion:** While the switch is *legally permissible*, changing accounting policy primarily to inflate earnings — rather than for sound reporting reasons — is **ethically problematic**. The recommended path is operational improvement and honest stakeholder communication.

---

### Q7 — Draft Note to Financial Statements

> **Merrimack Tractors and Mowers Inc.**  
> **Note: Change in Inventory Accounting Policy** | *Effective January 1, 2008*
>
> The Company has changed its inventory valuation method from **LIFO** to **FIFO**. FIFO more accurately reflects current inventory costs on the Balance Sheet and aligns with industry best practices. Under rising input costs, it provides greater financial transparency.
>
> **Financial Impact:** Higher ending inventory, lower COGS, higher reported net income, and higher income tax liabilities. The LIFO reserve has been reclassified to retained earnings. Prior period statements have been restated for comparability.

---

##  Key Concepts

| Term | Definition |
|------|-----------|
| **LIFO** | Newest inventory sold first; reduces taxable income in inflationary periods |
| **FIFO** | Oldest inventory sold first; increases reported income during inflation |
| **LIFO Reserve** | Difference between LIFO and FIFO ending inventory values |
| **COGS** | Cost of Goods Sold — direct cost of units sold |
| **Pro-Forma Statement** | Projected financial statement based on assumptions |
| **Earnings Management** | Using accounting choices to influence reported results |

---

##  References

- Bruns, W. J. Jr., Bruns, S., & Harmeling, S. S. — *Merrimack Tractors and Mowers: LIFO or FIFO? (Brief Case)*, Harvard Business School
- [Indeed — What is Financial Reporting?](https://www.indeed.com/career-advice/career-development/what-is-financial-reporting)
- [HBS Faculty Profile](https://www.hbs.edu/faculty/Pages/item.aspx?num=41746)

---

## 📄 License

This repository is submitted for **academic purposes only**. Not intended for commercial use.

---
