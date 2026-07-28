# 🌦️ Automated Weather Notification Workflow

A lightweight workflow built with **n8n** that automatically retrieves current weather information from the **OpenWeatherMap API** and delivers it to Gmail on a scheduled interval.

> This project was created to learn workflow automation, API integration, and event-driven scheduling using n8n.

---

## 🚀 Overview

Instead of manually checking the weather every day, this workflow automates the process by fetching the latest weather information and emailing it automatically.

---

## 🔄 Workflow

```text
Schedule Trigger
        │
        ▼
OpenWeatherMap API
        │
        ▼
Gmail
```

---

## 🛠️ Tech Stack

- n8n
- OpenWeatherMap API
- Gmail Integration

---

## ✨ What I Learned

- Creating scheduled workflows in n8n
- Integrating third-party REST APIs
- Working with API responses
- Automating repetitive tasks
- Connecting multiple services without writing backend code

---

## 📂 Project Files

```
📁 weather-email-automation
 ├── weather-email-automation.json
 ├── workflow.png
 └── README.md
```
## 🚀 Getting Started

1. Clone this repository.
2. Import `weather-email-automation.json` into n8n.
3. Configure your OpenWeatherMap credentials.
4. Configure your Gmail credentials.
5. Replace the recipient email address.
6. Publish the workflow.
---

## 📸 Workflow

*(Add your screenshot here.)*

---

## 💡 Future Improvements

- Send alerts only when rain is expected.
- Include weather forecasts instead of current conditions.
- Support notifications through Telegram or Slack.
- Add AI-generated weather summaries.

---
