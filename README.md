# Student Performance Analysis Dashboard

## Objective
Analyze how study habits, attendance, and background factors relate to
students' final exam performance, and identify what matters most for
improving academic results.

## Dataset
- 500 student records
- Columns: gender, age, study_hours_per_week, attendance_rate,
  parent_education, internet_access, extracurricular, previous_score,
  final_score, passed
- Note: "None" in parent_education is a valid category (no formal
  parental education), not missing data.

## Tool
Power BI Desktop

## Dashboard Contents
- KPI cards: student count, average attendance, average final score,
  average previous score, average study hours
- Line chart: study hours vs final score
- Line chart: attendance rate (binned) vs final score
- Bar chart: average final score by parental education
- Pie chart: pass/fail distribution
- Slicers: gender, age, parental education, pass/fail, extracurricular

## Key Findings
1. Study hours is the clearest gap between pass and fail. Students who
   passed studied 19.5 hours/week on average, versus 7.7 hours/week for
   those who failed.
2. Attendance also splits pass/fail, but less sharply — 77.9% average
   for passing students vs 73.5% for those who failed.
3. 64.6% of students passed (323 of 500).
4. Gender makes almost no difference in final score (56.5 vs 55.5).
5. Age has little effect on final score, with all ages (15–19) averaging
   within 3 points of each other.

## Recommendation
Since study hours has the strongest link to passing, a study-skills or
time-management support programme is likely to raise outcomes more
than attendance enforcement alone.

## Files in this repository
- `student_performance.csv` — the dataset used
- `Syntecxhub_Student_Performance.pbix` — the Power BI dashboard file
- `dashboard.pdf` — a static, viewable version of the dashboard

## How to view
Open the `.pbix` file in Power BI Desktop (free download), or view
`dashboard.pdf` directly on GitHub for a quick look without installing
anything.
