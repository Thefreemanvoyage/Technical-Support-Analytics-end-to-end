# Technical Support Analytics — End to End

An end-to-end data project analysing **2,330 support tickets** to answer one question:
**how well is the support centre hitting its SLA targets, and what's causing the misses?**

Built across the full analytics workflow: **Excel → Python → SQL → Power BI.**

---

## What I found

- 📈 **The centre answers fast but closes slow.** 87% of tickets meet the first-response
  target, but only **81% are resolved on time** — about **1 in 5 tickets breaches** the
  resolution SLA.
- 🔍 **The misses aren't random.** They cluster in **Pricing & licensing tickets**,
  **chat-channel tickets**, and **medium-priority work** — while urgent (high-priority)
  tickets are actually handled best.
- 🗓️ **Demand peaks mid-week and mid-afternoon** (busiest on Wednesdays, around 3 PM) —
  useful for staffing.

## What I recommended

- Protect the **medium-priority queue**, which slips the most.
- Review how **chat tickets** are handled — they breach far more than email.
- Add resolution capacity for **Pricing & licensing**, the biggest source of misses.

---

## Tools used

**Python** (data cleaning) **PostgreSQL** (analysis) **Power BI** (dashboard) **Excel**

## What's in this repo

| File | What it is |
|------|------------|
| `Raw.Technical Support Dataset.xlsx` | The original raw data |
| `Pycleanedtickets-checkpoint.ipynb` | Python cleaning notebook |
| `SQLqueries` | SQL analysis queries |
| `Technical Support Dashboard KPI Report.pbix` | Power BI dashboard |

---

**Rahul B**
📧 rahulforreal4747@gmail.com
