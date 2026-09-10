# 📊 Job Market Analysis (Data Analyst)

An interactive **Power BI** dashboard designed to analyze the Data Analyst job market, offering key insights into average salaries, required technical skills, experience requirements, remote work trends, and geographic job distribution.

---

## 🖼️ Dashboard Preview

### 1. Job Market Overview
High-level summary tracking total job postings (23.33K), average annual salary ($95.27K), top paying roles (Data Scientist at $136K, Data Engineer at $130K), and top hiring companies.
![Job Market Overview](./Job%20Market%20Analysis%20%28Data%20Analyst%29_page-0001.jpg)

### 2. Skill & Experience Analytics
Deep dive into technical skill demand (Python: 10K+, SQL: 9K+, Excel: 6K+), salary by experience level (Senior: $128.8K, Mid: $99.2K, Entry: $70.8K), and salary trends across work schedules.
![Skill and Experience Analytics](./Job%20Market%20Analysis%20%28Data%20Analyst%29_page-0002.jpg)

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop:** Used to design the report interface, model job market datasets, create dynamic measures, and configure interactive slicers.
* **DAX (Data Analysis Expressions):** Utilized to build custom calculations for average salaries, skill demand counts, and salary benchmarks by experience level.
* **Power Query:** Applied for data cleaning, standardizing salary values across different payment frequencies (hourly vs. annual), and parsing technical skills.
* **CSV / Excel:** Primary structured dataset containing job postings, company details, salaries, location data, and skill tags.

---

## ⚙️ How I Built This Dashboard

1. **ETL & Data Cleaning:**
   * Cleaned and normalized raw job postings data using Power Query, handling missing salary records and standardizing location and job title fields.
2. **Data Modeling:**
   * Structured relational tables linking job postings with skill categories, experience tiers, and geographic regions.
3. **DAX Measures & KPIs:**
   * Created key analytical metrics:
     * **Market Benchmarks:** Total Job Postings (`23.33K`) and Average Salary (`$95.27K`).
     * **Top Technical Skills:** Python (`10,480` postings), SQL (`9,090`), Excel (`6,580`), and Power BI (`3,580`).
     * **Salary Tiers:** Senior-level (`$128.80K`), Mid-level (`$99.20K`), and Entry-level (`$70.80K`).
4. **UI/UX Design:**
   * Implemented a clean modern dark-theme interface with custom side-panel filtering for Job Title, Country, Experience Level, and Work Schedule.

---

## 📂 Repository Structure

```text
Job_Market_Analysis/
│
├── Job Market Analysis (Data Analyst)_page-0001.jpg # Overview page preview
├── Job Market Analysis (Data Analyst)_page-0002.jpg # Skills & Experience preview
├── README.md                                        # Documentation file
└── Job Market Analysis (Data Analyst)/             # Project subfolder
    ├── Job Market Analysis (Data Analyst).pbix      # Main Power BI file
    └── [Data Files / CSVs]                          # Source datasets
