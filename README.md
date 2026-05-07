# n8n Automation Workflows Portfolio

Portfolio of n8n automation workflows built for AI agents, business process automation, social media operations, CRM updates, reporting, and productivity systems.

This repository demonstrates practical automation work across real-world use cases: connecting APIs, processing data, using AI models, routing leads and messages, generating summaries, updating databases, and sending notifications across tools like Gmail, Google Sheets, Slack, Notion, Google Drive, Airtable, LinkedIn, Instagram, Reddit, Mailchimp, and OpenAI.

## What This Portfolio Shows

- End-to-end n8n workflow design
- AI agent and OpenAI workflow integration
- API automation and webhook-based systems
- Gmail, Google Sheets, Slack, Notion, Drive, Airtable, and CRM-style automations
- Lead capture, customer feedback, reporting, and content automation
- Data extraction, transformation, routing, and notification workflows
- Clean workflow documentation and GitHub-ready project organization
- Security-aware publishing with credentials and IDs removed

## Automation Areas

| Area | Example capabilities |
| --- | --- |
| AI Agents | Customer feedback agents, Slack responders, PRD-to-task agents, AI content generation |
| Business Operations | Invoice parsing, reporting, feedback collection, Gmail labeling, Google Sheets updates |
| Social Media Automation | LinkedIn posting, Instagram DM replies, Twitter/X posting, Reddit research, YouTube insights |
| Data and Reporting | Sentiment analysis, review monitoring, news summaries, chart generation, structured exports |
| Integrations | OpenAI, Gmail, Google Sheets, Slack, Notion, Google Drive, Airtable, Mailchimp, Reddit, LinkedIn, Instagram APIs |

## Featured Workflows

| Workflow | Use case | File |
| --- | --- | --- |
| AI LinkedIn AutoPoster | Generates AI-assisted LinkedIn post ideas from web research and publishes them to LinkedIn. | [View JSON](workflows/ai-linked-in-auto-poster.json) |
| Brand Mentions Monitor | Monitors brand mentions across Reddit, search, Slack, and Google Sheets for quick follow-up. | [View JSON](workflows/brand-mentions-monitor.json) |
| Customer FeedBack Agent | Collects customer feedback, routes it through an AI agent, and sends structured updates to Airtable, Gmail, or Slack. | [View JSON](workflows/customer-feed-back-agent.json) |
| E-commerce AI Agent - Weekly Reviews | Summarizes Amazon and Daraz review signals into sentiment insights and email-ready reports. | [View JSON](workflows/e-commerce-ai-agent-weekly-reviews-amazon-and-daraz.json) |
| Full Stack App Backend with n8n | Webhook-based AI backend workflow for app prototypes using n8n with Lovable, Firebase, or Supabase. | [View JSON](workflows/full-stack-app-with-n8n-plus-loveable-or-firebase-plus-supabase.json) |
| Gmail Labeling AI Agent | Classifies incoming Gmail messages with AI and applies labels automatically. | [View JSON](workflows/gmail-labeling-ai-agent.json) |
| Gmail to Google Sheets | Captures Gmail data and appends structured rows into Google Sheets. | [View JSON](workflows/gmail-to-google-sheets.json) |
| Instagram DM Auto-Responder | Receives Instagram DM events and sends AI-assisted Graph API responses. | [View JSON](workflows/instagram-dm-auto-responder.json) |
| Instagram Leads to Sheets/Airtable | Pulls Instagram lead data through the Graph API and stores it in Sheets or Airtable. | [View JSON](workflows/instagram-leads-to-sheets-airtable-via-ig-graph-api.json) |
| Invoice Parser Agent | Extracts invoice details from Drive PDFs, structures them with OpenAI, logs them to Sheets, and emails summaries. | [View JSON](workflows/invoice-parser-agent-drive-to-pdf-to-open-ai-to-sheets-to-email.json) |
| Mailchimp Feedback Request Agent | Sends feedback requests through Mailchimp and follows up by Gmail when needed. | [View JSON](workflows/mailchimp-feedback-request-agent.json) |
| Manual Chart PNG to Google Drive | Generates chart images from manual input and uploads PNG files to Google Drive. | [View JSON](workflows/manual-to-chart-png-to-google-drive.json) |
| News Sentiment and Summary Agent | Runs daily news ingestion, summarizes sentiment, and sends a digest by Gmail. | [View JSON](workflows/news-sentiment-and-summary-agent-daily.json) |
| Notion to Twitter/X Post with Media | Reads Notion post content and publishes media-ready posts to Twitter/X. | [View JSON](workflows/notion-to-twitter-post-with-media.json) |
| PRD to Notion Tasks Agent | Turns PRD content into structured Notion tasks with AI assistance. | [View JSON](workflows/prd-to-notion-tasks-agent.json) |
| Reddit Business Idea Research | Mines Reddit discussions for business ideas and organizes scored insights in Google Sheets and Slack. | [View JSON](workflows/reddit-business-idea.json) |
| Slack Agent Responder | Uses an AI agent to respond to Slack events with calculator, search, and knowledge tools. | [View JSON](workflows/slack-agent-responder.json) |
| Video Script TTS Processing Agent | Processes scripts into TTS-ready assets and stores generated files in Google Drive. | [View JSON](workflows/video-script-tts-processing-agent.json) |
| YouTube Top 10 Insights to Sheets | Collects YouTube insights, summarizes top results, and writes the findings to Google Sheets. | [View JSON](workflows/you-tube-top-10-insights-to-sheets.json) |

## Repository Structure

```text
.
|-- README.md
|-- .gitignore
`-- workflows/
    |-- ai-linked-in-auto-poster.json
    |-- brand-mentions-monitor.json
    |-- customer-feed-back-agent.json
    `-- ...
```

## How to Use These Workflows

1. Open n8n.
2. Import a JSON file from the `workflows/` folder.
3. Reconnect the required credentials inside your own n8n instance.
4. Replace placeholders such as `<API_KEY>`, `<EMAIL_ADDRESS>`, `<WEBHOOK_URL>`, `<DATABASE_ID>`, and `<GOOGLE_SHEET_URL>` with your own values.
5. Test each workflow before activating it in production.

## Security and Privacy

All workflow exports in this repository have been cleaned for public sharing. Sensitive values such as API keys, access tokens, credential IDs, emails, webhook URLs, Google Sheet IDs, Drive IDs, database IDs, and account-specific identifiers have been removed and replaced with placeholders.

## About Me

I build n8n automations that connect business tools, reduce manual work, and turn repeatable processes into reliable workflows. My focus areas include AI agents, API integrations, CRM and lead automation, reporting systems, social media workflows, and productivity automations.

If you are hiring for n8n automation, AI workflow automation, or no-code/low-code operations automation, this repository is a sample of the systems I can design, clean up, document, and prepare for real use.
