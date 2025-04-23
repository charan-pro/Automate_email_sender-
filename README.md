# 📩 Automating Email Sender – n8n Workflow

This repository contains an advanced workflow built using [n8n](https://n8n.io), designed to automatically generate and send emails using the **Gemini AI model** for smart content creation.

🔗 **Live Workflow Link**: [View on n8n Cloud](https://charan-pro.app.n8n.cloud/workflow/kVm6qpQfuHCXxWXd)   

---

## 🧠 Overview

### 📌 Workflow Name:
**Automating Email Sender **

### 🤖 Purpose:
To automatically generate email content using the **Gemini AI** (Google's conversational model), and then send it via email – completely automated within an n8n workflow.

### 💼 Use Cases:
- Marketing automation: generate and send personalized emails
- Customer support: auto-respond with AI-generated answers
- Daily or weekly reports with smart summaries
- Notification emails with custom AI-generated messages

## 🔧 Workflow Capabilities

✅ Accepts prompts or triggers (manual, webhook, scheduled, etc.)  
✅ Sends that prompt to the **Gemini AI model**  
✅ Receives and formats AI-generated email content  
✅ Sends the email to the recipient via an email service (like Gmail or SMTP)  
✅ Logs or stores the results if configured (optional)

---

## 📁 Files in this Repository

| File Name                       | Description                               |
|--------------------------------|--------------------------------------------|
| `automating-email-sender-4.json` | Exported n8n workflow JSON file           
| `README.md`                    | Detailed documentation for this workflow   |

---

## 🚀 How to Use This Workflow

### 1. Download the Workflow
- Click on `automating-email-sender-4.json` (once added)
- Click **“Download”** or copy the raw content

### 2. Import into n8n
- Open your n8n instance (cloud or local)
- Go to the menu → **Import Workflow**
- Paste the copied JSON or upload the downloaded file

### 3. Configure:
- Add or update your **email credentials** (SMTP, Gmail, etc.)
- Set up your **Gemini AI API key or connection**
- Customize prompts and logic for your use case

### 4. Activate the Workflow
- Click **“Activate”** to start using it
- Trigger it manually or let it run on schedule or webhook

### 5. Project screenshots


![automate email](https://github.com/user-attachments/assets/9c477835-7580-4a00-a175-5a697f75cd18)


![2025-04-23 (4)](https://github.com/user-attachments/assets/f220bc42-3238-4efb-a18a-b7bb856b3c3e)


![email2](https://github.com/user-attachments/assets/bc11aae7-9434-4779-83aa-6dfb78a8586e)



### 6.Demo vedio Drive link

https://drive.google.com/file/d/1uiwAfGe3FLCS6iRG4b9yZIj3t5JmQ2Kd/view?usp=drivesdk


## 🔐 Security Note

> Ensure all sensitive data like API keys and email credentials are securely stored using **n8n’s credentials system**.  
> Never hard-code secrets directly into nodes.

---

## 🧑‍💻 Author

**Charan**  
🔗 [My n8n Cloud Workspace](https://charan-pro.app.n8n.cloud)

---

## ⭐ Support & Feedback

If you found this workflow helpful:
- ⭐ Star this repo
- 🛠️ Fork and customize it for your own needs
- 📨 Share your feedback or improvements!

---


