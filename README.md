## Project Overview
Customer information is fragmented across meeting notes, CRM tickets, emails, and individual account manager memory. AccountIQ acts as a centralized knowledge agent that reads incoming updates, maintains a structured customer profile, and generates different types of briefs depending on who needs the information and why.

## What It Does
Displays incoming customer updates from simulated sources (Meeting Notes, HubSpot Tickets, Email Summaries, AM Updates)
Processes updates into a structured customer profile organized by contacts, priorities, risks, and opportunities
Generates four stakeholder-specific brief types from the same profile:

New Team Member — narrative context, key contacts, what to watch out for, first week priorities
Internal Meeting — open issues with owners, discussion questions, action items
Customer Call Prep — recommended talking order, verbatim questions to ask, risks to watch
Executive Summary — bottom line first, business risk, revenue impact, clear directive


Supports account manager field notes via an add update flow with automated summarization and categorization
Exports briefs as PDF, email draft, or clipboard copy


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
