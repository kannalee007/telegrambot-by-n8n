🤖 Telegram Chatbot using Gemini AI (n8n Workflow)

📌 Overview

This project is a Telegram chatbot built using n8n workflows, integrated with the Google Gemini Chat Model to generate intelligent responses.

Instead of writing backend code, the bot is created using visual automation, making it easy to design, modify, and scale.

⸻

🚀 Features
	•	💬 Real-time Telegram chat responses
	•	🧠 AI-powered replies using Gemini
	•	🔄 Fully automated workflow via n8n
	•	⚡ No-code / low-code implementation
	•	🔗 Easy to extend with additional nodes

⸻

🧰 Tech Stack
	•	n8n (Workflow Automation Tool)
	•	Telegram Bot API
	•	Google Gemini API (Generative AI)

⸻

🧩 Workflow Architecture

The bot works through a sequence of nodes in n8n:
	1.	Telegram Trigger Node
	•	Listens for incoming messages
	2.	HTTP Request / Gemini Node
	•	Sends user input to Gemini API
	3.	Function / Processing Node (optional)
	•	Formats request/response
	4.	Telegram Send Message Node
	•	Sends AI-generated reply back to user
