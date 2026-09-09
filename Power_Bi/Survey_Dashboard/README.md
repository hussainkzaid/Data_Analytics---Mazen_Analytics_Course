# Data Professional Survey Breakdown Dashboard

An interactive **Power BI Dashboard** that analyzes survey results from data industry professionals, uncovering key insights on demographics, salary benchmarks, favorite programming languages, work-life balance, and job satisfaction.

---

## 📊 Executive Summary & Core Metrics

- **Total Survey Takers:** 630 professionals
- **Average Age of Participants:** 29.87 years
- **Work/Life Balance Happiness Score:** 5.74 / 10
- **Salary Satisfaction Score:** 4.27 / 10

---

## 🛠️ Key Dashboard Features & Visualizations

### 1. High-Level Demographics
- **Count & Age Cards:** Instant KPI indicators showing total survey participants (630) and their average age (~30 years old).
- **Geographic Distribution (Treemap):** Visual breakdown of survey respondents across major regions including *United States, Canada, India, United Kingdom, and Other countries*.

### 2. Compensation & Role Analytics
- **Average Salary by Job Title:** Horizontal bar chart comparing average compensation across roles:
  - **Data Scientist** (Highest compensation)
  - **Data Engineer**
  - **Data Architect**
  - **Data Analyst**
  - **Database Developer**
  - **Students / Job Seekers**
- **Perceived Difficulty in Breaking Into Data:** Donut/pie chart categorizing job search and career entry difficulty (*Neither easy nor difficult, Difficult, Easy, Very Difficult, Very Easy*).

### 3. Technical Preferences
- **Favorite Programming Language:** Stacked bar visual highlighting language adoption among data professionals:
  - **Python** (Overwhelming majority leader with 400+ voters)
  - **R**
  - **Other**
  - **C / C++**
  - **JavaScript**
  - **Java**

### 4. Work Satisfaction Metrics (Gauge Charts)
- **Happiness With Work/Life Balance:** Measured at **5.74 out of 10**.
- **Happiness With Salary:** Measured at **4.27 out of 10**, indicating a lower average satisfaction level with compensation compared to work-life flexibility.

---

## 💻 Technical Stack

- **Analytics Tool:** Microsoft Power BI Desktop
- **Data Transformations:** Power Query (Data cleaning, handling survey responses, DAX measures for average age and happiness scores)
- **Visuals Used:** Treemaps, Gauge Charts, Horizontal Bar Charts, Donut Charts, Stacked Column Charts, Card Visuals
- **UI Design:** Slate & Earthy Dark Palette with contrasting accents

---

## 🚀 How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/data-professional-survey-dashboard.git
   ```
2. **Open in Power BI:**
   Open the `.pbix` project file in **Microsoft Power BI Desktop**.
3. **Explore Insights:**
   Interact with any visual (such as selecting a specific job title or country) to cross-filter satisfaction scores, salary figures, and programming language choices dynamically.
