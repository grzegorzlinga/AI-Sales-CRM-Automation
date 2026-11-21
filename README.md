# AI Sales CRM Automation System

### Intelligent Lead Management with Make, Airtable & OpenAI

An AI-powered sales CRM automation designed to help businesses capture, organize, qualify, and manage incoming sales leads.

The system combines Make.com, Airtable, and the OpenAI API to automate lead processing, reduce repetitive data entry, and support sales teams with AI-generated insights and draft responses.

## Key Features

- **Automated Lead Capture** — Receives incoming lead information through a Make webhook.
- **Duplicate Detection** — Checks existing CRM records using external lead identifiers.
- **AI Lead Scoring** — Evaluates sales potential on a 0–100 scale.
- **Priority Classification** — Assigns Low, Medium, or High priority.
- **AI Lead Summaries** — Generates concise summaries of incoming inquiries.
- **AI Reply Drafts** — Prepares personalized responses for human review.
- **Contact & Company Management** — Organizes related records in Airtable.
- **Structured CRM Data** — Stores lead information and AI analysis in a centralized database.
- **Webhook Responses** — Returns structured responses to incoming requests.

## Technology Stack

| Technology | Purpose |
|---|---|
| Make.com | Workflow orchestration and automation |
| Airtable | CRM database and record management |
| OpenAI API | AI lead analysis and response generation |
| Webhooks | Incoming lead capture |
| JSON | Structured data exchange |

## Workflow Overview

1. A new lead is submitted through a webhook.
2. Make validates the incoming information.
3. Airtable is searched for an existing lead.
4. Duplicate leads are identified.
5. New leads are analyzed using OpenAI.
6. AI generates a score, priority, summary, and reply draft.
7. Company and contact records are checked.
8. Lead information is saved to the CRM.
9. The workflow returns a structured response.

## Airtable CRM Structure

The CRM uses six interconnected tables:

1. Leads
2. Companies
3. Contacts
4. Activities
5. Sales Reps
6. Automation Logs

This structure supports organized lead management and provides a foundation for further sales automation.

## Business Applications

The system can support businesses that receive inquiries through websites, contact forms, or other connected sources.

Potential benefits include:

- Less repetitive manual data entry
- More consistent lead qualification
- Better visibility into incoming inquiries
- Faster preparation of sales responses
- Centralized customer and company information

## Project Documentation

This repository includes:

- **Portfolio Case Study (PDF)** — Business context, solution overview, and project presentation.
- **Architecture (PDF)** — System architecture and workflow design.
- **Sanitized Make Blueprint (JSON)** — A portfolio-safe version of the automation scenario.

## Implementation Notes

The included blueprint is intended for demonstration and technical review.

To deploy a working instance, users must configure their own Make connections, Airtable database, webhook, and OpenAI API access.

The blueprint does not include active API credentials.

## Customization

The architecture can be adapted to different lead sources, CRM requirements, scoring criteria, and business processes.

## Author

**Grzegorz Linga**

AI Automation Developer

Specializing in Make.com, n8n, Airtable, OpenAI API integrations, webhooks, and business process automation.

---

*Portfolio project demonstrating practical AI-powered CRM automation and workflow integration.*
