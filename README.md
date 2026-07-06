# 🚀 Telegram AI Voice & Complaint Management Agent

An autonomous, multi-modal AI Agent built on **n8n** that streamlines customer support by processing both text and voice notes via Telegram. It intelligently looks up order status, logs customer complaints directly into Google Sheets, and sends instant automated replies.

---

## 🔥 Key Features

* **🎙️ Multi-Modal Processing:** Handles both text messages and voice notes seamlessly via Telegram.
* **🧠 Intelligent AI Routing:** Powered by advanced AI logic to understand customer intent (Checking Order Status vs. Lodging a Complaint).
* **📊 Live CRM Integration:** Automatically appends and updates customer complaints in a Google Sheets database (`complaint_log`).
* **⚡ Instant Automated Responses:** Keeps customers engaged with real-time updates and ticket confirmations.

---

## 🛠️ Tech Stack & Tools Used

* **Automation Engine:** n8n
* **Frontend/Interface:** Telegram Bot API
* **Database/CRM:** Google Sheets API
* **Language/Logic:** JavaScript / JSON

---

## 📂 How to Use This Workflow

1. Download or copy the blueprint from the `workflow.json` file in this repository.
2. Open your **n8n** instance.
3. Create a new workflow, click anywhere on the canvas, and press `Ctrl + V` to import the entire agent setup.
4. Configure your Telegram Bot credentials and link your Google Sheet.
