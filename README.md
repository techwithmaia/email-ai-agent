# Email AI Agent

Streamline your inbox with AI-powered workflows that categorize incoming emails, draft intelligent replies, and notify your team of key messages. Built in n8n, this automation helps reduce manual triage, accelerate response times, and keep your communication organized.

---

## Features

- **Gmail Integration**: Monitors your inbox for new unread emails.
- **Labeling Automation**: Applies Gmail labels based on email categories like:
  - Internal
  - Customer Support
  - Promotions
  - Admin/Finance
  - Sales Opportunities
- **AI-Powered Classification**: Uses OpenAI models to classify and summarize email content.
- **Drafting Responses**: Automatically drafts replies based on email context.
- **Slack Notifications**: Sends updates to a Slack channel for sales opportunities and internal drafts.

---

## File Content

- `Email_AI_Agent.json`

---

## Categories & Logic

Emails are classified into the following categories:

| Category          | Purpose |
|-------------------|---------|
| **Internal**       | Internal staff emails (e.g., support requests, inquiries) |
| **Customer Support** | Communication with existing customers |
| **Promotions**     | Marketing emails, newsletters |
| **Admin/Finance**  | Invoices, billing, financial updates |
| **Sales Opportunities** | Leads or business opportunities |

Each label triggers specific downstream nodes to analyze, draft, and notify accordingly.

---

## Created by Maia P.

**AI Automation Engineer**   
Helping businesses scale smart systems with ai automation and crm solutions.

> Let’s build your custom system

