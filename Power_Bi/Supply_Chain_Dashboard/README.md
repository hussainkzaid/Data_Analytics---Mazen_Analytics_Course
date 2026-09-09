# Baladna Food Industries Performance Analytics Dashboard

An interactive **Power BI Dashboard** built for **Baladna For Food Industries** to monitor supply chain operations, production volumes, regional distribution, target achievements, and week-over-week (WoW) growth across Egyptian governorates.

---

## 📊 Executive Summary & Core KPIs

- **Total Produced Quantity:** 4 Million units *(Current Week: 204K | Last Week: 193K | WoW Growth: ▲ 6.0%)*
- **Target Achievement Rate:** 49.28% *(Current Week: 58.47% | Last Week: 67.57% | Change: ▼ 13.5%)*
- **Weekly Distribution:** 93 Million units *(Current Week: 25M | Last Week: 19M | WoW Growth: ▲ 28.6%)*
- **Average Distribution Rate:** 25.52%
- **Overall WoW Distribution Growth:** 28.63%

---

## 🛠️ Key Dashboard Features & Analytics Views

### 1. Operational Overview
- **KPI Summary Cards:** Tracks real-time production, target achievement, and distribution volume alongside previous-week comparisons and sparklines.
- **Product Category Breakdown:** Donut chart showcasing production share across key product categories including *Cheese, Chilled Juice, Hi-Protein, Ice Tea, and Long Life Milk*.
- **Regional Target vs. Distribution Analysis:** Combined bar-and-line chart tracking total distributed quantity against average target achievement across Egyptian governorates (*Luxor, Assiut, Qena, Aswan, Sohag, Red Sea, Minya, Cairo, Alexandria, Dakahlia, etc.*).
- **Weekly Production vs. Distribution Comparison:** Dual-bar trend visual evaluating volumes across operational weeks.
- **Geographic Supply Map:** Interactive map pinpointing distribution coverage and supply volume density across Egypt.

### 2. Tabular Data View
- Detailed regional matrix breaking down performance by governorate:
  - **Avg Target Achievement (%)**
  - **Distributed This Week vs. Last Week**
  - **Distributed WoW % Growth**
  - **Distribution Rate (%)**
  - **Supply Coverage Index**

### 3. Detailed Region Drill-Down
- Focused KPI cards displaying region-specific metrics (e.g., *Alexandria region analytics showing distribution trends, WoW distribution growth at 28.63%, and supply coverage metrics*).

### 4. Interactive Navigation & UI Control
- Dynamic side panel featuring smooth navigation buttons: **Overview**, **Data View**, and **Filters**.
- One-click **Clear All Slicers** button to instantly reset active analytical views.

---

## 💻 Technical Stack

- **Tool:** Microsoft Power BI Desktop
- **Data Transformations:** Power Query (DAX calculations for WoW growth percentages, weekly target metrics, and coverage ratios)
- **Visuals:** Map Integration, Custom KPI Cards, Combo Bar-Line Charts, Donut Charts, Matrix Tables
- **UI Design:** Custom branded dark-blue theme featuring yellow accents matching company identity

---

## 🚀 How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/baladna-food-industries-dashboard.git
   ```
2. **Open in Power BI:**
   Open the `.pbix` project file in **Microsoft Power BI Desktop**.
3. **Explore Data:**
   Use the side navigation buttons to toggle between the **Overview** dashboard, detailed **Data View** matrix, and customized region slicers.
