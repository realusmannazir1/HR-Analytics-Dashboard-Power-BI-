# HR Analytics Dashboard (Power BI)

A comprehensive Power BI dashboard designed to analyze employee data, track key performance indicators (KPIs), and uncover critical insights regarding employee attrition. This interactive dashboard assists Human Resources departments in understanding the core drivers behind turnover, allowing for data-driven retention strategies.

---

## 📊 Dashboard Overview

The dashboard features a dark, modern gradient theme (deep blue to dark red/burgundy) that visually segment top-level KPIs from core categorical breakdowns. It tracks data across **1,470 total employees** with an active focus on the **237 attrition cases** to pinpoint exactly where and why turnover occurs.

---

## 📈 Key Performance Indicators (KPIs)

Located at the top of the report view, these high-level cards provide an immediate pulse check on the organization's workforce status:

* **Count of Employee:** `1,470` — The total number of employee records evaluated in the dataset.
* **Attrition:** `237` — The total number of employees who have left the company.
* **Attrition Rate:** `16.1%` — The percentage of total workforce turnover ($\frac{237}{1470} \times 100$).
* **Average Age:** `37` — The average age of the workforce.
* **Average Salary:** `6.5K` — The average monthly income across employees.
* **Average Years:** `7.0` — The mean tenure of employees at the company.

---

## 🔍 Slicers & Filters

The top-right section provides interactive global slicers to dynamically filter the entire dashboard by specific departments or demographics:

* **Department Slicers:** Quick-toggle buttons for:
    * `Human Resources`
    * `Research & Development`
    * `Sales`
* **Attrition by Gender Slicer:** A segmented visual slice showing the breakdown of attrition by gender:
    * **Male:** 140 employees lost (represented in blue).
    * **Female:** 79 employees lost (represented in orange).

---

## 🎨 Visualization Breakdowns

### 1. Attrition by Education Field (Donut Chart)
Analyzes how turnover is distributed across different educational backgrounds of employees:
* **Life Sciences:** `38%` (Largest contributing field)
* **Medical:** `27%`
* **Marketing:** `15%`
* **Technical Degree:** `14%`
* **Other:** `5%`

### 2. Attrition by Age (Column Chart)
Identifies the specific age demographics most prone to leaving the company, grouped into brackets:
* **26–35:** `116` cases (Peak attrition age group)
* **18–25:** `44` cases
* **36–45:** `43` cases
* **46–55:** `26` cases
* **55+:** `8` cases

### 3. Job Role Attrition Matrix (Table / Heatmap)
A cross-tabulation matrix detailing attrition volume across specific **Job Roles** evaluated against a numerical scale or rating system (columns `1`, `2`, `3`, `4`), along with total sums:
* **Laboratory Technician:** `62` total cases (Highest overall role attrition)
* **Sales Executive:** `57` total cases
* **Research Scientist:** `47` total cases
* **Sales Representative:** `33` total cases
* **Human Resources:** `12` total cases
* **Manufacturing Director:** `10` total cases
* **Healthcare Representative:** `9` total cases
* **Manager:** `5` total cases
* **Research Director:** `2` total cases
* *Total Summed Matrix Check:* `237`

### 4. Attrition by Salary (Horizontal Bar Chart)
Segments employee turnover based on monthly income brackets to see if financial compensation plays a role:
* **Upto 5k:** `163` cases (Massively disproportionate attrition among lower earners)
* **5k–10k:** `49` cases
* **10k–15k:** `20` cases
* **15k+:** `5` cases

### 5. Attrition by Years At Company (Area Chart)
A continuous line/area chart showing the direct relationship between employee tenure (Years at Company) and attrition volume:
* **Peak Attrition:** Occurs sharply at the **1-year** mark (reaching `59` cases).
* **Trend:** Sharp decline after year 1, with minor bumps around year 5 (`19` cases) and year 10 (`10` cases), showing that long-tenured employees are highly stable.

### 6. Attrition by Job Role (Horizontal Bar Chart)
A clean, rank-ordered bar chart summarizing the top roles experiencing turnover to provide immediate visibility into problem areas:
1.  **Laboratory Technician** (`62`)
2.  **Sales Executive** (`57`)
3.  **Research Scientist** (`47`)
4.  **Sales Representative** (`33`)

---

## 🛠️ Tech Stack & Environment

* **Tool:** Power BI Desktop
* **Data Layout:** Single-page interactive report layout optimized for 16:9 screens.
* **Theme/UI:** Customized dark mode gradient dashboard template utilizing card metrics, donut charts, bar/column charts, matrices, and area charts.

---

## 💡 Core Insights Derived
1.  **Early Tenure Risk:** The area chart clearly shows that the first year of employment is the highest risk window for turnover. Onboarding and early-stage engagement strategies need improvement.
2.  **Compensation Correlates with Attrition:** Over **68%** of all attrited employees (`163 out of 237`) earned under \$5,000 per month.
3.  **Role Vulnerability:** Field-level and technical execution roles like *Laboratory Technicians*, *Sales Executives*, and *Research Scientists* make up the vast majority of organizational exits.