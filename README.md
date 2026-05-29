# Parental_leave_denmark
End-to-end analysis of the gender gap in Danish parental leave 2015–2024 using Python, SQL and Tableau

# 🇩🇰 Parental Leave Gender Gap in Denmark (2015–2024)

An end-to-end data analysis exploring how the gender gap in parental 
leave has evolved across Danish municipalities, and what role education 
level and the 2022 law reform played.

## 📊 Interactive Dashboard
👉 [View Tableau Dashboard](https://public.tableau.com/app/profile/daria.ivchenko/viz/BarselDashboard/ParentalLeaveGenderGapinDenmark)

## ❓ Business Questions
1. How has the gender gap in parental leave changed in Denmark between 
   2015 and 2024?
2. Does a father's education level affect how many days of parental 
   leave he takes?
3. Which municipalities have the smallest and largest gender gaps in 2024?

## 🗂️ Data Source
Data is fetched directly from the **Statistics Denmark API** 
(api.statbank.dk), table BARSEL05. This approach ensures full 
reproducibility with no row limits unlike manual CSV downloads.

The dataset covers:
- 98 Danish municipalities + national aggregates
- Years 2015–2024
- Parental leave days broken down by gender, education level, 
  entitlement status and region

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python (pandas, requests, geopy) | Data fetching, cleaning, analysis |
| SQLite + SQL | Database creation and querying |
| Matplotlib | Exploratory visualisations |
| Tableau Public | Interactive dashboard |

## 🔍 Key Findings
- 📉 The gender gap dropped from **253 days in 2015 to 163 days in 2024** 
  — a reduction of 90 days over 9 years
- ⚖️ The **2022 parental leave law reform** caused a sharp acceleration — 
  fathers more than doubled their leave days after 2022
- 🎓 Fathers with a **master's degree** take nearly twice as many leave 
  days as fathers with lower secondary education — and this gap persists 
  across all years
- 🗺️ **Copenhagen and Frederiksberg** consistently show the smallest 
  gender gap; rural municipalities show the largest

## 📁 Repository Structure
```
├── Parental_leave_project.ipynb  # Main analysis notebook
└── README.md
```

## ▶️ How to Run
1. Clone the repository
2. Open `parental_leave_analysis.ipynb` in Google Colab or Jupyter
3. Run all cells — data is fetched live from the Statistics Denmark API
4. No additional data downloads needed

## 👤 Author
**Daria Ivchenko** — Junior Data Analyst  
[LinkedIn](https://www.linkedin.com/in/daria-ivchenko-759830325/) · 
[GitHub](https://github.com/Ida-bit97)
