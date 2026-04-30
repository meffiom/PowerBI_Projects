# SnowRoute — Supply Chain Intelligence Platform

> End-to-end Snowflake data platform for supply chain analytics.
> Built to answer why 57% of all orders arrive late and which 
> shipping routes carry the highest operational risk.

---

## Project Overview

I built this project to take a raw 180,000-row supply chain 
CSV file and turn it into something a business stakeholder 
can sit in front of and make decisions from. The platform 
covers the full stack — from raw ingestion through to a 
four-page Power BI dashboard.

---

## Key Findings

| Metric | Value | Status |
|--------|-------|--------|
| Total Revenue | $36.78M | ✅ |
| Total Orders | 66,000 | ✅ |
| Late Delivery Rate | 57.28% | 🔴 |
| On-Time Rate | 42.72% | 🔴 |
| Avg Profit Margin | 10.83% | 🟡 |
| Unique Customers | 21K | ✅ |
| Avg Risk Score | 56.10 / 100 | 🔴 |
| Minor Delay Revenue | $19.6M | 🔴 |
| First Class Late Rate | 100% | 🔴 |

**Critical finding:** First Class shipping — the premium 
delivery tier — has a 100% late rate across all 27,814 
orders. Not a single First Class shipment arrived on time.

**Revenue finding:** Minor Delay orders (1–3 days late) 
account for $19.6M in revenue — more than On Time orders 
at $15.8M. The business is processing more high-value 
orders through the delayed channel than the on-time channel.

---

## Dataset

DataCo Smart Supply Chain for Big Data Analysis
kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis
180,519 rows · Orders, shipments, customers, products,
delivery status · Free to download

## Dashboard
<img width="1170" height="642" alt="Screenshot 2026-04-23 021715" src="https://github.com/user-attachments/assets/2ba63a6a-e59a-4afe-8e22-4974a8d82dec" />

<img width="1135" height="640" alt="Screenshot 2026-04-23 021742" src="https://github.com/user-attachments/assets/c325a0d3-978c-48c8-a30b-5eb3956d3105" />

<img width="1125" height="634" alt="Screenshot 2026-04-23 021841" src="https://github.com/user-attachments/assets/f91dfe02-9ca6-4eb7-8b84-9a2c0a975faa" />

<img width="1119" height="628" alt="Screenshot 2026-04-23 021858" src="https://github.com/user-attachments/assets/0c75ed51-5cc6-4ccc-9590-e2153f51efaa" />

