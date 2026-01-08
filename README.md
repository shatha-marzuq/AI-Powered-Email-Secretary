# AI-Powered Email Secretary & Automator 🤖📧

## 📝 Overview
This project is an intelligent automation system built using **n8n**. It streamlines email management by monitoring a Gmail inbox, analyzing content using **Google Gemini AI**, and organizing key information into **Google Sheets** for quick review.

## ✨ Key Features
* **Real-Time Monitoring**: Automatically triggers when a new email arrives in Gmail.
* **AI Summarization**: Generates a concise summary of the email content using the Gemini-1.5-Flash model.
* **Smart Triage**: Categorizes emails by importance (Urgent, Routine, Not Important).
* **Automated Data Logging**: Extracts and formats the sender's info, summary, status, and date into structured columns.

## 🛠️ Tech Stack
* **n8n**: Workflow automation and logic orchestration.
* **Google Gemini AI**: Natural Language Processing (NLP) for summarization and classification.
* **Google Sheets API**: Cloud-based storage for the processed data.
* **JavaScript**: Custom logic for date formatting and JSON data parsing.

## 📸 Proof of Concept
### The Automation Workflow
![Workflow Screenshot](رابط_صورة_المسار_هنا)
*Description: The integrated n8n workflow connecting Gmail, Gemini AI, and Google Sheets.*

### Result in Google Sheets
![Sheets Screenshot](رابط_صورة_الجدول_هنا)
*Description: Sample output showing how emails from various sources (Coursera, noon Food, etc.) are successfully processed.*
