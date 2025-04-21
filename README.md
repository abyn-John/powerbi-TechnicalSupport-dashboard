# 🛠️ Technical Support Analytics Report (Power BI)

A data-driven look at how technical support teams perform — who’s killing it, who’s struggling, and where things can be tightened up. Built with Power BI using a technical support dataset packed with ticket and agent data.

---

## 📦 What's Inside

- Problem We’re Solving  
- Project Goals  
- About the Data  
- ETL Breakdown  
- Dashboard Overview  
- Q&A Insights  
- Wrap-Up

---

## ❓ Problem Statement

Support teams deal with tons of tickets. Some get closed fast, others drag. The idea here is to track **ticket resolution efficiency** and **SLA compliance** over time — and shine a light on agent performance.

---

## 🎯 Project Objectives

1. **Monitor Ticket Closure**  
   Track how long it takes to resolve tickets and whether they hit SLA deadlines.

2. **Evaluate Agent Performance**  
   See how different agents are doing — who’s quick, who keeps customers happy.

3. **Measure Customer Satisfaction**  
   Spot trends in post-ticket survey results and agent interactions.

4. **Give Better Insights to Management**  
   Provide clear KPIs to help make smarter operational decisions.

---

## 📊 Dataset Breakdown

This project uses two main tables full of support ticket data. Key fields include:

- **Ticket Status, ID, Priority, Source, Topic**
- **Agent Info**: Name, Group (1st/2nd Line Support)
- **Timestamps**: Created time, Resolution time, Close time
- **SLA Metrics**: For both first response and final resolution
- **Agent-Customer Interactions**
- **Survey Ratings**
- **Geographic Info**: Country, Latitude, Longitude
- **Product & Support Levels**

Basically — who handled the ticket, what was the issue, when did it happen, how fast did they fix it, and how did the customer feel about it.

---

## 🔄 ETL Process (aka Clean-Up Time)

Here’s what went down:

- Loaded the dataset into Power BI  
- Cleaned up: removed empty and error values  
- Checked for data quality issues  
- Transformed columns where needed  

Pretty straightforward.

---

## 📈 Dashboard Pages

This report has **two main pages**:

### Page 1: Ticket Analysis

**KPIs & Visuals:**

- 🕓 Average Resolution Time  
- ✅ SLA Compliance Rate  
- 🗺️ Tickets by Country (Map)  
- 📈 Ticket Volume Over Time (Trend Line)

![image](https://github.com/user-attachments/assets/bfc7b73f-e158-4289-a867-650d8242aada)


---

### Page 2: Agent Performance

**KPIs & Visuals:**

- 🧍 Tickets Handled Per Agent (Table)  
- ⏱️ Total Active Time per Agent (Bar Chart)  
- 🧩 Agent Group Preference (Pie Chart: 1st vs 2nd Line Support)  
- 🎯 Agent Score (Scatter Plot based on Interactions + Survey Ratings)

![image](https://github.com/user-attachments/assets/06ba16f5-565f-4c41-b42c-fa16c63759cc)


---

## 🔍 Analytical Questions Answered

- Are we closing tickets fast enough?
- Which countries or regions have the most issues?
- Are SLAs being met or missed?
- Which agents are standout performers?
- How do customer survey ratings line up with actual agent activity?

---

## 🧠 Conclusion

This dashboard gives a clear look into what’s working and what’s not in support operations. It’s fast, visual, and cuts through the noise. Whether you're managing the team or just curious about performance, this gives you a solid pulse check.

---

## 🚀 Want to Try It?

Clone the repo, open the `.pbix` file in Power BI Desktop, and start exploring.

---

Thanks for stopping by. Feedback, forks, and PRs are welcome. 🙌
