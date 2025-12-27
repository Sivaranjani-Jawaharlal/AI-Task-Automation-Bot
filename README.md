**AI Task Automation Bot (n8n)**

An AI-powered productivity assistant built using n8n, integrating Telegram, Gmail, and Todoist.
The bot uses an AI Agent with memory to intelligently manage tasks and emails through natural language commands.

**Features**

AI Agent powered by OpenRouter (LLM-based decision making)

Telegram chatbot interface

**Gmail automation:**

Read emails

Reply to emails

Draft emails

Send emails

Add labels

Mark emails as unread

**Todoist task management:**

Create tasks

Update tasks

Move tasks between projects

Close / reopen / delete tasks

Fetch single or multiple tasks

🧠 Conversational memory using Memory Buffer

⏰ Scheduled daily & weekly automation summaries

**Tech Stack**

n8n – Workflow automation

AI Agent (LangChain) – Decision making

OpenRouter – LLM integration

Telegram Bot API – User interaction

Gmail API – Email operations

Todoist API – Task management

Memory Buffer – Context-aware responses

**Workflow Overview**

The workflow consists of:

Telegram Trigger to receive user commands

Schedule Triggers for automated summaries

AI Agent to understand intent and route actions

Tool integrations (Gmail & Todoist) controlled by the AI Agent

Memory node to retain conversation context

Telegram response node to send results back to the user

<img width="1231" height="612" alt="n8n" src="https://github.com/user-attachments/assets/f0ae71c4-dff9-49a7-aaa2-6a14117c6df5" />

**Setup Instructions**
Prerequisites

n8n (Cloud or Self-hosted)

Telegram Bot Token

Gmail OAuth credentials

Todoist OAuth credentials

OpenRouter API key

Steps

Clone this repository:

git clone https://github.com/your-username/AI-Task-Automation-Bot.git


Open n8n → Import workflow

Import workflow/Task_Bot_AI.json

Configure credentials:

Telegram

Gmail

Todoist

OpenRouter

Activate the workflow

Start chatting with the bot via Telegram 

**Security Note**

All API credentials are managed via n8n credentials

No sensitive keys are stored in this repository
