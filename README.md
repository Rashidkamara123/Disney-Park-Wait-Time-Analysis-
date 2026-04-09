📌 Project Overview
This project analyzes historical wait time data from Disney World rides to uncover patterns in guest behavior, peak hours, seasonal trends, and the measurable impact of COVID-19 on park operations. The goal is to provide data-driven insights that could inform park capacity planning, guest experience strategy, and operational decision-making.
This analysis is directly relevant to roles in theme park analytics, travel & entertainment data, and operations strategy.

📊 Key Findings
InsightDetail📦 Total Records Analyzed3,509,324🎢 Total Rides Tracked39📅 Date Range2018 → 2022⏱️ Overall Avg Wait Time13.6 minutes🎠 Busiest RideMonorail (35.4 min avg)📆 Busiest DaySaturday🕛 Peak Hour12:00 (noon)📉 COVID Low6.3 min avg (2020)📈 Post-COVID High19.6 min avg (2022)☀️ Hottest MonthAugust

📁 Project Structure
disney-park-wait-time-analysis/
│
├── disney-park-wait-time-analysis.ipynb  # Main analysis notebook
├── waiting_times.csv                      # Primary dataset
├── entity_schedule.csv                    # Ride schedule data
├── link_attraction_park.csv               # Attraction-park mapping
├── disney_top_rides.png                   # Top 10 busiest rides
├── disney_day_of_week.png                 # Wait times by day
├── disney_hourly_wait.png                 # Wait times by hour
├── disney_yearly_trend.png                # Yearly trend with COVID impact
├── disney_heatmap.png                     # Year x Month heatmap
└── README.md
📈 Visualizations
1. Top 10 Busiest Rides
The Monorail leads all attractions with a 35.4 minute average wait, followed by Space Slide and Giant Wheel. Classic Disney infrastructure consistently draws the longest queues.
2. Wait Times by Day of Week
Saturday is the undisputed busiest day at 16.9 minutes average — nearly 30% higher than the quietest days mid-week. Wednesday and Thursday offer the shortest waits for strategic visitors.
3. Wait Times by Hour of Day
Wait times peak sharply at noon and remain elevated through 2PM before declining into the evening. The data suggests arriving at park open or after 6PM minimizes wait times significantly.
4. Yearly Trend (COVID Impact)
Wait times dropped dramatically from 18.4 minutes in 2019 to just 6.3 minutes in 2020 due to COVID-19 capacity restrictions. By 2022, pent-up demand pushed averages to a record 19.6 minutes — the highest in the dataset.
5. Year × Month Heatmap
The heatmap reveals clear seasonal patterns: summer months (June–August) consistently show the highest wait times across all years. The COVID period (2020–2021) shows near-zero values reflecting closures and capacity limits.
Python 3.13
Pandas — data loading, cleaning, feature engineering
NumPy — numerical operations
Matplotlib — custom visualizations
Seaborn — heatmap and styling
JupyterLab — development environment
Source: Disneyland Visitors Data (100+ Rides) — Kaggle
Size: 3,509,324 records
Key Columns: WORK_DATE, DEB_TIME, DEB_TIME_HOUR, ENTITY_DESCRIPTION_SHORT, WAIT_TIME_MAX, GUEST_CARRIED, CAPACITY
💡 Actionable Insights for Park Visitors
Best day to visit: Wednesday or Thursday
Best time to arrive: At park open or after 6PM
Avoid: Saturdays in July and August
Least crowded period: Weekdays in January, February, and November
🚀 How to Run
bash# Clone the repo
git clone https://github.com/Rashidkamara123/disney-park-wait-time-analysis.g
cd disney-park-wait-time-analysis
Rashid Kamara
Data Analyst | Travel & Entertainment Analytics
 rrashid.kamara@gmail.com
github.com/Rashidkamara123
