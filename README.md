## Project Overview
🚀 Live Demo: https://siyu-guo18.github.io/accountiq-ai-agent/AccountIQ%20Agent.html 

Customer information is fragmented across meeting notes, CRM tickets, emails, and individual account managers' memories. AccountIQ acts as a centralized knowledge agent that reads incoming updates, maintains a structured customer profile, and generates different types of briefs depending on who needs the information and why.

## What It Does
* Consolidates customer updates from meeting notes, CRM tickets, email summaries, and account manager notes into a unified customer profile
* Automatically identifies key contacts, priorities, risks, opportunities, and recommended next actions
* Generates stakeholder-specific briefs for new team member onboarding, internal meetings, customer call preparation, and executive reporting
* Maintains a centralized source of customer knowledge to improve team alignment and customer communication
* Exports briefs as PDF, email draft, or clipboard copy


## Agent Architecture
```text
Meeting Notes (Gong, Otter.ai) CRM Updates (HubSpot)
Email Conversations (Gmail) Account Manager Notes
        ↓
Zapier / Make / n8n
        ↓
AccountIQ Agent
        ↓
Customer Profile
        ↓
Stakeholder Briefs
```

## Tools
* Claude-Assisted Development
* HTML / CSS / JavaScript
* Gemini API

