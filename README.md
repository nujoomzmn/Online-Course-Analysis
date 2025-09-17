# 📊 Online Course Analytics Dashboard

## Overview  
This project features an interactive **Power BI Dashboard** designed to analyze the performance and trends of a large online course platform. The dashboard provides a comprehensive, data-driven view of key business metrics, including **revenue generation, subscriber growth, audience engagement, and content distribution** across various dimensions like time, course level, and pricing models.  

The insights derived are crucial for **strategic decision-making in content strategy, marketing, pricing, and resource allocation**.  

---

## 🎯 Key Insights & Analysis  

- **Monetization & Popularity:** The vast majority of courses (92%) are paid, indicating a strong monetization strategy. Paid courses are the primary driver of the platform's revenue.  
- **Exponential Growth:** Both the total number of subscribers and total revenue have seen significant year-over-year growth, with a particularly sharp increase from 2015 onwards.  
- **Content Strategy:** All Levels courses are the most popular, making up over half (54.53%) of all content. This is followed by Beginner Level courses (52.45%), suggesting a market heavily skewed towards learners new to a subject.  
- **Seasonal Trends:** Revenue and reviews peak in March, indicating this is a high-activity period for course purchases and engagement. The latter half of the year (Q4) shows a relative dip in revenue.  
- **Engagement Correlation:** A positive correlation is observed between the number of subscribers and the number of reviews, which is a common indicator of course satisfaction and community engagement.  

---

## 📈 Dashboard Metrics & Visualizations  

### High-Level KPI Summary  
- **Total Subscribers:** 12 Million  
- **Total Revenue:** $243K  
- **Total Lectures:** 148K  
- **Average Number of Reviews:** 156 per course  
- **Average Course Duration:** ~4 hours  

### Trend Analysis by Time  
- **Total Subscribers by Year:** Line chart showing subscriber growth from 2011 to 2017.  
- **Sum of Price by Year:** Line chart visualizing revenue growth over the same period.  
- **Total Price and Review by Month:** A dual-axis bar/line chart comparing monthly revenue and review volume, highlighting seasonal trends.  

### Content & Pricing Analysis  
- **Course Level Distribution:** A donut chart showing the breakdown of courses by difficulty level (All Levels, Beginner, Intermediate, Expert).  
- **Column Count by Paid:** A bar chart comparing the volume of Free vs. Paid courses.  
- **Sum of Price by Day:** A detailed bar chart showing which days of the week generate the most revenue.  

### Correlation Analysis  
- **Subscribers vs. Reviews Scatter Plot:** Analyzes the relationship between the number of subscribers a course has and the number of reviews it receives.  

### Detailed Data Table  
- A summary table providing exact figures for Price, Number of Reviews, and a third metric (likely subscribers or courses) broken down by month.  

---

## 🛠️ Technical Details  

- **Tool:** Microsoft Power BI  
- **Data Sources:** The dataset includes records of online courses with attributes such as:  
  - `price`, `is_paid`  
  - `num_subscribers`, `num_reviews`  
  - `published_date` (year, month, day)  
  - `level` (Beginner, Intermediate, etc.)  
  - `content_duration`, `num_lectures`  

- **Interactivity:** The report includes interactive filters for **Year, Month, Day, and Course Level** to slice and dice the data dynamically.  

---


---


---

## 📜 License  
This project is for educational and analytical purposes. Attribution required if reused.  

