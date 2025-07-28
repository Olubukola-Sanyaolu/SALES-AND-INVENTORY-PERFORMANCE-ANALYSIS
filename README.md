#  Sales & Inventory Performance Analysis



##  Business Problem

A mid-sized retail business is facing challenges with **declining sales volume**, **frequent stockouts**, and **inefficient inventory turnover**. Despite strong-performing products in both revenue and volume, the business struggles to:

- Maintain optimal stock levels
- Replenish inventory for fast-moving items in time
- Reduce accumulation of dead stock
- Track supplier reliability and lead times

Additionally, **46% of the inventory is either out of stock or below reorder point**, indicating poor demand forecasting and replenishment inefficiencies. To address these issues and support better decision-making, two Power BI dashboards were developed.

---

##  Dashboard 1: Sales & Product Insights

This dashboard focuses on **sales performance**, product revenue, and stock-level impact.

<img width="737" height="399" alt="sales" src="https://github.com/user-attachments/assets/cc44ae29-042d-4c11-8f7b-5d505847ffed" />


###  Key Insights:
- **Sales Volume Trend:** Steady decline from Q1 (15.3K) to Q3 (13.8K)
- **Revenue Trend:** Highest in Q2 ($93K), dropped in Q3 ($81K)
- **Top Revenue Generators:** Arabica Coffee ($18K), White Tea ($16K), Halibut ($11K)
- **Top-Selling Products by Volume:** Bread Flour (1,002 units), Pomegranate (972), Cauliflower (911)
- **Dead Stock Identified:** Products like Butter, Milk, and White Rice have high stock but no sales
- **Stock Alert:** 46% of items are either out of stock or below reorder levels

###  Recommendations:
- Investigate causes of the **decline in sales volume** (e.g. seasonality, stockouts, competition)
- Restock fast-moving and high-revenue products like Bread Flour, Arabica Coffee
- Launch **promotional campaigns** to clear out dead stock
- Monitor suppliers contributing to stock issues and re-evaluate contracts
- Align procurement cycles with **quarterly revenue trends**

---

##  Dashboard 2: Inventory Insights

This dashboard focuses on **inventory turnover**, restocking needs, and supplier performance.


<img width="712" height="400" alt="inventory" src="https://github.com/user-attachments/assets/083adaf1-0d2e-428c-b32c-b6e6a59556bb" />


###  Key Insights:
- **Total Inventory Value:** $333K
- **Total Stock on Hand:** 55,053 units
- **Average Unit Price:** $6
- **Average Inventory Turnover Rate:** 24
- **Average Lead Time:** 15 days (some products have over 60 days)
- **Top Turnover Products:** Bread Flour (1,047), Egg (Goose) (920), Cauliflower, Bell Pepper
- **Backorders Detected:** Several products are flagged as “Backordered” despite high demand
- **Discontinued Items:** Still present in inventory (e.g. IDs 03-644-9775, 64-041-8691)

###  Recommendations:
- Automate **reorder alerts** for fast-moving, high-turnover products
- Prioritize restocking for top-selling items like Bread Flour, Cauliflower
- Remove **discontinued items** from inventory and reporting systems
- Conduct a **supplier performance review**, especially those with long lead times or frequent backorders
- Use **ABC inventory analysis** to categorize products by value and movement
- Maintain safety stock for products with high lead time or inconsistent supply

---

##  Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI** | Data modeling, DAX calculations, KPI cards, interactive visuals, slicers |


---



##  Value Delivered

- Increased visibility into sales & product performance
- Improved stock planning and reduced risk of stockouts
- Enabled proactive inventory management and supplier evaluation
- Equipped stakeholders with an **interactive decision-support tool**

