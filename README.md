## Project Overview
Customer information is fragmented across meeting notes, CRM tickets, emails, and individual account managers' memories. AccountIQ acts as a centralized knowledge agent that reads incoming updates, maintains a structured customer profile, and generates different types of briefs depending on who needs the information and why.

## What It Does
* Consolidates customer updates from meeting notes, CRM tickets, email summaries, and account manager notes into a unified customer profile
* Automatically identifies key contacts, priorities, risks, opportunities, and recommended next actions
* Generates stakeholder-specific briefs for new team member onboarding, internal meetings, customer call preparation, and executive reporting
* Maintains a centralized source of customer knowledge to improve team alignment and customer communication
* Exports briefs as PDF, email draft, or clipboard copy


## Agent Architecture
Meeting Notes · Email Summaries · HubSpot Tickets · AM Updates
                          ↓
              Zapier / Make / n8n (routing layer)
                          ↓
                   AccountIQ Agent
                          ↓
          Customer Profile → Stakeholder Briefs
The MVP simulates source integrations to demonstrate agent behavior. In production, HubSpot webhooks, Gmail OAuth, and meeting note APIs (Gong, Otter.ai) would feed updates automatically.


## Tools
* HTML / CSS / JavaScript
* Gemini API
* Claude-Assisted Development
