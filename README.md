# 🏥 Hospital Emergency Room Dashboard

**An interactive analytics dashboard for exploring hospital emergency room (ER) operations and patient flow.**
This dashboard provides detailed visualizations of ER data, helping administrators and staff identify patterns, monitor performance, and optimize resource allocation.

---

## 📖 Project Overview

The **Hospital Emergency Room Dashboard** is designed to visualize hospital ER data to help understand patient behavior, operational efficiency, and performance metrics. Using structured ER data, this dashboard highlights trends in:

* Patient arrivals and visit volumes
* Wait times and patient throughput
* Admission vs. discharge ratios
* Demographics and patient satisfaction
* Departmental referrals

It is intended for hospital administrators, healthcare analysts, and operational managers who need actionable insights from historical ER data.

---

## 🗃️ Data Used

The dashboard uses a structured **ER dataset** containing the following types of information:

| Data Category                   | Fields                                                                | Description                                                |
| ------------------------------- | --------------------------------------------------------------------- | ---------------------------------------------------------- |
| **Patient Information**         | Patient ID, Age, Gender, Race                                         | Unique identifiers and demographics for ER patients        |
| **Visit Details**               | Visit Date, Arrival Time, Discharge Time, Wait Time, Admission Status | Captures patient flow, duration of stay, and outcomes      |
| **Medical & Departmental Data** | Department Referred To, Reason for Visit, Treatment Provided          | Helps analyze department workload and referral patterns    |
| **Operational Metrics**         | ER Capacity, Staff on Duty, Hourly Patient Count                      | Supports resource planning and identifying bottlenecks     |
| **Patient Feedback**            | Satisfaction Score, Feedback Comments                                 | Measures patient satisfaction by demographic or visit type |

> The data can come from hospital ER logs exported as CSV or structured database extracts.

---

## 🚀 Features & Insights

### Key Features

* **Total ER Visits:** Track daily, weekly, monthly, and yearly patient volumes.
* **Patient Demographics Analysis:** Breakdown by age, gender, and race to identify which groups use ER services the most.
* **Wait Time Analysis:** Average wait times by hour, day, and department to detect bottlenecks.
* **Admissions vs. Discharges:** Compare numbers to understand ER load and hospitalization rates.
* **Referral Analysis:** Examine which departments receive the most referrals and from which patient groups.
* **Satisfaction Analysis:** Compare patient satisfaction across demographics, visit types, and departments.
* **Peak Hour Heatmaps:** Identify busiest times of day to improve staffing efficiency.
* **Trends & Forecasting:** Observe trends in patient volume and wait times over months or years.

### Insights You Can Draw

1. **Patient Volume Patterns:** Identify high-volume days and months to optimize staffing schedules.
2. **Wait Time Bottlenecks:** Detect times when wait times spike and allocate resources efficiently.
3. **Demographic Trends:** Determine which age groups or genders are most frequent ER users.
4. **Admissions Analysis:** See the ratio of patients admitted vs discharged to anticipate bed occupancy.
5. **Departmental Workload:** Understand which departments handle the most ER referrals.
6. **Satisfaction Trends:** Track which groups report lower satisfaction to improve patient experience.
7. **Hourly Analysis:** Pinpoint the busiest hours for targeted resource deployment.

---

## 🛠️ Technology Stack

| Category               | Tool                                         |
| ---------------------- | -------------------------------------------- |
| **Data Visualization** | Power BI Desktop                             |
| **Data Processing**    | Power Query, DAX (Data Analysis Expressions) |
| **Data Source**        | CSV/Database of ER visits                    |
| **File Format**        | `.pbix` for the Power BI project             |

---

## 📊 Dashboards

Below are the key dashboard views included in this project.

### **1. Overall Emergency Room Monthly Overview**

A high‑level view of the emergency room performance showing core metrics like:

* Total number of patients
* Average wait times
* Satisfaction scores
* Admissions vs non‑admissions

![Hospital Emergency Room Dashboard_pages-to-jpg-0001](https://github.com/user-attachments/assets/f38b2a32-fd5d-48f6-8280-3287aeae39f6)

---

### **2. Overall Emergency Room Consolitdated Overview**

Visualizes trends in patient visits over time, including breakdowns by gender, age group, and visit frequency.

![Hospital Emergency Room Dashboard_pages-to-jpg-0002](https://github.com/user-attachments/assets/f1ca92e7-9444-4326-9b61-7b3c942c547a)

---

### **3. Emergency Room Patient Details Analysis**

Shows wait time distribution by department, time of day, and day of week — helping identify bottlenecks.

![Hospital Emergency Room Dashboard_pages-to-jpg-0003](https://github.com/user-attachments/assets/67876e1c-4bdc-48a6-b692-c3eed9d844b7)

---

### **4. Key Takeaways**

Displays key insights from all dashboards.

![Hospital Emergency Room Dashboard_pages-to-jpg-0004](https://github.com/user-attachments/assets/e1c1d62f-1b0d-4d5c-abba-f57b541a16dd)

---

## 📊 Descriptive Analysis & Observations

**(January 2023 - December 2024)**

The emergency room dataset, spanning 24 months, provides valuable insights into the patterns and trends of **3,613 unique patients**.

### Patient Wait Time & Satisfaction

* Average wait time: **≈35.3 minutes**, highlighting the need to improve operational efficiency.
* Overall satisfaction score: **4.86 / 10**, indicating moderate satisfaction levels.
* Patients aged 50-59 years gave the highest satisfaction (**5.29**), while those aged 70-79 years rated the lowest.

### Departmental Referrals

* **2,096 patients** did not require any referrals.
* Among referred patients, the most common departments were:

  * General Practice: 722 cases
  * Orthopedics: 392 cases
  * Physiotherapy: 104 cases
  * Cardiology: 99 cases

### Peak Busy Periods

**Busiest Days:**

* Wednesday: 549 patients
* Monday: 543 patients
* Sunday: 528 patients

**Busiest Hours:**

* 11 PM, 12 AM, 6 PM, 7 PM, indicating the need for sufficient staffing during these times.

### Patient Demographics

**Age Groups:**

* 20-29 years: 501 patients (largest group)
* 30-39 years: 472 patients
* 60-69 years: 473 patients
* 50-59 years: significant number of patients

**Race Distribution:**

* White: 1,008
* African American: 780
* Multiracial: 606
* Asian: 402
* Declined to identify: 399

### Admission Patterns

* **Admitted:** 1,792 patients
* **Treated & Released:** 1,821 patients

### Summary

This analysis highlights:

* High ER patient volume
* Moderate satisfaction levels
* Significant demand for General Practice and Orthopedics referrals
* Busiest periods: Wednesdays and late-night / early-morning hours
* Diverse patient demographics
* Highest satisfaction among 50-59 year-olds (5.29), lowest among 70-79 year-olds

These insights provide actionable data to **enhance resource allocation, streamline operations, and improve patient care quality**.

---

## 🔮 Future Enhancements

* **Predictive Modeling:** Forecast peak hours and patient volume using historical data.
* **Real-Time Integration:** Connect to live hospital data feeds for up-to-date dashboards.
* **Expanded Metrics:** Include treatment success rates, ER cost analysis, or length of stay statistics.
* **Interactive Reports:** Publish dashboards to Power BI Service for web access and sharing.

---
