# n8n Workflow Collection

Clean, GitHub-ready n8n workflow exports with sensitive values replaced by placeholders.

## Workflows

| Workflow | File | Use case |
| --- | --- | --- |
| AI LinkedIn AutoPoster | [ai-linked-in-auto-poster.json](workflows/ai-linked-in-auto-poster.json) | Generates AI-assisted LinkedIn post ideas from web research and publishes them to LinkedIn. |
| Brand Mentions Monitor | [brand-mentions-monitor.json](workflows/brand-mentions-monitor.json) | Monitors brand mentions across Reddit, search, Slack, and Google Sheets for quick follow-up. |
| Customer FeedBack Agent | [customer-feed-back-agent.json](workflows/customer-feed-back-agent.json) | Collects customer feedback, routes it through an AI agent, and sends structured updates to Airtable, Gmail, or Slack. |
| E-commerce AI Agent - Weekly Reviews (Amazon & Daraz) | [e-commerce-ai-agent-weekly-reviews-amazon-and-daraz.json](workflows/e-commerce-ai-agent-weekly-reviews-amazon-and-daraz.json) | Summarizes weekly Amazon and Daraz review signals into sentiment insights and email-ready reports. |
| FULL STACK APP WITH N8N + LOVEABLE OR FIREBASE + SUPABASE | [full-stack-app-with-n8n-plus-loveable-or-firebase-plus-supabase.json](workflows/full-stack-app-with-n8n-plus-loveable-or-firebase-plus-supabase.json) | Webhook-based AI backend workflow for full-stack app prototypes using n8n with Lovable, Firebase, or Supabase. |
| Gmail -> Google Sheets | [gmail-to-google-sheets.json](workflows/gmail-to-google-sheets.json) | Captures Gmail data and appends structured rows into Google Sheets. |
| Gmail Labeling AI Agent | [gmail-labeling-ai-agent.json](workflows/gmail-labeling-ai-agent.json) | Classifies incoming Gmail messages with AI and applies labels automatically. |
| Instagram DM Auto-Responder | [instagram-dm-auto-responder.json](workflows/instagram-dm-auto-responder.json) | Receives Instagram DM events and sends AI-assisted Graph API responses. |
| Instagram Leads -> Sheets/Airtable (via IG Graph API) | [instagram-leads-to-sheets-airtable-via-ig-graph-api.json](workflows/instagram-leads-to-sheets-airtable-via-ig-graph-api.json) | Pulls Instagram lead data through the Graph API and stores it in Sheets or Airtable. |
| Invoice Parser Agent (Drive -> PDF -> OpenAI -> Sheets -> Email) | [invoice-parser-agent-drive-to-pdf-to-open-ai-to-sheets-to-email.json](workflows/invoice-parser-agent-drive-to-pdf-to-open-ai-to-sheets-to-email.json) | Extracts invoice details from Drive PDFs, structures them with OpenAI, logs them to Sheets, and emails summaries. |
| Mailchimp Feedback Request Agent | [mailchimp-feedback-request-agent.json](workflows/mailchimp-feedback-request-agent.json) | Sends feedback requests through Mailchimp and follows up by Gmail when needed. |
| Manual -> Chart PNG -> Google Drive | [manual-to-chart-png-to-google-drive.json](workflows/manual-to-chart-png-to-google-drive.json) | Generates chart images from manual input and uploads PNG files to Google Drive. |
| News Sentiment & Summary Agent (Daily) | [news-sentiment-and-summary-agent-daily.json](workflows/news-sentiment-and-summary-agent-daily.json) | Runs daily news ingestion, summarizes sentiment, and sends a digest by Gmail. |
| Notion -> Twitter (Post with Media) | [notion-to-twitter-post-with-media.json](workflows/notion-to-twitter-post-with-media.json) | Reads Notion post content and publishes media-ready posts to Twitter/X. |
| PRD to Notion Tasks Agent | [prd-to-notion-tasks-agent.json](workflows/prd-to-notion-tasks-agent.json) | Turns PRD content into structured Notion tasks with AI assistance. |
| REDDIT BUSINESS IDEA | [reddit-business-idea.json](workflows/reddit-business-idea.json) | Mines Reddit discussions for business ideas and organizes scored insights in Google Sheets and Slack. |
| Slack Agent Responder | [slack-agent-responder.json](workflows/slack-agent-responder.json) | Uses an AI agent to respond to Slack events with calculator, search, and knowledge tools. |
| Video Script TTS Processing Agent | [video-script-tts-processing-agent.json](workflows/video-script-tts-processing-agent.json) | Processes scripts into TTS-ready assets and stores generated files in Google Drive. |
| YouTube Top 10 Insights -> Sheets | [you-tube-top-10-insights-to-sheets.json](workflows/you-tube-top-10-insights-to-sheets.json) | Collects YouTube insights, summarizes top results, and writes the findings to Google Sheets. |

## Using These Workflows

1. Import a workflow JSON file from the `workflows/` folder into n8n.
2. Reconnect credentials in n8n.
3. Replace placeholder IDs, URLs, and addresses with values from your own accounts.
4. Test each workflow in a safe environment before activating it.

## Sanitization

The exports replace API keys, emails, tokens, webhook URLs, Google Sheet IDs, Drive IDs, credential IDs, database IDs, and related account identifiers with placeholders such as `<API_KEY>`, `<EMAIL_ADDRESS>`, `<WEBHOOK_URL>`, and `<CREDENTIAL_ID>`.
