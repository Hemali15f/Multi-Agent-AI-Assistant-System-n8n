# Multi-Agent Personal Assistant System

A powerful AI-driven multi-agent automation system built with **n8n**, **Google Gemini**, **Telegram**, **Gmail**, **Google Calendar**, **Airtable**, and **Tavily Search**. This system acts as a personal AI assistant capable of managing emails, calendars, contacts, content creation, and web searches through a single Telegram interface. 

---

## 🚀 Features

### 📧 Email Management Agent

* Send professional emails
* Create email drafts
* Read emails from Gmail
* Reply to emails
* Label emails
* Mark emails as unread

### 📅 Calendar Management Agent

* Create events
* Create events with attendees
* View scheduled events
* Update existing events
* Delete calendar events

### 👥 Contact Management Agent

* Store contacts in Airtable
* Update contact details
* Search existing contacts
* Retrieve contact information automatically

### ✍️ Content Creation Agent

* Generate blog posts
* Research topics using web search
* Create SEO-friendly content
* Include source citations

### 🌐 Web Search Agent

* Search real-time information using Tavily API
* Retrieve news and research data
* Provide contextual information for content generation

### 🎙️ Voice & Text Support

* Telegram voice message transcription
* Natural language interaction
* Voice-to-action automation

### 🧠 Memory Support

* Conversation memory using n8n Memory Buffer
* Context-aware interactions

---

## 🏗️ System Architecture

```text
Telegram User
      │
      ▼
Telegram Trigger
      │
      ▼
Ultimate Assistant (Router Agent)
      │
 ┌────┼────┬─────┬─────┐
 ▼    ▼    ▼     ▼     ▼
Email Calendar Contact Content Search
Agent  Agent   Agent   Agent  Agent
      │
      ▼
Telegram Response
```

---

## 🛠️ Tech Stack

* **n8n**
* **Google Gemini**
* **Telegram Bot API**
* **Gmail API**
* **Google Calendar API**
* **Airtable**
* **Tavily Search API**
* **AI Agents (LangChain Nodes)**
* **Memory Buffer**
* **JavaScript Expressions**
* **OAuth 2.0 Authentication**

---

## 📋 Workflow Overview

### Parent Agent

The Ultimate Assistant acts as the central orchestrator and decides which specialized agent should handle the user's request.

### Specialized Agents

#### Email Agent

Handles:

* Sending emails
* Draft creation
* Email retrieval
* Replies
* Label management

#### Calendar Agent

Handles:

* Event creation
* Event updates
* Event deletion
* Event lookup

#### Contact Agent

Handles:

* Contact storage
* Contact retrieval
* Contact updates

#### Content Creator Agent

Handles:

* Blog generation
* Topic research
* SEO optimization

---

## 🔄 Example Commands

### Email

```text
Send an email to John asking for project updates.
```

### Calendar

```text
Create a meeting tomorrow at 10 AM.
```

### Contacts

```text
Save Sarah's contact:
Email: sarah@example.com
Phone: +1 1234567890
```

### Blog Writing

```text
Write a blog on AI Automation in Small Businesses.
```

### Search

```text
Find the latest AI news.
```

---

## 📂 Integrations

| Service         | Purpose                        |
| --------------- | ------------------------------ |
| Telegram        | User Interface                 |
| Gmail           | Email Operations               |
| Google Calendar | Schedule Management            |
| Airtable        | Contact Database               |
| Tavily          | Internet Search                |
| Gemini          | AI Reasoning & Decision Making |

---

## 🎯 Key Highlights

* Multi-Agent Architecture
* Real-Time Automation
* Voice Command Support
* Contact-Aware Actions
* Automated Email Workflows
* Calendar Scheduling
* AI Content Generation
* Web Research Capabilities
* Memory-Based Conversations
* Telegram-Powered Interface

---

## 📈 Future Improvements

* WhatsApp Integration
* CRM Integration
* Task Management Agent
* PDF Analysis Agent
* Knowledge Base Agent (RAG)
* Meeting Summaries
* Slack Integration
* Multi-Language Support

---

## 👨‍💻 Author

**Hemali Firke**
Computer Engineering Student | AI Automation Enthusiast | Developer


---

⭐ Built to explore how AI agents can collaborate and automate real-world business workflows through a unified conversational interface.
