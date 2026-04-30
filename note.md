## Methodology

- Loaded the `NYC.csv` dataset using pandas (**1,458,644 rows × 11 columns**)
- Inspected dataset structure and confirmed there were **no missing values**
- Converted `pickup_datetime` to datetime format for time-based analysis
- Extracted key temporal features including **hour of day, weekday, and month**
- Engineered a new feature: `trip_duration_minutes = trip_duration / 60`
- Applied outlier filtering by removing trips shorter than 1 minute and longer than 120 minutes to ensure realistic trip analysis
- Performed aggregations using `groupby()` to analyze:
  - Hourly demand patterns
  - Weekly demand distribution
  - Monthly trends
  - Average trip duration behavior
- Built visualizations using matplotlib and seaborn:
  - Line chart for hourly demand
  - Bar charts for weekly and monthly trends
  - Histogram for trip duration distribution
  - Heatmap for demand intensity across hours and weekdays
- Conducted vendor-level comparison based on average trip duration

---

## Business Insights

**Peak Demand Concentration:**  
Taxi demand is heavily concentrated during evening hours, aligning with post-work commuting patterns.  
→ Fleet availability should be increased during these periods to meet demand efficiently and reduce passenger wait times.

---

**Low Utilization Periods:**  
Early morning hours show significantly lower activity compared to the rest of the day.  
→ Fleet size can be reduced during these periods to optimize operational costs and minimize idle time.

---

**End-of-Week Demand Surge:**  
Demand tends to increase toward the end of the week, with noticeable peaks on later weekdays.  
→ Driver scheduling and incentive strategies should be aligned with these demand patterns to maximize efficiency.

---

**Consistent Short-Distance Trips:**  
Trip durations are generally short and stable, indicating that taxis are primarily used for quick urban transportation.  
→ Optimizing routing and reducing idle time between trips can improve overall fleet productivity.

---

**Time-Based Demand Variability:**  
Demand patterns vary significantly across different times of day and days of the week, as shown in the heatmap analysis.  
→ Implementing dynamic pricing and intelligent dispatch systems can help better match supply with demand.

---
