# Telegram-Gmail AI Assistant

## About The Project
This project is an automated workflow built using n8n. The system acts as a smart personal assistant via the Telegram app, connecting a Gmail account with an AI model (Groq) to facilitate email management through a simple chat interface.

## Key Features
- Send Emails: Send emails directly by typing a command in Telegram.
- Read Latest Messages: Fetch and display the latest emails in a neat table format showing Date, Sender, Subject, and a 
  snippet of the message.
- Scheduled Summaries: A scheduled system that runs at the end of the day to read emails, analyze them, and send a summary of the most important alerts and events via Telegram.

Tech Stack
- n8n: For building the workflow and data flow automation.
- Telegram API: As the user interface.
- Gmail API: For accessing the inbox (reading and sending).
- Groq Chat Model: As the AI Agent to understand user commands and analyze text.
- Simple Memory: To save the chat context with the bot.

System Architecture
The following diagram shows how the nodes connect to each other to create this system:
<img width="1037" height="550" alt="Screenshot 2026-08-23 110204" src="https://github.com/user-attachments/assets/e7cea305-b476-4356-8a6a-2a1d49ff7c63" />

Live Demo / Output
1. Sending emails and reading the inbox:
<img width="1143" height="798" alt="Screenshot 2026-08-23 110602" src="https://github.com/user-attachments/assets/28b347aa-56df-4678-86db-30389b834965" />

2. Automatic alerts and summaries:
<img width="1107" height="849" alt="image" src="https://github.com/user-attachments/assets/6eefde10-5b08-4562-8fab-ecbd9243c753" />


Repository Files
You can find the workflow.json file in this repository, which can be imported directly into any n8n environment to run the system.
