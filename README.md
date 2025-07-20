Automated Task Scheduler using n8n and Google Sheets

This project is an automated task reminder system built using [n8n](https://n8n.io) and Google Sheets.

It checks your Google Sheet every 5 minute and sends reminders based on the scheduled time (AM/PM format). Ideal for automating your daily routine tasks!

🔧 Features

Time-based condition checks
Google Sheets integration
Send messages to mobile or WhatsApp
Real-time task updates

📁 Workflow Export

This repo includes the exported `.json` workflow file from n8n. You can import it into your own n8n instance.

📦 Tech Stack

- n8n (Open-source automation)
- Google Sheets (Task list & schedule)
- Twilio Mobile Messaging

🧠 How It Works

1. Google Sheet contains task schedule in 12-hour format
2. n8n reads the sheet every minute
3. IF node checks current time and AM/PM
4. Sends a message if there's a match

---

📌 Author

Created by [Siva Raj](https://github.com/Siva-raj06)

