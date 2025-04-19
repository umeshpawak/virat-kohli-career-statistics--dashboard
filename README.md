
# 🏏 Virat Kohli Career Statistics Dashboard (2008–2023)

# objective 
This project showcases an interactive Power BI dashboard tracking the cricket career of Virat Kohli from 2008 to 2023. It displays his performance across different formats (ODI, T20I, Test) using key metrics like total runs, average, strike rate, and boundaries.


## 📊 Dashboard Preview

![Virat Kohli Career Dashboard](https://github.com/umeshpawak/virat-kohli-career-statistics--dashboard/blob/main/virat%20bi%20dashborad.jpeg)



# 🏏 Virat Kohli Career Power BI Dashboard

A Power BI dashboard project analyzing the international cricket career of **Virat Kohli** from 2008 to 2023 — includes insights on total runs, formats played, boundary stats, yearly performance, and key batting KPIs like average and strike rate.

This repository contains a fully interactive Power BI dashboard designed to visually track the consistency and achievements of one of cricket's modern greats.

![Full Dashboard Preview](https://github.com/your-username/virat-kohli-career-dashboard/blob/main/virat%20kohli%20full%20dashboard.png)

---

## 📊 Dashboard Highlights

- **Total Runs Scored:** 26,601  
- **Average:** 53.49  
- **Strike Rate:** 92.59  
- **Innings Played:** 574  
- **4s & 6s Count:** 2,630 Fours and 294 Sixes  
- **50s & 100s per Year:** Trendline breakdown  
- **Format Filter:** ODI, Test, and T20I  
- **Year Range Selector:** 2008 – 2023  
- **Performance Over Time:** Visualized with bar and line charts

---

## 🗂️ Power BI Project File  
[🔗 Download PBIX File](https://github.com/your-username/virat-kohli-career-dashboard/blob/main/virat%20kohli%20career%20dashboard.pbix)

---

## 📄 Dataset Used  
[📁 Download Dataset CSV]()

---

##  Questions & Answers

**Q. How many total runs has Virat Kohli scored?**  
➡ 26,601 runs across all formats.

**Q. What is his overall batting average and strike rate?**  
➡ Average: 53.49, Strike Rate: 92.59

**Q. What years were his top-performing?**  
➡ 2017 and 2018 were peak years with 2800+ runs each.

**Q. How many boundaries has he scored?**  
➡ 2,630 fours and 294 sixes.

**Q. How does he perform in different formats?**  
➡ You can filter by ODI, Test, and T20I for detailed stats.

---

## 🔄 Project Workflow / Process

1. **Collected Data**  
   Career stats compiled from public sources like ESPNcricinfo.

2. **Data Cleaning in Power Query**  
   Removed nulls, fixed year format, standardized column names.

3. **Data Modeling**  
   Connected tables and built relationships between formats, years, and runs.

4. **DAX Calculations**  
   - `Total Runs = SUM(Runs)`
   - `Strike Rate = (SUM(Runs) / SUM(Balls)) * 100`
   - `50s = COUNTIF(Runs, 50-99)`
   - `100s = COUNTIF(Runs, >=100)`

5. **Dashboard Design**  
   Used bar, line, and donut charts with slicers for interactivity.

6. **Final Touches**  
   Added year and format filters, KPIs, and tooltips for a cleaner user experience.

---

## 🛠 Tools Used

- Power BI Desktop  
- Power Query  
- DAX  
- MS Excel (for data prep)

---

## 🙌 Acknowledgments

- Data sourced from public cricket records.  
- Project built for learning, visualization practice, and showcasing data storytelling with Power BI.

---

