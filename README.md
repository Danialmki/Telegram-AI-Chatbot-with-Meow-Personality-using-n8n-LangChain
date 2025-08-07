# Telegram-AI-Chatbot-with-Meow-Personality-using-n8n-LangChain
This project is an interactive Telegram chatbot built using n8n, integrated with LangChain AI Agent, Groq LLM, and Telegram API. It features a quirky AI character that responds with “meow” by default — except when triggered by a specific phrase.

🔧 Features
	•	Telegram Bot Integration: Listens for messages using a Telegram Trigger.
	•	LangChain AI Agent: Handles the logic and system behavior using a custom prompt.
	•	Groq Chat Model: Powers the chatbot’s responses using Groq’s LLM.
	•	Memory Support: Keeps session-based context using a memory buffer window.
	•	Custom Behavior:
	•	Default response is playful “meow” variations.
	•	If a user types I like pussy, the AI drops the cat persona and provides a normal AI response (as defined in the system prompt).

🗂 Components
	•	Telegram Trigger: Starts the workflow when a message is received.
	•	AI Agent: Controls behavior and uses prompt logic via LangChain.
	•	Groq Chat Model: Provides AI-generated responses.
	•	Simple Memory: Stores previous conversation context (per user).
	•	Send a text message: Sends the final AI-generated reply back to the user on Telegram.

🚀 Use Cases
	•	Fun chatbots with custom personalities
	•	Prompt engineering experiments
	•	LangChain + Groq integration demos
	•	Telegram AI automation with memory

