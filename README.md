# Call-Center-Performance-Report

📌 Project Overview

This project analyzes call center performance by tracking key metrics such as:

Call handling efficiency (duration & resolution time)

Agent-wise performance

Customer satisfaction (CSAT) trends

Call type distribution

The goal is to provide actionable insights into team productivity and customer experience using data visualization dashboards.


🎯 Objectives

Measure average resolution time and call duration across agents.

Track monthly call volumes to identify workload patterns.

Visualize call type distribution (Billing, Tech, Sales, etc.) per agent.

Monitor customer satisfaction (CSAT) trends to improve service quality.

Highlight top-performing and low-performing agents.

📂 Project Structure
Call-Center-Performance/
    │
    ├── call_logs.csv             # Dataset (synthetic sample)
    └── call_center_analysis.py   # Python script for analysis

⚙️ Procedure

Load data from call_logs.csv

Clean & preprocess (convert dates, group by fields)

Compute KPIs:

📞 Total Calls

⏱️ Average Call Duration

⚡ Average Resolution Time

😀 Average CSAT Score

Visualize with charts:

Monthly Call Volume (Line Chart)

Avg. Resolution Time by Agent (Bar Chart)

Call Volume by Type per Agent (Stacked Bar)

Monthly CSAT Trend (Line Chart)

Avg. CSAT by Agent (Bar Chart)

📊 Expected Outputs

Console KPIs

📞 Total Calls: 200
⏱️ Average Call Duration (sec): 315.2
⚡ Average Resolution Time (sec): 290.8
😀 Average CSAT Score: 3.9


Visualizations

Line chart: Monthly call volume 📈

Bar chart: Avg. resolution time per agent 📊

Stacked bar chart: Call volume by type per agent 🟦🟥🟧

Line chart: Monthly CSAT trend 😀

Bar chart: Avg. CSAT per agent ⭐

🚀 How to Run
1. Clone the repo
git clone https://github.com/yourusername/call-center-performance.git
cd call-center-performance

2. Install dependencies
pip install pandas matplotlib

3. Run the analysis
python call_center_analysis.py

4. View results

KPIs will print in the console

Charts will open in pop-up windows

📈 Insights & Usage

This project helps:

Managers monitor agent performance 📊

Support leads identify reasons for poor CSAT 😕

Operations teams allocate resources better ⚡

🛠️ Tech Stack

Python 🐍

Pandas (data analysis)

Matplotlib (data visualization)

✅ Expected Benefits

✔️ Faster performance reviews
✔️ Early detection of customer dissatisfaction
✔️ Improved resource allocation and training

✨ Contributor

Kshitij Chandel
