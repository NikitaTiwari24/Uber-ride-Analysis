# Uber-ride-Analysis
Data cleaning, EDA , Power BI dashboard analyzing 150K ride bookings — identifying ₹28.97M in cancellation-driven revenue loss"

Problem Statement

Only ~62% of ride bookings on the platform were completing successfully. The remaining ~38% — cancellations, driver-shortage situations, and incomplete trips — represented a significant, unquantified loss in potential revenue and operational efficiency. There was no clear picture of:

How much revenue this was actually costing the platform
Whether the problem was driven by customers, drivers, or supply shortages
Whether specific locations, times, or vehicle types were disproportionately affected

This project analyzes the dataset to answer these questions with concrete numbers, and packages the findings into an interactive dashboard.


Key Findings

Overall completion rate: 62.00% — consistent across vehicle types (61–63%) and hours (61–64%), but varies significantly by location (55–66%)
Driver-initiated cancellations (27,000) are 2.5x more frequent than customer cancellations (10,500) — the single largest controllable driver of ride failure

Estimated lost revenue: ₹28.97M, or 38% of total potential revenue — of this, driver cancellations alone account for ~₹13.7M
~2/3 of "customer" cancellations are actually driver-caused (driver not moving toward pickup, driver asked to cancel) — not pure customer preference

"No Driver Found" and cancellation rates vary meaningfully by pickup location (4.7%–10.3% and up to ~30% respectively) but not by hour or vehicle type — indicating a localized supply issue, not a timing or fleet-type issue

Ratings show no meaningful correlation with distance, fare, wait time, or vehicle type (all |r| < 0.01) — a data-quality observation suggesting ratings may be randomly generated in this dataset rather than behavior-driven
Booking demand is flat across weekdays/weekends (410 vs 413 bookings/day) but shows a clear two-peak pattern by hour of day (~10 AM and ~8 PM), consistent with commute-driven usage


