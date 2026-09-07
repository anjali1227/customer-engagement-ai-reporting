# Customer Engagement AI Reporting

An automated customer engagement analytics workflow built using n8n,
JavaScript and OpenAI to analyze account-level email engagement and
generate actionable Customer Success insights.

## Problem

Customer Success teams and customer success managers often spend significant time manually analyzing
email engagement metrics and preparing account-level reports.

This workflow automates that process by transforming raw engagement data
into an AI-generated customer health report and delivering the report
directly via email.

## Workflow

<img width="770" height="371" alt="Screenshot 2026-09-07 155448" src="https://github.com/user-attachments/assets/0ab41ed2-46c3-43c4-bcd5-d3a832000bdb" />


Manual Trigger
→ Data Input
→ JavaScript Processing
→ AI Agent
→ HTML Report Formatter
→ Gmail

## What the workflow does

- Processes customer engagement data
- Calculates email engagement metrics
- Identifies high and low performing content categories
- Analyzes unsubscribe activity
- Assigns an account health status
- Generates key business insights using an LLM
- Recommends actions for Customer Success teams
- Automatically formats the output as an HTML email
- Delivers the report through Gmail

## AI Analysis

The AI Agent evaluates:

- Overall engagement
- Email open rate
- Best-performing category
- Weakest-performing category
- Unsubscribe activity
- Key business insights
- Recommended Customer Success actions

## Example Output

<img width="464" height="332" alt="Screenshot 2026-09-07 155226" src="https://github.com/user-attachments/assets/a0ed2e23-8e7b-43a2-9c50-80a46b0135c3" />
<img width="427" height="276" alt="Screenshot 2026-09-07 155247" src="https://github.com/user-attachments/assets/47d22d92-ee8d-45f5-a580-c1199fd2e962" />



## Tech Stack

- n8n
- JavaScript
- OpenAI
- Gmail
- Excel / CSV
- LLM-based analytics

## Key Features

### Automated Analysis

Raw engagement data is transformed into account-level insights without
manual analysis.

### AI-Powered Recommendations

The workflow converts engagement metrics into practical actions for
Customer Success teams.

### Automated Reporting

The final report is formatted as an HTML email and delivered automatically.

## Setup

1. Import the n8n workflow from `workflow/`.
2. Connect your OpenAI credentials.
3. Connect your Gmail account.
4. Replace the sample data with your own dataset.
5. Configure the email recipient.
6. Run the workflow.

## Privacy

The repository contains only synthetic/sample data.
No customer information, credentials, API keys, or proprietary company
data are included.

## Future Improvements

- Schedule automated weekly reports
- Generate reports for multiple accounts
- Store historical engagement metrics
- Add trend analysis
- Add Slack/Microsoft Teams notifications
- Add customer health scoring
- Build a Customer Success dashboard
