# Healthcare-no-show-analysis

**Real-World EDA Case Study | Patient Behavior Insights | Healthcare Analytics Portfolio**

---

### 📊 Overview

In this project, I perform an exploratory data analysis (EDA) on over 110,000 medical appointment records to understand why patients miss their scheduled visits. The findings provide actionable insights to help healthcare providers reduce no-shows, optimize scheduling, and improve patient engagement.

> 📌 **Primary Goal**: Understand key behavioral and demographic factors that influence appointment attendance.

---

### 🗂️ Dataset Details

| Feature     | Description                                                                                    |
| ----------- | ---------------------------------------------------------------------------------------------- |
| 110k+ rows  | Real hospital appointment records                                                              |
| Key columns | Gender, Age, Hypertension, Diabetes, SMS received, No-show flag                                |
| Source      | [Kaggle – No-show Appointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments) |

---

### 📌 Business Context

> Each missed appointment wastes hospital time, increases patient health risk, and drives up operational cost.

Using historical data, I identify **patterns in patient attendance** across multiple features — such as age, chronic disease, weekday, and SMS reminders — providing insights that can be turned into **preventative actions** by clinics or health systems.

---

### 📈 Key Insights

**Attendance Patterns:** 80% attendance overall; younger patients and those who received SMS reminders show higher no-show rates

**Temporal Trends:** No appointments on Sundays; Saturdays have low appointment volume; weekday attendance remains stable

**Messaging Impact:** Unexpectedly, SMS reminders correlate with higher no-shows, indicating a potential need to improve communication strategies

---

### ⚒️ Methodology

1. **Data Cleaning**

   * Date formatting
   * Column renaming
   * Dropping non-relevant fields
2. **Feature Engineering**

   * Created `Age Group`, `Weekday` features
   * Converted categorical columns to dummies
3. **Univariate & Bivariate EDA**

   * No-show counts vs. Gender, Disease, SMS
   * Correlation plots and heatmaps

---

###  Final Notes

This project demonstrates my proficiency in exploratory data analysis, critical thinking, and deriving actionable insights from real-world healthcare data. It highlights my ability to:

* Analyze large datasets and uncover meaningful patterns
* Use data-driven storytelling to inform healthcare operational decisions
* Apply data cleaning, feature engineering, and visualization techniques effectively
* Communicate complex findings clearly for business stakeholders

