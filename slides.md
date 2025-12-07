# Quarterly Earnings Report  
### Technical Consultant Presentation  
**Email:** 23f2003825@ds.study.iitm.ac.in  

---

## Key Highlights

<p class="fragment">Revenue growth of <b>12% YoY</b></p>
<p class="fragment">Net profit increased by <b>8%</b></p>
<p class="fragment">Operating margin improved by <b>2.1%</b></p>

Note:
These are highlights for Q4.

---

## Financial Formula (Math)

The Net Interest Margin is:

$$
NIM = \frac{Interest\ Income - Interest\ Expense}{Average\ Earning\ Assets}
$$

Note:
Explain calculation impact.

---

## Example Code

```python
def calculate_growth(prev, current):
    return ((current - prev) / prev) * 100

print("Growth:", calculate_growth(120, 135))
