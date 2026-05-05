# 🤖 Simple Chart Bot (AI Chatbot using n8n)

## 📄 Description
Simple Chart Bot is an AI-powered chatbot built using **n8n**, a no-code/low-code workflow automation tool. This chatbot leverages an **AI Agent integrated with OpenAI (gpt-4o-mini)** to process user queries and generate intelligent, context-aware responses.
The workflow is triggered when a user sends a chat message. The AI Agent processes the request using a connected language model and maintains conversation context using a memory buffer. This project demonstrates how **Generative AI + workflow automation** can be combined to build scalable chatbot systems without heavy coding.

## 🚀 Features
- 🤖 AI-powered conversational chatbot  
- ⚡ Real-time response generation  
- 🧠 Context retention using memory buffer  
- 🔄 Automated workflow using n8n  
- 🔗 Integration with OpenAI Chat Model (gpt-4o-mini)  
- 🧩 No-code / low-code implementation  

## 🛠️ Tech Stack
- **n8n** – Workflow automation  
- **OpenAI GPT-4o-mini** – Language model  
- **AI Agent Node** – Handles reasoning & responses  
- **Memory Buffer Window** – Maintains conversation context  

## 🔁 Workflow Overview
1. User sends a message  
2. **Chat Trigger Node** activates workflow  
3. **AI Agent** receives input  
4. **OpenAI Chat Model (gpt-4o-mini)** processes the query  
5. **Memory Node** stores conversation context  
6. AI Agent generates response  
7. Response is returned to the user  

