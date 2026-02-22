# 🚀 AI Lead Capture + Smart CRM Automation

## 📌 Overview
An AI-powered lead capture and CRM automation system built using n8n and Airtable.

This workflow:
- Captures leads via Webhook
- Uses OpenAI to classify lead type
- Detects urgency level
- Stores data in Airtable
- Enables automated follow-ups

---

## 🏗 Architecture Flow

Lead Capture:
Webhook → n8n → Airtable → AI Processing → Notification → CRM

Follow-Up Automation:
Schedule Trigger → Airtable → Condition Check → Email → CRM Update

---

## ⚙ Tech Stack
- n8n
- Airtable
- OpenAI API
- Webhooks

---

## 📂 Setup Instructions

1. Import workflow JSON into n8n
2. Add your API keys
3. Connect Airtable credentials
4. Activate workflow

---

## 💼 Use Cases
- Real estate lead automation
- Coaching institute inquiries
- SaaS onboarding systems
- Freelance CRM automation

---

## 🔐 Security Note
API keys and webhook URLs are not included.
Use `.env.example` to configure your environment.

---

## 👨‍💻 Author
Rohan Dune
📧 Email: dunerohan1719@email.com  
🔗 LinkedIn: https://www.linkedin.com/in/rohan-dune/
💼 Open to freelance automation & AI workflow projects
