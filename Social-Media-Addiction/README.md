# 📱 Student Social Media Addiction Metrics

## 📌 1. Project Overview
This project analyzes survey records from **705 students** to measure how daily screen time impacts sleep, mental health, and academic focus. The goal is to isolate the exact usage threshold where regular app activity becomes a behavioral risk.

---

## 📂 2. Project Directory

| File Name | Description | Link |
| :--- | :--- | :---: |
| 📊 **Students Social Media Addiction (1).csv** | Raw 705-row student survey data | [Open](./Students%20Social%20Media%20Addiction%20(1).csv) |
| 📓 **Social Media Addiction.ipynb** | Data cleaning & exploratory analysis | [Open](./Social%20Media%20Addiction.ipynb) |
| ⚙️ **python main.py** | Automated batch pipeline script | [Open](./python%20main.py) |
| 🖼️ **social_media_chart.png** | Final platform distribution chart | [View](./social_media_chart.png) |

---

## 📊 3. Chart Preview
![Social Media Addiction Chart](./social_media_chart.png)

---

## 💡 4. Key Metrics & Insights

### A. Platform Metrics vs. Lifestyle
| Platform | Users | Daily Screen Time | Addiction (1-10) | Nightly Sleep |
| :--- | :---: | :---: | :---: | :---: |
| 💬 **WhatsApp** | 54 | **6.48 Hours** | **7.46** | 5.87 Hours |
| 🎵 **TikTok** | 154 | **5.35 Hours** | **7.43** | 6.36 Hours |
| 📸 **Instagram** | 249 | 4.87 Hours | 6.55 | 7.02 Hours |
| 👥 **Facebook** | 123 | 4.51 Hours | 5.67 | 7.36 Hours |
| 💼 **LinkedIn** | 21 | 2.52 Hours | 3.81 | 7.29 Hours |

### B. The 5-Hour Daily Tipping Point
| Daily Screen Time | Avg. Addiction | Avg. Sleep | Avg. Mental Health | Academic Issues |
| :--- | :---: | :---: | :---: | :---: |
| **Moderate** (≤ 5 hrs) | 5.48 / 10 | 7.51 Hours | 6.86 / 10 | **39.6%** of students |
| **Heavy** (> 5 hrs) | **7.77 / 10** | **5.97 Hours** | **5.34 / 10** | **98.6%** of students |

### C. Core Data Correlations
* **Addiction vs. Mental Health ($r = -0.95$):** Severe app dependency matches a sharp drop in wellness scores.
* **Addiction vs. Social Conflicts ($r = +0.93$):** Higher dependency tracks directly with increased peer/family arguments.
* **Daily Screen Time vs. Sleep ($r = -0.79$):** Heavy daily usage cuts away **1.5 hours** of rest every single night.

---

## 🎯 5. Conclusion & Suggestions
* **Conclusion:** **5 hours of daily usage** is the critical danger zone. Passing this threshold triggers severe sleep deprivation ($<6$ hours) and a near-total collapse in academic focus (**98.6%**), driven mostly by TikTok, WhatsApp, and Instagram.
* **Suggestions:** Set automated app reminders at 4.5 hours of use, disconnect from algorithmic feeds 90 minutes before bedtime to restore sleep, and use screen-time flags as an early warning metric for student counseling support.

---
🔗 **Return to Main Portfolio:** [@Ravikumar196](https://github.com/Ravikumar196) | Connect via **[LinkedIn](https://www.linkedin.com/in/ravi-kumar-13b322236/)**
