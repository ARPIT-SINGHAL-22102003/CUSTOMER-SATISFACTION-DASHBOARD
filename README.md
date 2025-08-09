📊 Customer Satisfaction Dashboard – Power BI
📌 Overview
This project is an interactive Customer Satisfaction Dashboard built in Power BI to track key customer experience metrics such as:

Total Tickets handled

Average CSAT Score (Customer Satisfaction Score)

NPS Score (Net Promoter Score)

Average Response Time

Ticket distribution by Category, Channel, and Location

The goal is to provide business insights that help improve service quality, customer loyalty, and operational efficiency.

🗂 Dataset
Source: Simulated/cleaned customer support dataset.

Key Fields:

Category, Channel_Name, Customer_City

CSAT Score

NPS Category (Promoter, Passive, Detractor)

Issue Reported At, Issue Responded At (for response time calculation)

⚙️ Data Cleaning & Transformation
Data preparation was done using Power BI Power Query, including:

Removing irrelevant columns

Handling missing values (e.g., replacing nulls with "Unknown")

Converting date fields to Date/Time format

Creating calculated fields:

Response Time (mins)

NPS Category

NPS Score formula: %Promoters - %Detractors

📈 Dashboard Features
KPIs

Total Tickets: 86K

Avg. CSAT Score: 4.24 / 5

NPS Score: 67.89%

Avg. Response Time: 0.60 sec

Visuals

Column Chart – Tickets by Category

Pie Chart – NPS Category Distribution

Bar Chart – Avg. CSAT by Channel

Line Chart – CSAT Trend over Time

Map – Tickets by City

Interactive Filters (Channel, Category, Date, Agent Shift)

🔍 Key Insights
Returns & Order-Related categories generate the most tickets.

Outcall channel has the highest CSAT; Email needs improvement.

Majority of customers are Promoters (82.46%), indicating strong loyalty.

Fast response times (<1 sec) are a major service strength.

💡 Recommendations
Focus on Returns & Order-Related categories for process optimization.

Improve Email channel performance through training and faster follow-ups.

Replicate Outcall best practices across other channels.

Maintain ultra-fast response times to retain customer satisfaction.

🛠 Tools & Technologies
Power BI – Data visualization and dashboard creation

Power Query – Data cleaning and transformation

Excel – Initial data exploration

📂 Repository Structure
bash
Copy
Edit
📁 Customer-Satisfaction-Dashboard
│── 📄 README.md
│── 📊 CUSTOMER_SATISFACTION_DASHBOARD.pbix   # Power BI dashboard file
│── 📄 Customer_support_data.csv              # Dataset
│── 📄 Report.pdf                             # One-page summary report
🚀 How to Use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/ARPIT-SINGHAL-22102003/Customer-Satisfaction-Dashboard.git
Open the .pbix file in Power BI Desktop.

Explore the dashboard and interact with filters to gain insights.
