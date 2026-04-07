# Mental Health Platform – Data Analysis

##  Overview
This project focuses on analyzing user behavior on a mental health platform. The goal was to understand how users interact with therapy sessions, identify where users drop off, and uncover ways to improve retention and revenue.

The analysis was performed using Python in Google Colab, with data cleaning, feature engineering, and exploratory analysis.

---

## Objectives
- Analyze user retention across therapy sessions
- Identify the biggest drop-off point in the user journey
- Evaluate therapist performance using user ratings
- Understand revenue distribution across users and therapists
- Generate insights to improve user engagement

---

##  Tech Stack
- Python (Pandas, NumPy)
- Matplotlib (for visualization)
- Google Colab
- Excel (dataset)

---

##  Dataset Description
The dataset consists of three main components:
- **Sessions**: Contains session details like user ID, therapist ID, session date, and fee
- **Users**: Includes user signup date and acquisition source
- **Feedback**: Contains session ratings and review text

---

##  Data Processing Steps
- Handled missing values using median and logical defaults
- Removed duplicate and inconsistent session entries
- Corrected session sequence using chronological order
- Merged all datasets into a unified structure
- Created new features like:
  - Total sessions per user
  - Average rating per user
  - Time gap between sessions

---

##  Key Analysis Performed
- **Cohort Analysis** to track retention over time
- **Funnel Analysis** (Session 1 → Session 2 → Session 3)
- **Therapist Performance** based on average ratings
- **Correlation Analysis** between ratings and retention
- **Revenue Analysis** (per user and therapist)
- **Drop-off Analysis** to identify churn points

---

##  Key Insights
- The highest user drop-off occurs between **Session 1 and Session 2**
- Users who give higher ratings are more likely to continue sessions
- Retention improves significantly after the second session
- Not all acquisition sources bring high-value users
- Therapist performance directly impacts user retention

---

##  Business Recommendations
- Focus on improving the first session experience
- Introduce follow-up reminders after Session 1
- Match users with better-suited therapists early
- Track **Session 2 Booking Rate** as a key metric
- Optimize marketing channels based on user lifetime value, not just signups

---

##  Outputs
The project generates the following files:
- Cohort analysis data
- Funnel conversion data
- Revenue analysis
- Drop-off distribution

These can be used to build dashboards in tools like Looker Studio.

---

## 🚀 Conclusion
This project highlights how data can be used to understand user behavior and improve product performance. By focusing on retention and user experience, the platform can significantly increase both engagement and revenue.
