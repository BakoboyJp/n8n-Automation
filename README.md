
# n8n Workflows for Bakoboy Enterprise

This repository contains custom-built n8n automation workflows designed to support administrative tasks for Bakoboy Enterprise, Inc., a small business operation led by Justin Patt.

## 📋 Workflows Included

### 1. Universal Lead Capture & Auto Reply
**File:** `universal_lead_capture_workflow.json`

**Description:**
This workflow captures incoming leads/messages via webhook (from website forms, SMS, or other integrations), logs the data into Google Sheets, sends an automatic reply (currently via Gmail), and creates a Google Calendar event for follow-up.

**Nodes:**
- Webhook Trigger
- Log to Google Sheet
- Send Auto Reply (via Gmail)
- Create Google Calendar Event

## ✅ How to Use

1. Import the workflow JSON into your n8n editor.
2. Connect the required credentials:
   - Google Sheets
   - Gmail
   - Google Calendar
3. Update the Webhook URL in your form, SMS, or integration platform.
4. Customize the Gmail reply message and calendar details if needed.

## 🔐 Notes

Twilio support is planned but currently pending access. The reply mechanism will be updated from Gmail to SMS once Twilio credentials are available.

---

## 📬 Contact

Justin A. Patt  
Founder, Bakoboy Enterprise, Inc.  
Email: [jpatt@bakoboy.com](mailto:jpatt@bakoboy.com)  
Website: [https://bakoboy.com](https://bakoboy.com)
