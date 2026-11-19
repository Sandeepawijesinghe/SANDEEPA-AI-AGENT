# 🤖 SANDEEPA AI AGENT
### An Intelligent AI-Powered Telegram Assistant

**SANDEEPA AI AGENT** is an AI Agent automation project built using **n8n, OpenRouter, and Telegram**. It demonstrates how Large Language Models (LLMs) can interact with external tools, retrieve information, perform calculations, and maintain conversational context.

The project combines AI reasoning, tool integration, and workflow automation to create an interactive Telegram-based AI assistant.

---

## 🧠 Artificial Intelligence Capabilities

This project demonstrates practical applications of AI Agent Engineering:

- **LLM Integration:** Connects an AI language model through OpenRouter.
- **AI Agent:** Processes natural-language messages and determines how to respond.
- **Tool Calling:** Uses external tools to retrieve information and perform calculations.
- **Conversational Memory:** Maintains conversation context using Simple Memory.
- **Workflow Automation:** Connects AI components through n8n.
- **Telegram Integration:** Provides a conversational interface through a Telegram bot.

## 🚀 Key Features

| Feature | Description |
|---|---|
| AI Agent | Understands and processes user messages |
| OpenRouter Chat Model | Provides the language model |
| Wikipedia Tool | Retrieves information from Wikipedia |
| Calculator Tool | Performs mathematical calculations |
| Simple Memory | Maintains conversational context |
| Telegram Bot | Receives questions and sends AI responses |
| n8n Automation | Connects and manages the workflow |

## 🏗️ System Architecture

The workflow follows this architecture:

```text
              USER
                |
                v
        TELEGRAM TRIGGER
                |
                v
            AI AGENT
                |
       +--------+--------+
       |        |        |
       v        v        v
   OpenRouter  Memory  AI Tools
                       /      \
                      v        v
                 Wikipedia  Calculator
                      \        /
                       \      /
                        v    v
                    AI RESPONSE
                         |
                         v
                 TELEGRAM MESSAGE
                         |
                         v
                        USER
```

## 🛠️ Technology Stack

| Technology | Role |
|---|---|
| n8n | AI workflow automation |
| OpenRouter | LLM connectivity |
| Telegram Bot API | User interaction |
| Wikipedia | External information retrieval |
| Calculator | Mathematical operations |
| Simple Memory | Conversation context |

## 💡 Example Use Case

A user can send a question through Telegram:

**Example Prompt:**

> Find the population of Sri Lanka using Wikipedia, divide it by 2, and tell me the result.

The AI Agent can:
1. Understand the user's request.
2. Use the Wikipedia tool to retrieve population information.
3. Use the Calculator tool to perform the calculation.
4. Generate a response.
5. Send the result back through Telegram.

## 📂 Project Structure

```text
SANDEEPA-AI-AGENT/
│
├── SANDEEPA_AI_AGENT_GitHub.json
│
└── README.md
```

## ⚙️ Installation & Setup

### Prerequisites

- An n8n instance (Community Edition)
- A Telegram Bot created using BotFather
- An OpenRouter account and API key
- An internet connection
- A public HTTPS webhook URL for Telegram Trigger

### Step 1 — Import Workflow

1. Open your n8n instance.
2. Create a new workflow.
3. Select **Import from File**.
4. Import `SANDEEPA_AI_AGENT_GitHub.json`.

### Step 2 — Configure Credentials

Configure the following credentials in n8n:

- OpenRouter API credentials
- Telegram API credentials

### Step 3 — Configure Telegram Webhook

Make your n8n instance reachable through a public HTTPS URL and configure the webhook URL appropriately.

### Step 4 — Test the AI Agent

Send a message to your Telegram bot and verify that the AI Agent can respond using its connected tools.

---

## 🔐 Security

- API keys and Telegram bot tokens are not included in this repository.
- Credentials must be configured separately in n8n.
- Never commit private API keys, access tokens, or secrets to GitHub.

## 🎯 Project Objectives

This project was developed to explore and practice:

- Artificial Intelligence (AI)
- AI Agent Engineering
- Large Language Models (LLMs)
- Tool Calling and Integration
- Conversational Memory
- Workflow Automation
- API Integrations

## 🔮 Future Improvements

- Integrate additional AI tools.
- Improve long-term memory capabilities.
- Add document and file analysis.
- Introduce web search capabilities.
- Develop a more advanced multi-agent workflow.
- Improve error handling and monitoring.

## 👨‍💻 Developer

**Sandeepa Wijesinghe**

Aspiring AI Engineer | Mechatronics & Robotics Enthusiast

Interested in Artificial Intelligence, Agentic AI, Generative AI, Robotics, and Intelligent Automation.

**GitHub:** [Sandeepawijesinghe](https://github.com/Sandeepawijesinghe)

---

*Building intelligent systems, one project at a time.* 🤖

⭐ If you find this project interesting, consider giving this repository a star!


## 📸 Workflow Preview

![SANDEEPA AI AGENT Workflow](%7B68A83EC6-B404-41D9-BF99-3D298EEC817E%7D.png)
