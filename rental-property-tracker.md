# Rental Property Tracker - Template
## Use this for tracking 3 rental properties

---

## INSTRUCTIONS
1. Copy each tab/sheet into Google Sheets or Excel
2. Fill in your property details in the yellow cells
3. Formulas will calculate automatically
4. Use one row per property

---

## TAB 1: PROPERTY OVERVIEW

| Property Name | Address | Purchase Price | Down Payment | Loan Amount | Interest Rate | Loan Term (years) | Monthly Rent | Vacancy Rate (%) |
|---------------|---------|----------------|--------------|-------------|---------------|-------------------|--------------|-------------------|
| Property 1    |         |                |              |             |               |                   |              |                   |
| Property 2    |         |                |              |             |               |                   |              |                   |
| Property 3    |         |                |              |             |               |                   |              |                   |

---

## TAB 2: CLOSING COSTS

| Category | Property 1 | Property 2 | Property 3 |
|----------|------------|------------|------------|
| **PURCHASE COSTS** | | | |
| Purchase Price | | | |
| Inspection Fee | | | |
| Appraisal Fee | | | |
| Title Insurance | | | |
| Closing/Attorney Fees | | | |
| Loan Origination Fee | | | |
| Points (Loan Discount) | | | |
| Recording Fees | | | |
| Survey Fee | | | |
| **RENOVATION COSTS** | | | |
| Repairs | | | |
| Appliances | | | |
| Paint/Flooring | | | |
| HVAC/Plumbing | | | |
| **CASH TO CLOSE** | =SUM(B4:B14) | =SUM(C4:C14) | =SUM(D4:D14) |

**Formula Note:** The "Cash to Close" row sums up all costs for each property.

---

## TAB 3: MONTHLY EXPENSES

| Expense Category | Property 1 | Property 2 | Property 3 |
|------------------|------------|------------|------------|
| **FIXED COSTS** | | | |
| Mortgage (P&I) | | | |
| Property Taxes | | | |
| Insurance | | | |
| HOA Fees | | | |
| **VARIABLE COSTS** | | | |
| Property Management (%) | | | |
| Repairs/Maintenance | | | |
| CapEx (Reserve 5-10%) | | | |
| Utilities (if paid) | | | |
| Lawn/Snow Removal | | | |
| **MONTHLY TOTAL** | =SUM(B4:B12) | =SUM(C4:C12) | =SUM(D4:D12) |

---

## TAB 4: ANNUAL EXPENSES

| Annual Expense | Property 1 | Property 2 | Property 3 |
|----------------|------------|------------|------------|
| Property Taxes (x12) | | | |
| Insurance (x12) | | | |
| HOA (x12) | | | |
| Maintenance Reserve | | | |
| CapEx Reserve | | | |
| Property Management | | | |
| **ANNUAL TOTAL** | =SUM(B4:B10) | =SUM(C4:C10) | =SUM(D4:D10) |

---

## TAB 5: CASH FLOW ANALYSIS

| Metric | Property 1 | Property 2 | Property 3 |
|--------|------------|------------|------------|
| **INCOME** | | | |
| Monthly Rent | | | |
| Other Income (laundry/parking) | | | |
| **EFFECTIVE GROSS** | =B4+B5 | =C4+C5 | =D4+D5 |
| Vacancy Loss (5%) | =B6*0.05 | =C6*0.05 | =D6*0.05 |
| **ADJUSTED GROSS** | =B6-B7 | =C6-C7 | =D6-D7 |
| **EXPENSES** | | | |
| Monthly Expenses | | | |
| **NOI (Net Operating Income)** | =B8-B12 | =C8-C12 | =D8-D12 |
| **ANNUAL NOI** | =B13*12 | =C13*12 | =D13*12 |
| **DEBT SERVICE** | | | |
| Annual Debt Service | | | |
| **CASH FLOW** | =B14-B17 | =C14-C17 | =D14-D17 |
| **MONTHLY CASH FLOW** | =B18/12 | =C18/12 | =D18/12 |

---

## TAB 6: RETURNS & METRICS

| Metric | Property 1 | Property 2 | Property 3 |
|--------|------------|------------|------------|
| **INVESTMENT** | | | |
| Total Cash Invested | | | |
| **RETURNS** | | | |
| Annual Cash Flow | | | |
| Cash-on-Cash Return (%) | =B4/B5*100 | =C4/C5*100 | =D4/D5*100 |
| Cap Rate (%) | =B6/B5*100 | =C6/C5*100 | =D6/D5*100 |
| GRM (Gross Rent Multiplier) | =B5/(B7*12) | =C5/(C7*12) | =D5/(D7*12) |
| 1% Rule | =B7/B5*100 | =C7/C5*100 | =D7/D5*100 |

---

## FORMULAS EXPLAINED

### Monthly Cash Flow
```
Net Operating Income - Debt Service = Cash Flow
```

### Cash-on-Cash Return
```
(Annual Cash Flow ÷ Total Cash Invested) × 100
```

### Cap Rate
```
(NOI ÷ Property Value) × 100
```

### 1% Rule
```
(Monthly Rent ÷ Purchase Price) × 100
```
*Target: 1% or higher*

---

## QUICK REFERENCE - WHAT TO LOOK FOR

| Metric | Good | Warning | Bad |
|--------|------|---------|-----|
| Cash-on-Cash Return | >8% | 5-8% | <5% |
| Cap Rate | >6% | 4-6% | <4% |
| 1% Rule | >1% | 0.5-1% | <0.5% |
| Vacancy Rate | <5% | 5-10% | >10% |
| Debt Service Ratio | <75% income | 75-85% | >85% |

---

*Created by Carl 🦦*
*For Renee's Rental Properties*