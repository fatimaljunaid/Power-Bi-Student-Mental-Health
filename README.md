# Student Mental Health Dashboard

An interactive Power BI dashboard analyzing mental health patterns among 100 students, based on a cleaned dataset prepared with Python.

## Table of Contents

- [Overview](#overview)
- [Dashboard Pages](#dashboard-pages)
- [Dataset](#dataset)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Tools Used](#tools-used)
- [Files](#files)
- [Author](#author)

---

## Overview
This project presents a 4-page interactive Power BI dashboard that explores the factors affecting student mental health across 100 students and 26 variables.

The dashboard transforms a cleaned survey dataset into actionable insights for educators, counselors, and school administrators.

**Highlights:**
- 4 interactive pages
- AI-powered Key Influencers visual
- Decomposition Tree for drill-down analysis
- Prioritized recommendations based on data

---

## Dashboard Pages

### Page 1: Student Mental Health (Overview)
![Overview](screenshots/dashboard_page1.png)

- Total student count (100)
- Average Mental Health Score (15.61)
- Average Wellness Index (5.19)
- Risk Level distribution (Donut Chart)
- Correlation by Factor (Bar Chart)

---

### Page 2: Deep Dive Analysis
![Deep Dive](screenshots/dashboard_page2.png)

Advanced analytics with interactive visuals:
- **Key Influencers** - AI-powered factor discovery
- **Scatter Plot** - Sleep Quality vs Mental Health
- **Gauge** - Overall Mental Health indicator
- **Treemap** - Risk distribution
- **Ribbon Chart** - Sleep pattern impact

---

### Page 3: Detailed Student Data
![Details](screenshots/dashboard_page3.png)

Tabular analysis for in-depth review:
- Key metrics by Risk Level
- Key metrics by Teacher Relationship
- KPI cards for quick reference

---

### Page 4: Recommendations
![Recommendations](screenshots/dashboard_page4.png)

Five actionable recommendations prioritized by impact:
- Priority 1 (Urgent): Mental Health Intervention
- Priority 2 (High): Substance Use Prevention
- Priority 3 (Medium): Teacher Relationship Training
- Priority 4 (Medium): Sleep Hygiene Programs
- Priority 5 (Low): Re-evaluate Social Media Priorities

---

## Dataset

**Source:** Mental health survey of 100 students

**Variables:** 26 features across 5 categories

| Category | Variables |
|----------|-----------|
| Mental Health | Anxiety, Depression, Stress Levels |
| Academic | Performance, Engagement, Stress |
| Lifestyle | Sleep Quality, Physical Activity, Nutrition |
| Social | Family Support, Peer Support, Teacher Relationship |
| Behaviors | Social Media, Substance Use, Mood Fluctuations |

**Derived Metrics:**
- **Mental Health Score** (0-30): sum of Anxiety + Depression + Stress
- **Wellness Index** (0-10): average of Sleep + Self-esteem + Emotional Stability
- **Risk Level**: Low / Medium / High classification

The dataset was cleaned and prepared using Python (pandas, numpy).

---

## Key Findings

### 1. High Risk Prevalence
- 45% of students are in the High Risk category
- 46% are in Medium Risk
- Only 9% are in Low Risk

### 2. Strongest Risk Factors
| Factor | Correlation |
|--------|:-----------:|
| Substance Use | +0.31 |
| Nutrition Quality | +0.17 |

### 3. Strongest Protective Factors
| Factor | Correlation |
|--------|:-----------:|
| Motivation Level | -0.27 |
| Teacher Relationship | -0.21 |
| Sleep Quality | -0.19 |
| Work-Life Balance | -0.15 |

### 4. Teacher Relationship Impact
| Relationship | Mental Health Score | High Risk % |
|--------------|:---:|:---:|
| Negative | 17.06 | 53% |
| Neutral | 15.23 | 44% |
| Positive | 14.33 | 37% |

Positive teacher relationships reduce High Risk probability from 53% to 37%.

### 5. Surprising Finding
Social Media Addiction showed no significant correlation with mental health issues in this dataset. This suggests either confounding variables exist, or social media may serve as a coping mechanism rather than a cause.

---

## Recommendations

| Priority | Area | Action |
|:---:|------|--------|
| 1 | Mental Health Intervention | Counseling services, screening program, peer support |
| 2 | Substance Use Prevention | Awareness campaigns, counseling, parent education |
| 3 | Teacher Relationship Training | Workshops, mentorship, feedback sessions |
| 4 | Sleep Hygiene Programs | Sleep education, screen time limits, relaxation techniques |
| 5 | Social Media Re-evaluation | Shift focus, investigate other factors |

---

## Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Interactive dashboard |
| **DAX** | Calculated measures |
| **Python (pandas)** | Data cleaning and preparation |
| **CSV** | Data source format |

---

## Files

```
mental-health-dashboard/
├── screenshots/                    # Dashboard page images
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   ├── dashboard_page3.png
│   └── dashboard_page4.png
├── clean_data.csv                  # Cleaned dataset
├── PowerBI_Dashboard.pbix          # Power BI file
└── README.md
```

---

## Author

**Fatima Al Junaid**

- GitHub: [@fatimaljunaid](https://github.com/fatimaljunaid)
- Data Analyst | Power BI | Python | SQL

---

## License

This project is open for educational and research purposes.
