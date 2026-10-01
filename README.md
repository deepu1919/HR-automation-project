# HR Automation Project

Automated HR feedback collection and daily summary delivery using n8n.

## What it does
- Collects daily feedback from employees via form / chat trigger
- Stores responses in Google Sheets
- Sends daily summary to HR via Slack at 6 PM
- Uses AI to summarize feedback trends

## Tools Used
- n8n (workflow automation)
- Slack API
- Google Sheets

## Workflow File
`HR automation workflow.json` - Import this in n8n to use

## How to Use
1. Import JSON into n8n
2. Connect your Slack and Google credentials
3. Activate workflow
