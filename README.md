# 🤖 AI Email Assistant

An AI-powered email automation workflow built with n8n, Gmail, and Google Gemini.

The automation monitors incoming Gmail messages, analyzes them with Gemini, categorizes them, determines urgency, and generates professional draft replies.

## 🚀 Features

- 📩 Detects incoming Gmail messages
- 🤖 Analyzes emails using Google Gemini
- 🏷️ Categorizes emails
- 🚦 Determines email urgency
- ✍️ Generates professional replies
- 🚫 Filters spam emails
- 📝 Creates Gmail drafts instead of automatically sending emails
- 🔀 Uses conditional workflow logic
- ⚙️ Parses AI output into structured JSON

## 🧠 Workflow

```text
Gmail - New Email
        ↓
Gemini - Analyze Email
        ↓
Code - Parse AI Response
        ↓
IF - Ignore Spam
        ↓
Gmail - Create Draft