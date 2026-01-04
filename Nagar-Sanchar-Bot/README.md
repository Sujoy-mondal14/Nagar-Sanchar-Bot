# 🏙️ Nagar Sanchar - AI Local Alert Assistant

> **A Multimodal AI Chatbot built on Botpress to keep citizens informed and safe.**

## 📖 Project Overview
**Nagar Sanchar** is an AI-powered chatbot designed to bridge the gap between official updates and local citizens. It functions as a 24/7 intelligent assistant that aggregates local data to provide real-time alerts about power outages, water supply, and emergency situations.

Unlike traditional apps, Nagar Sanchar is **multimodal**, allowing users to interact via text or voice, making it accessible to a wider demographic.

## 🚀 Key Features
* **📢 Real-Time Alerts:** Delivers instant notifications about local disruptions (electricity, traffic, water).
* **🤖 AI-Powered Understanding:** Uses Large Language Models (LLMs) to understand natural language queries in local dialects.
* **📍 Location-Aware:** Provides hyper-local updates based on the user's specific area.
* **⚡ Multimodal Interaction:** Users can ask questions or report issues using text and media inputs.

## 🛠️ Tech Stack
* **Platform:** [Botpress Cloud](https://botpress.com/)
* **AI Engine:** Gemini 2.5 pro / Claude 3.5 Sonnet (via Botpress)
* **Scripting:** JavaScript (Node.js) for custom API integrations
* **Interface:** Web Widget / WhatsApp Integration

## 📂 Repository Structure
* `Nagar_Sanchar.bpz` - **The Source Code.** This is the full bot export file containing all flows, intents, and logic.
* `screenshots/` - Visual documentation of the bot's workflow and conversation logic.

## ⚙️ How to Run (Instructions for Judges)
Since this project is built on a low-code platform, the logic is encapsulated in the `.bpz` archive.

1.  **Download:** Download the `Nagar_Sanchar.bpz` file from this repository.
2.  **Import:** * Go to the [Botpress Cloud Dashboard](https://cloud.botpress.cloud/).
    * Create a new chatbot.
    * Click on **"Import / Export"** in the top menu.
    * Select **"Import from .bpz"** and upload the file.
3.  **Test:** Click **"Publish"** to test the bot live in the emulator.

## 📸 Workflow Preview
*(Please see the `screenshots` folder for detailed flow diagrams)*

> **Note:** This bot requires an active internet connection to query the LLM and fetch real-time data.

---

### 👨‍💻 Author
**Sujoy** *B.Tech Student, IIIT Ranchi* *Project created for Hackathon 2026*

