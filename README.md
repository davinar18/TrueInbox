# TrueInbox

A human-friendly AI tool that helps users detect suspicious, manipulative, or potentially scammy messages in their inbox. Powered by natural language understanding, TrueInbox classifies emails or DMs based on tone, intent, and red flags commonly used in phishing or social engineering.

## 🎯 Objective
To help users confidently identify risky or deceptive messages by:
- Analyzing the message tone and intent
- Providing a risk score and reasoning
- Flagging persuasive or manipulative language patterns

## 🛠 Tech Stack
- **Backend**: Flask
- **LLM API**: Open-source Hugging Face models

## 🔍 AI Concepts Used
- Prompt engineering for tone + deception detection
- Risk scoring based on LLM output classification
- Behavior signal extraction (money requests, vague authority, urgency)

## 💡 Example
**User Input:**
> "Hello, we reviewed your resume. Please send a $50 fee to proceed with your application."

**TrueInbox Output:**
- ❌ **Risk Level:** High (91%)
- **Reason:** Detected urgency, financial request, vague sender identity
- **Classification:** Likely Scam

## ✅ Features
- Paste a message and instantly get a classification (Safe / Suspicious / Scam)
- Risk score breakdown
- Clear explanation of red flags found in the message
- Minimal setup using Hugging Face API
