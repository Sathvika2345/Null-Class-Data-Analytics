# Null-Class-Data-Analytics
# 📊 Real-Time Data Analytics Projects

This repository contains three real-time data analytics visualizations created as part of internship projects using **Python**, **Power BI**, and **Tableau**. Each visualization addresses specific business requirements with advanced filtering, scheduling logic, and insightful designs.

---

## 🔧 Projects Overview

### 🚀 1. Real-Time Google Play Store Data Analytics (Python)

**📈 Visualization**: Scatter Plot with Trendline  
**🔍 Description**:  
This plot displays the relationship between **revenue** and **number of installs** for **paid apps only**. It includes:
- A **trendline** to show correlation
- **Color-coded points** based on **app categories**

**📦 Tools**:  
- Python  
- Pandas  
- Matplotlib  
- Seaborn

```bash
pip install pandas matplotlib seaborn
ShowGraphFlag = 
VAR CurrentTime = TIME(HOUR(NOW()), MINUTE(NOW()), 0)
RETURN IF(CurrentTime >= TIME(15, 0, 0) && CurrentTime <= TIME(17, 0, 0), 1, 0)
/RealTime-Dashboards
│
├── google-play-python/
│   ├── scatter_plot_revenue_installs.py
│   └── sample_data.csv
│
├── twitter-powerbi/
│   ├── powerbi-dashboard.pbix
│   └── dax-logic.txt
│
├── job-tableau/
│   ├── tableau-dashboard.twbx
│   └── category_translations_calc.txt
│
└── README.md
