# 🌦️ Weather Bot using n8n and Telegram

## 📌 Project Overview

This project is an automated Weather Notification Bot developed using n8n. It retrieves real-time weather information using the Open-Meteo API, processes the weather data, and sends formatted weather updates directly to Telegram.

## 🛠️ Technologies Used

- n8n – Workflow Automation
- Open-Meteo API – Weather Data Retrieval
- Telegram Bot API – Weather Notifications
- HTTP Request – API Integration
- JavaScript – Data Processing and Message Formatting

## ⚙️ Workflow Architecture

The automation consists of the following steps:

1. **Schedule Trigger:** Automatically triggers the workflow at the configured time.
2. **HTTP Request:** Fetches weather information from the Open-Meteo API.
3. **Build Message:** Processes and formats the weather information into a readable message.
4. **Telegram Send Message:** Sends the formatted weather notification to Telegram.

## ✨ Key Features

- Automated weather information retrieval.
- Integration with an external weather API.
- Dynamic weather message formatting.
- Telegram-based weather notifications.
- Scheduled workflow execution.

## 📸 Project Screenshots

Screenshots of the workflow, node configurations, and execution results are available in the `screenshots` folder.

## 🚀 How to Run the Project

1. Download the workflow JSON file from the `workflows` folder.
2. Open your n8n instance.
3. Select Import from File.
4. Import the downloaded JSON workflow.
5. Configure your Telegram bot credentials.
6. Configure the required weather API parameters and location.
7. Activate the workflow.
8. Receive weather notifications through Telegram.

## 🌐 API Reference

Open-Meteo Weather API: https://open-meteo.com/

## 👩‍💻 Author

**Jeevidha A**

GitHub: https://github.com/Jeevidha-A
