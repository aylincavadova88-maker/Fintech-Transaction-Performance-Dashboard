## 🎯 What I Did: Extensive Fintech Analytics Framework

### 1. Advanced Data Cleaning & Engineering (Data Hygiene)
* **Deduplication:** Audited the transaction ledger and removed duplicate row entries to prevent double-counting of fintech volumes.
* **Null Value Resolution:** Isolated system errors and dropped missing/null transaction entries to ensure 100% data integrity.
* **Transaction Status Filtering:** Separated `Success` transactions from `Failed/Cancelled` status records to calculate actual net revenue.
* **Numerical Masking:** Cleaned up numerical display noise by truncating unnecessary decimals (removing `.00` values) to make financial figures instantly readable.
* **Chronological Standardization:** Converted raw timestamps into clean date hierarchies and compressed long month names (`yan`, `fev`) to optimize chart whitespace.

### 2. Multi-Dimensional Modeling & KPI Generation (Pivot Architecture)
* **Transaction Value Buckets:** Created custom segmentation categories to group transaction sizes into behavioral buckets (e.g., Low, Medium, High Value) for user profiling.
* **Volume & Revenue Trends:** Engineered multi-year Pivot matrices aggregating chronological velocity trends to trace cyclical usage peaks.
* **Relative Share Calculations:** Formulated percentage-of-total calculations to evaluate the dynamic market share of each payment method/merchant category.

### 3. Fintech Dashboard UI/UX Design
* **Corporate Theme:** Applied a professional dark-blue executive layout tailored for digital banking and fintech presentation standards.
* **Trend & Proportional Charts:** Connected high-impact Line Charts for velocity tracking and Doughnut Charts for structural segment contribution.
* **Interactive Dynamic Slicers:** Integrated responsive Slicers (`Region` and `Segment`) to allow stakeholders to perform real-time, cross-pivot interactive filtering.
