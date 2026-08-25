# ***🏥 Healthcare Visits Analysis Dashboard***

## **Project Overview**
This project analyzes 23,800+ healthcare visits collected over 3 years (2023–2025) using Power BI. The dashboard provides insights into patient visits, hospital performance, insurance coverage, patient satisfaction, and demographics through interactive visualizations.

The goal is to help healthcare administrators monitor hospital operations, evaluate patient experience, and identify trends that support data-driven decisions.

## **📁 Dataset Information**

**File:** healthcare_visits.csv

The dataset contains approximately 23,800 patient visit records between January 2023 and December 2025. Each record represents one hospital visit.

---

### Dataset Features

| Column | Description |
|---|---|
| VisitID | Unique visit identifier |
| VisitDate | Date of the visit |
| PatientID | Unique patient identifier |
| Age | Patient age |
| Gender | Patient gender |
| Department | Hospital department |
| Doctor | Attending physician |
| VisitType | Outpatient / Inpatient / Emergency |
| Diagnosis | Patient diagnosis |
| LengthOfStayDays | Hospital stay duration |
| TreatmentCost | Total treatment cost |
| InsuranceProvider | Insurance company or Self-Pay |
| PaymentMethod | Insurance, Cash, or Credit Card |
| InsuranceCoveredPct | Insurance coverage percentage |
| InsuranceCoveredAmount | Amount covered by insurance |
| OutOfPocketCost | Amount paid by the patient |
| SatisfactionScore | Patient satisfaction rating (1–5) |

---

### **📊 Dashboard Pages***

| Page | Description | Screenshot |
|---|---|---|
| **Summary** | Overview of key metrics and KPIs including Total Revenue, Total Visits, MOM Growth %, YOY Growth %, and SPLY | ![Summary](Figs/Screenshot%202026-07-26%20183120.png) |
| **Visits Analysis** | Detailed visit trends and patterns including Visits by Month, Weekday vs Weekend distribution, and Department Visits by Year | ![Visits Analysis](Figs/Screenshot%202026-07-26%20183157.png) |
| **Insurance Analysis** | Insurance coverage and provider analysis including Top Insurance Provider (Allianz), Insurance Covered vs Out-of-Pocket percentages, and Revenue by Department & VisitType | ![Insurance Analysis](Figs/Screenshot%202026-07-26%20183222.png) |
| **Visit Type Analysis** | Breakdown by visit type and department including Patient Volume by Age & Gender, Satisfaction Score Trends, Doctor Performance, and Average Length of Stay by Department | ![Visit Type Analysis](Figs/Screenshot%202026-07-26%20183257.png) |
---

### **📋 Dashboard KPIs**
| KPI | Value |
|---|---|
| Total Patients | ~4,000 |
| Average Stay Days | 1.5 days |
| Insurance Cost Coverage % | 62.45% |
| Average Patient Satisfaction | 3.0 / 5 |
| Average Patient Age | 45.66 years |
| Visits Covered by Insurance % | ~80% |

---

### 📈 Revenue Analysis

**Revenue by Year:**

| Year | Revenue | Growth |
|---|---|---|
| 2023 | 27.14M | - |
| 2024 | 30.08M | +10.8% |
| 2025 | 35.11M | +16.7% |

---

**Revenue by Month (2025):**

| Month | Revenue |
|---|---|
| January | 7.70M |
| February | 7.26M |
| March | 7.50M |
| **Total** | **22.46M** |

---

**Monthly Comparison:**

| Metric | Value |
|---|---|
| MOM Growth % | 3.46% |
| YOY Growth % | 61.36% |
| SPLY | 35.11M |

---

### 👥 Patient Volume by Age & Gender

| Age Group | Female | Male | Total |
|---|---|---|---|
| 18-30 | 2.4K | 2.3K | 4.7K |
| 31-45 | 2.4K | 2.4K | 4.8K |
| 46-60 | 2.4K | 2.4K | 4.8K |
| 60+ | 2.4K | 2.4K | 4.8K |
| **Total** | **9.6K** | **9.5K** | **19.1K** |

---

### 🏥 Department Analysis

**Total Revenue by Department & VisitType:**

| Department | Revenue (M) |
|---|---|
| Cardiology | 9.8 |
| Neurology | 9.6 |
| Orthopedics | 9.6 |
| Oncology | 9.2 |
| Dermatology | 9.2 |
| Emergency | 9.0 |
| General Surgery | 9.0 |
| Internal Medicine | 8.9 |
| Pediatrics | 8.7 |
| Radiology | 9.0 |
| **Total** | **92.0M** |

---

**Average Length of Stay (Inpatient) by Department:**

| Department | Days |
|---|---|
| Cardiology | 5.7 |
| Dermatology | 5.6 |
| Emergency | 5.5 |
| General Surgery | 5.4 |
| Internal Medicine | 5.3 |
| Neurology | 5.2 |
| Oncology | 5.1 |
| Orthopedics | 5.0 |
| Pediatrics | 4.9 |
| Radiology | 4.8 |
| **Average** | **5.25** |

---

### 📊 Visits Analysis

**Visits by Month (2023-2025):**

| Month | Average Visits |
|---|---|
| January | ~2,000 |
| February | ~2,000 |
| March | ~2,000 |
| April | ~2,000 |
| May | ~2,000 |
| June | ~2,000 |
| July | ~2,000 |
| August | ~2,000 |
| September | ~2,000 |
| October | ~2,000 |
| November | ~2,000 |
| December | ~2,000 |
| **Average** | **~2,000** |

---

**Visits by VisitType:**

| Visit Type | Percentage |
|---|---|
| Outpatient | 66.21% |
| Hospital | 24.80% |
| Emergency | 15.18% |
| **Total** | **106.19%** |

---

**Department Visits by Year:**

| Year | Total Visits |
|---|---|
| 2023 | 7.6K |
| 2024 | 7.8K |
| 2025 | 8.5K |
| **Total** | **23.9K** |

---

**Weekday vs Weekend Visits:**

| Day Type | Percentage |
|---|---|
| Weekend | 75.4% |
| Weekday | 24.6% |
| **Total** | **100.0%** |

---

### 💰 Insurance Analysis

**Top Insurance Provider:**

| Provider | Covered Revenue |
|---|---|
| Allianz | 18.18M |
| **Total** | **18.18M** |

---

**Insurance Coverage:**

| Category | Percentage |
|---|---|
| Insurance Covered | 37.55% |
| Out-of-Pocket | 62.45% |
| **Total** | **100.00%** |

---

### ⭐ Patient Satisfaction

**Average Satisfaction Score Trend:**

| Month | Score |
|---|---|
| January | 3.02 |
| February | 3.00 |
| March | 2.98 |
| April | 2.96 |
| May | 2.94 |
| June | 2.92 |
| July | 2.90 |
| August | 2.88 |
| September | 2.86 |
| October | 2.84 |
| November | 2.82 |
| December | 2.80 |
| **Average** | **2.91** |

---

**Average Satisfaction by Department:**

| Department | Score |
|---|---|
| General Surgery | 3.06 |
| Neurology | 3.04 |
| Reflexology | 3.04 |
| Dermatology | 3.01 |
| Orthopedics | 3.00 |
| **Average** | **3.03** |

---

**Doctor Performance:**

| Doctor | Visit Count | Avg Satisfaction |
|---|---|---|
| Dr. Ahmed Fathy | 1.13K | 3.05 |

## **🎯 Key Insights**
### 👥 Patient Overview
Nearly 4,000 unique patients visited the hospital during the analysis period

The average patient age is 45.66 years

Patient volume remains relatively stable across months

### 🏥 Hospital Stay
Average hospital stay is 1.5 days

Cardiology has the longest average stay at 5.7 days

Most visits are outpatient (66.21%)

### 💰 Revenue & Insurance
Total Revenue 2025: 35.11M (29.4% growth from 2023)

Insurance covers 62.45% of treatment costs

Allianz is the top insurance provider with 18.18M covered revenue

80% of all visits covered by insurance

### ⭐ Patient Satisfaction
Average satisfaction score: 3.0 / 5

General Surgery has highest satisfaction (3.06)

Monthly satisfaction shows slight downward trend (3.02 → 2.80)

### 📈 Trends
Weekend visits account for 75.4% of total visits

Revenue shows consistent growth year over year

Department visits increasing annually (7.6K → 8.5K)

### 🛠️ Tools Used
Power BI Desktop - Dashboard creation and visualization

Power Query - Data transformation and cleaning

DAX - Time intelligence and complex calculations

Data Modeling - Building relationships and star schema

Interactive Visualizations - Drill-through and filtering capabilities

## 🌟 Support & Feedback

If you find this project helpful or useful for your analysis, please consider giving it a **Star** ⭐️ to show your support!

[![GitHub stars](https://img.shields.io/github/stars/fareshisham576-lgtm/HealthCare_Visits_Analysis?style=social)](https://github.com/fareshisham576-lgtm/HealthCare_Visits_Analysis)

### **Made By**
## ***Fares Hesham Mohammed***
### **LinkedIn Profile**
[Fares Hisham](https://www.linkedin.com/in/fares-hisham-a862a1375?utm_source=share_via&utm_content=profile&utm_medium=member_android)
