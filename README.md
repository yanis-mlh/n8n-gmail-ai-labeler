📧 AI Smart Inbox: Intelligent Gmail Labeling Agent
Inspired by high-performance productivity frameworks.
This repository contains a specialized n8n workflow that transforms your cluttered Gmail into a structured CRM-ready inbox using LLM-based categorization.

🌟 Key Features
Contextual Analysis: Goes beyond simple keyword matching; it understands the intent of the sender.

Dynamic Labeling: Automatically assigns labels (Lead, Pub, Famille) directly in your Gmail interface.

Zero-Inbox Strategy: Designed to help professionals focus only on high-value "Lead" emails while filtering noise.

Structured Output: Uses a LangChain-based output parser to ensure 100% reliability in label application.

🛠️ Workflow Architecture
Gmail Watcher: Monitors incoming mail at scheduled intervals.

AI Brain (LLM Chain): Analyzes the body text using GPT-4 (or Gemini 1.5 Flash for a free tier).

JSON Formatter: Converts AI reasoning into a clean, machine-readable format.

Action Node: Executes the addLabel command via Gmail API.

🚀 Getting Started
Import: Upload the Label mails.json file into your n8n instance.

Credentials:

Setup Gmail OAuth2 (Google Cloud Console).

Add your OpenAI API Key (or swap the node for Gemini).

Customization: Edit the "Basic LLM Chain" prompt to add your own business-specific labels (e.g., "Urgent", "Support", "Invoice").

Maintained by Yanis - AI Automation Engineer
