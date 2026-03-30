# 📊 Automated Trading Analytics Dashboard

## 🚀 Overview
Built an automated trading analytics system that tracks profit/loss, detects trading patterns, and sends real-time alerts using no-code tools.

## 🎯 Problem Statement
Manual tracking of trading performance is time-consuming and prone to errors. This project automates the entire workflow and provides real-time insights.

## 🔧 Tech Stack
- Google Sheets (Data Storage & Cleaning)
- Make.com (Automation & Logic Building)
- Looker Studio (Data Visualization Dashboard)
- Gmail API (Alert System)

## ⚙️ Key Features
- 📈 Automated Profit & Loss tracking
- 📊 Win Rate calculation
- 🚨 Real-time loss alerts via email
- 🔄 Fully automated data pipeline (No manual entry)
- 📉 Performance trend visualization

## 🔄 Workflow
Webhook / Input → Make.com (Router + Filters) → Google Sheets → Looker Studio Dashboard → Gmail Alerts

## 🧠 Logic Used
- Profit > 0 → Stored in Google Sheets
- Profit < 0 → Trigger email alert
- Structured data formatting to fix text-format issues
- Automated row insertion & calculated fields

---

## 📸 Dashboard & Workflow Screenshots

### 📊 Main Dashboard
(https://github.com/Anvesha8888/trading-analytics-dashboard/raw/main/Screenshot%202026-03-30%20182555.png)

### 📈 Performance View
(https://github.com/Anvesha8888/trading-analytics-dashboard/raw/main/Screenshot%202026-03-30%20182632.png)

### ⚙️ Automation Workflow (Make.com)
(https://github.com/Anvesha8888/trading-analytics-dashboard/raw/main/Screenshot%202026-03-29%20204336.png)

### 🔄 Before vs After Automation
(https://github.com/Anvesha8888/trading-analytics-dashboard/raw/main/beforeandafter.png)

---

## 🔥 Key Impact
- Reduced manual tracking effort by **80%**
- Enabled faster decision-making
- Improved trade monitoring accuracy

## 💡 Learnings
- Importance of clean & structured data
- Automation using routers & filters
- Dashboard design for insights

## 🚀 Future Improvements
- AI-based trade prediction
- Risk analysis dashboard
- Mobile notification system
