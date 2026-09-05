# 🏥 Hospital Patient Data Analysis Dashboard

An end-to-end data analysis project on hospital patient records, covering data cleaning, exploratory data analysis in Python, and an interactive Excel dashboard for tracking admissions, billing, and patient demographics.

## 🎯 Problem Statement

A hospital wants to understand patient admission patterns, billing trends, and demographic distribution to support better resource planning and identify high-billing critical cases.

## 🛠️ Tech Stack

- **Python** (Pandas, Matplotlib, Seaborn) — data cleaning and exploratory analysis
- **Microsoft Excel** — interactive dashboard with slicers and KPI tracking

## 🔄 Approach

1. **Data Cleaning (Python)** — Cleaned and prepared 55,000+ raw patient records, handling missing values and inconsistent formatting across admission, billing, and demographic fields, and exported a cleaned dataset for analysis.
2. **Exploratory Data Analysis (Python)** — Analyzed admission trends, length of stay, and billing patterns using Pandas, with visualizations built in Matplotlib and Seaborn to identify disease patterns and seasonal trends.
3. **Interactive Excel Dashboard** — Designed a dashboard with year and month slicers, KPI cards, and multiple chart types to give an at-a-glance view of hospital operations.

## 🔑 Key Insights

- Analyzed **795 patient records** in the featured monthly report, with an average stay of **15.5 days** and total billing of **~25,341** units.
- Patient gender split is roughly **53:47 (Male:Female)**.
- **Emergency admissions (35%)** slightly outnumber Elective (34%) and Urgent (31%) cases.
- **Senior citizens** form the largest age group among patients (264), followed by Young Adults (212) and Middle-aged patients (197).
- **Asthma, Arthritis, and Hypertension** are the top three medical conditions by patient count.
- Test results skew toward **Inconclusive (34%)**, closely followed by Abnormal (35%) and Normal (31%), suggesting a potential area for diagnostic process improvement.
- Peak admissions were observed during **June–August**, indicating a seasonal surge relevant to staffing and resource planning.

## 📸 Dashboard Preview

![Hospital Dashboard](screenshots/hospital_data_analysis_dashboard.png)

*Interactive Excel dashboard with year/month filters, KPI cards, admission-type breakdown, age-group distribution, test results, and top medical conditions.*

## 📁 Project Structure

```
Healthcare_Data_Analysis/
├── README.md
├── data/
│   ├── raw_hospital_data.csv
│   └── cleaned_hospital_data.csv
├── notebooks/
│   └── analysis.ipynb
├── dashboard/
│   └── Dashboard.xlsx
└── screenshots/
    └── hospital_data_analysis_dashboard.png
```

## ▶️ How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas matplotlib seaborn`
3. Run `notebooks/analysis.ipynb` to reproduce the data cleaning and EDA steps (takes `data/raw_hospital_data.csv` as input and produces `data/cleaned_hospital_data.csv`)
4. Open `dashboard/Dashboard.xlsx` in Excel to explore the interactive dashboard (use the Year/Month slicers to filter)

## 👤 Author

**Shivanshu Mishra**
[LinkedIn](https://linkedin.com/in/shivanshu-mishra-12135a341) | [GitHub](https://github.com/shivanshu-mishra01)
