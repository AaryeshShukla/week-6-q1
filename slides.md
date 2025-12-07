<!-- Title slide -->
# Q4 2025 — Quarterly Earnings Report
**Acme Bank Ltd.**  
Presenter: Technical Consulting Team  
---

## Highlights
- Revenue grew **12% YoY**. <!-- fragment -->
- Net interest margin improved by **0.35%**. <!-- fragment -->
- Operating costs controlled at **-3% QoQ**. <!-- fragment -->

Note:
Speaker: Start with a 30 second summary. Emphasize YoY revenue growth and NIM improvement.

---

## Financial Formula (math)
We forecast net income with:
$$ \text{Net Income} = (\text{Net Interest Income} + \text{Other Income}) - \text{Expenses} - \text{Provisions} $$

Note:
Explain that provisions are conservative and include stress scenarios.

---

## Example: Simple P&L snippet (code)
```sql
-- SQL sample to compute net interest income (example)
SELECT
  SUM(interest_received) - SUM(interest_paid) AS net_interest_income
FROM loan_interest
WHERE period >= '2025-10-01' AND period <= '2025-12-31';
